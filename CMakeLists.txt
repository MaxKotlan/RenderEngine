#cmake information
cmake_minimum_required(VERSION 3.0)
project(RenderEngine)

#build external libraries
add_subdirectory(extern)

#build main render engine source code
add_subdirectory(src)
