
cmake_minimum_required(VERSION 3.10)

project(glfw_project LANGUAGES C)

find_package(OpenGL REQUIRED)
find_package(glfw3 REQUIRED)

add_subdirectory(src)
