cmake_minimum_required(VERSION 3.15)
project(xd_engine CXX)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

set(EXE_NAME "Inchoatus")

add_executable(${EXE_NAME})

add_subdirectory(src)