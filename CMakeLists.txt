cmake_minimum_required(VERSION 3.9)
project(data_structure C)

set(CMAKE_C_STANDARD 11)

add_executable(data_structure main.c binarytree/binarytree.h binarytree/binarytree.c)
