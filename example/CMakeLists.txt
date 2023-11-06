cmake_minimum_required(VERSION 3.0.0)
project(example VERSION 0.0.1)

set(CMAKE_EXPORT_COMPILE_COMMANDS ON)

add_executable(${PROJECT_NAME} ./main.cpp)