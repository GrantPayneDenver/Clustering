cmake_minimum_required(VERSION 3.3)
project(Clustering)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES main.cpp Point.cpp Point.h)
add_executable(Clustering ${SOURCE_FILES})