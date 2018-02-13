cmake_minimum_required(VERSION 3.5)
project(tftp)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall -std=c++11")

set(SOURCE_FILES main.cpp)
add_executable(tftp ${SOURCE_FILES})