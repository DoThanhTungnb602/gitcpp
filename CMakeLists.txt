cmake_minimum_required(VERSION 3.20)

project(Git LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_EXPORT_COMPILE_COMMANDS ON)

add_subdirectory(third_party)
add_subdirectory(core)
add_subdirectory(porcelain)
add_subdirectory(cli)
