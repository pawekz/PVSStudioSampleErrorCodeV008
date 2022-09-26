cmake_minimum_required(VERSION 3.23)
project(MultiDimensionalArray3 C)

set(CMAKE_C_STANDARD 11)

add_executable(MultiDimensionalArray3 main.c
                                      multiArray.c
                                      multiArray.h)
