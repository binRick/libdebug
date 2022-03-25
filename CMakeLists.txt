cmake_minimum_required(VERSION 3.2)

project(test1)

set(CMAKE_C_STANDARD 99)

add_compile_options(-Wall -Wextra -g -DDEBUG -O0)

add_executable(
        ${PROJECT_NAME}
        libdebug.h
        test-libdebug1.c
)
