cmake_minimum_required(VERSION 3.0)
project(Add)

add_library(add test/add.cpp)
add_executable(main test/main.cpp)
target_link_libraries(main add)