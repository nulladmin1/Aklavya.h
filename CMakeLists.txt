cmake_minimum_required(VERSION 3.20)

project(aklavya)

set(CMAKE_CXX_STANDARD 23)

add_subdirectory(src)

target_link_libraries(aklavya_h PRIVATE aklavya_lib)

install(TARGETS aklavya_h DESTINATION bin)
