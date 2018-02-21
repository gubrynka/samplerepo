cmake_minimum_required(VERSION 2.8.12)

project(2_1)

set(CMAKE_CXX_COMPILER g++)
add_compile_options(-std=c++14)
add_compile_options(-Wall)
add_compile_options(-Werror)

add_executable(1_1.out main.cpp)
