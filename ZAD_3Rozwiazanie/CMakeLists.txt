cmake_minimum_required(VERSION 3.8)
project(PS4_ZAD_3)

set(CMAKE_C_STANDARD 11)

set(SOURCE_FILES main.c AVLtree.c AVLtree.h script.c script.h)
add_executable(PS4_ZAD_3 ${SOURCE_FILES})