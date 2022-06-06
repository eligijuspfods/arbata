cmake_minimum_required(VERSION 3.5)

project(arbata LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(arbata main.cpp)

install(TARGETS arbata DESTINATION bin)
