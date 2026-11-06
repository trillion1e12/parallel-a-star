cmake_minimum_required(VERSION 3.10.0)
project(parallel-a-star VERSION 0.1.0 LANGUAGES C CXX)

set(CMAKE_CXX_CLANG_TIDY "clang-tidy;-checks=-*,clang-analyzer-*;-warnings-as-errors=*")

add_executable(parallel-a-star
    src/main.cpp
)

