cmake_minimum_required(VERSION 3.10 FATAL_ERROR)

project(leet VERSION 0.1 LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_subdirectory(playground)
add_subdirectory(third_party)
add_subdirectory(problems)

