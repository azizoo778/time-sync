cmake_minimum_required(VERSION 3.8)
project(time_sync)

set(CMAKE_C_STANDARD 11)

set(SOURCE_FILES main.c)
SET(GCC_COVERAGE_LINK_FLAGS    "-lm")
add_executable(time_sync ${SOURCE_FILES})