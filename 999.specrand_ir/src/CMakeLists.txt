cmake_minimum_required(VERSION 3.10)
project(pgdlo)

set(CMAKE_C_COMPILER gcc)
set(CMAKE_VERBOSE_MAKEFILE ON)
set(CMAKE_C_FLAGS "-g")

add_executable(${Bench}.bc main.c specrand.c specrand.h)
