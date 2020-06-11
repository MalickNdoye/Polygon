cmake_minimum_required(VERSION 3.16)
project(Polygon C)

set(CMAKE_C_STANDARD 11)

add_executable(Polygon main.c Polygon.c Polygon.h window.c window.h)