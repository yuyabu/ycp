cmake_minimum_required(VERSION 3.14)
project(ycp)

set(CMAKE_C_STANDARD 11)

include_directories(.)

add_executable(ycp ycp.cpp)
