cmake_minimum_required(VERSION 3.8)
project(stackl)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES stackl.h stackl.cpp stackl-test.cpp)
add_executable(stackl ${SOURCE_FILES})