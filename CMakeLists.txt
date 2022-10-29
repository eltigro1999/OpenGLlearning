cmake_minimum_required(VERSION 3.06)

project(OpenGLLearning)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_subdirectory(external_libs/glfw)
add_subdirectory(external_libs/glad)
add_subdirectory(exe_code)
