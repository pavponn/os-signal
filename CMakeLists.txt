cmake_minimum_required(VERSION 3.0)
project(os_signal)

set(CMAKE_CXX_STANDARD 14)

add_executable(os_signal main.cpp Handler.cpp Handler.h)