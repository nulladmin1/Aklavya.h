cmake_minimum_required(VERSION 3.20)

project(aklavya)

set(CMAKE_CXX_STANDARD 23)

add_subdirectory(src)

install(TARGETS aklavya DESTINATION bin)
