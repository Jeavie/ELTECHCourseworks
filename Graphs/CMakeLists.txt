cmake_minimum_required(VERSION 3.8)
project(Graphs)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES main.cpp)
add_executable(Graphs ${SOURCE_FILES})
include_directories(GL)

target_link_libraries(Graphs OpenGL GL/Glaux.lib GL/GLU32.LIB GL/glui32.lib GL/glut32.lib GL/OPENGL32.LIB)