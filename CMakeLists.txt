cmake_minimum_required(VERSION 3.5)

project(Task2 LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
enable_testing()

add_executable(Task2 main.cpp Array.h)
add_subdirectory(Tests)