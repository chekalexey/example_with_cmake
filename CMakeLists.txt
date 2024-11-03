cmake_minimum_required(VERSION 3.0)
project(Add)

add_library(add add.cpp)
add_executable(main main.cpp)
target_link_libraries(main add)