cmake_minimum_required(VERSION 3.26)
project(uebung3 C)

set(CMAKE_C_STANDARD 11)

add_executable(uebung3 main.c)
target_link_libraries(uebung3 m)
