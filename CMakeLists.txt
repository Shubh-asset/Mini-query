cmake_minimum_required(VERSION 4.2.8)
PROJECT(MiniQuery)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(MiniQuery 
    src/main.cpp
    src/lib_header.cpp)

target_include_directories(MiniQuery 
    PRIVATE 
        ${CMAKE_CURRENT_SOURCE_DIR}/include
    )

#--------this below syntax is from above version 3.20 (much efficient though)---------
# target_sources(MiniQuery
#     PRIVATE 
#         src/main.cpp
#         src/lib_header.cpp
#     PUBLIC
#         FILE_SET HEADER_SET
#         BASE_DIRS
#             include
#         FILES
#             include/lib_header.h
#     )


