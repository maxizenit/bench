cmake_minimum_required(VERSION 3.10)
project(pgdlo)

set(CMAKE_C_COMPILER gcc)
set(CMAKE_VERBOSE_MAKEFILE ON)
set(CMAKE_C_FLAGS "-g")

add_executable(${Bench}.bc defines.h implicit.c implicit.h mcf.c
               mcf.h mcflimit.h mcfutil.c mcfutil.h
               output.c output.h pbeampp.c pbeampp.h
               pbla.c pbla.h pflowup.c pflowup.h
               prototyp.h psimplex.c psimplex.h pstart.c
               pstart.h readmin.c readmin.h treeup.c treeup.h)
