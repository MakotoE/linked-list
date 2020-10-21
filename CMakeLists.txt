cmake_minimum_required(VERSION 3.17)
project(linked-list)

set(CMAKE_CXX_STANDARD 17)

add_subdirectory(tests)

add_library(linked-list LinkedList.h)
set_target_properties(linked-list PROPERTIES LINKER_LANGUAGE CXX)
add_compile_options(-Wall -Wextra -pedantic)