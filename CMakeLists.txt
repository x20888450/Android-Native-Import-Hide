cmake_minimum_required(VERSION 3.20)
project("Android-Native-Import-Hide")
include_directories("${CMAKE_CURRENT_SOURCE_DIR}/src")
include_directories("${CMAKE_CURRENT_SOURCE_DIR}/single_header")
file(GLOB ANDROID-NATIVE-IMPORT-HIDE_SRC "${CMAKE_CURRENT_SOURCE_DIR}/src/*.cpp")
add_library("${PROJECT_NAME}" STATIC "${ANDROID-NATIVE-IMPORT-HIDE_SRC}")
