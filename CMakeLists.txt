cmake_minimum_required(VERSION 3.31)
project(CAP_lib C)

set(CMAKE_C_STANDARD 17)

add_library(CAP_lib SHARED library.c)
