cmake_minimum_required(VERSION 3.06)

project(OpenGLLearning)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

set(path_to_glfw external_libs/glfw/)
set(path_to_glad external_libs/glad/)
set(path_to_exe_code exe_code)
set(path_to_image external_libs/image)

add_subdirectory(${path_to_glfw})
add_subdirectory(${path_to_glad})
add_subdirectory(${path_to_exe_code})
add_subdirectory(${path_to_image})
#set_property(DIRECTORY ${CMAKE_CURRENT_SOURCE_DIR} PROPERTY VS_STARTUP_PROJECT OpenGLLearning)
