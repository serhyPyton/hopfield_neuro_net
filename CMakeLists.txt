cmake_minimum_required (VERSION 3.0)

project( hopfield_neuro_net )

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable( hopfield src/hopfield_net.cpp )
