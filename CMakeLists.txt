cmake_minimum_required(VERSION 2.8)

project (test)
file(GLOB test_SRC
    "*.h"
    "*.cpp"
)

add_executable(test ${test_SRC})
