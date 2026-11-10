cmake_minimum_required(VERSION 3.15)

project(tetris LANGUAGES C)

add_executable(tetris src/main.c)
target_include_directories(tetris PRIVATE include)
