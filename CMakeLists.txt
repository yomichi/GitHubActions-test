cmake_minimum_required(VERSION 3.6)
message(STATUS "CMake version: " ${CMAKE_VERSION})
project(GHAtest C)

enable_testing()

add_subdirectory(src)
add_subdirectory(test)
