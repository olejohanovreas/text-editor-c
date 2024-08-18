cmake_minimum_required(VERSION 3.29)
project(text_editor_c C)

set(CMAKE_C_STANDARD 11)

include_directories(.)

add_executable(text_editor_c
        kilo.c)
