cmake_minimum_required(VERSION 3.17)
project(start_scene)

set(CMAKE_CXX_STANDARD 17)

add_executable(start_scene src/scene-start.cpp src/gnatidread.h src/gnatidread2.h)

target_include_directories(start_scene PRIVATE lib/angel)