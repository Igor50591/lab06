cmake_minimum_required(VERSION 3.22)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

project(formatter)

add_library(formatter STATIC ${CMAKE_CURRENT_SOURCE_DIR}/formatter.cpp)

