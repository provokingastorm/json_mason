cmake_minimum_required(VERSION 3.8...4.4)
project(json_mason)

set(JSON_MASON_SRC
	json.hpp
	json_mason.cpp
)

include_directories(../imgui)

link_libraries(imgui)

add_executable(json_mason ${JSON_MASON_SRC})

target_link_libraries(json_mason PRIVATE d3d12 dxgi)