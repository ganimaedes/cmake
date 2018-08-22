cmake_minimum_required(VERSION 3.04)

project (sample)
file(GLOB SOURCE
    "*.h"
    "*.cpp"
)
set(CMAKE_CXX_STANDARD 14)
add_executable(sample ${SOURCE})
