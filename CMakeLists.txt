cmake_minimum_required(VERSION 4.3)
project(riscvemu C)

set(CMAKE_C_STANDARD 11)

add_library(riscvemu STATIC library.c
        src/registers.c
        include/registers.h)
