cmake_minimum_required(VERSION 3.10.2)
project(lab08_report05 LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 14)
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS}")

add_executable(${PROJECT_NAME}
        ./banker.cpp
        )
