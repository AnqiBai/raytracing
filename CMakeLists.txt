cmake_minimum_required(VERSION 3.17)
project(raytracing)

set(CMAKE_CXX_STANDARD 14)

file(GLOB raytracing_SRC
        "*.h"
        "*.cpp"
        )
add_executable(raytracing ${raytracing_SRC})