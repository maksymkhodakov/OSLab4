cmake_minimum_required(VERSION 3.22)
project(OSLab4)

set(CMAKE_CXX_STANDARD 17)

add_executable(pid_teller.cpp)
add_executable(process_reader.cpp)
add_executable(keyboard_hooker keyboard_hooker.c)