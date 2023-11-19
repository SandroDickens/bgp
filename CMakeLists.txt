cmake_minimum_required(VERSION 3.0)
project(bgp)

set(CMAKE_CXX_STANDARD 20)

add_subdirectory(controller)
add_subdirectory(model)
add_subdirectory(transaction)
add_subdirectory(view)
