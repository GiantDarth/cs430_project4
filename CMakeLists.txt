cmake_minimum_required(VERSION 3.6)
project(project4)

set(CMAKE_CXX_FLAGS "${CMAKE_C_FLAGS} -std=c11")

set(SOURCE_FILES src/main.c src/json.c src/json.h src/raycast.c src/raycast.h src/vector3d.h src/write.c src/write.h)
add_executable(project4 ${SOURCE_FILES})