cmake_minimum_required(VERSION 3.8...4.4)
project(json_mason)

set(CMAKE_CXX_STANDARD 23)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_SOURCE_DIR}/bin)

add_subdirectory(src/imgui)
add_subdirectory(src/json_mason)