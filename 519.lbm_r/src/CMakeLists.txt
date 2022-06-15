cmake_minimum_required(VERSION 3.10)
project(pgdlo)

set(CMAKE_C_COMPILER gcc)
set(CMAKE_VERBOSE_MAKEFILE ON)
set(CMAKE_C_FLAGS "-g")
set(CMAKE_C_FLAGS "-lm")

add_executable(${Bench}.bc config.h lbm_1d_array.h lbm.c lbm.h main.c main.h)
