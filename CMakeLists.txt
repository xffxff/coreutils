cmake_minimum_required(VERSION 3.16)
project(coreutils C)

set(CMAKE_C_STANDARD 11)

add_executable(cat
        src/cat.c)
