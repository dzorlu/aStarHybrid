cmake_minimum_required(VERSION 3.8)
project(aStar)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES main.cpp hybrid_breadth_first.cpp hybrid_breadth_first.h)
add_executable(aStar ${SOURCE_FILES})