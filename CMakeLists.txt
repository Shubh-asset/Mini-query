cmake_minimum_required(VERSION 3.20)
PROJECT(MiniQuery)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(MiniQuery src/main.cpp)

target_include_directories(MiniQuery PRIVATE include)
