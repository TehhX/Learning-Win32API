cmake_minimum_required(VERSION 3.31)
project(SanityCheck)
set(CMAKE_CXX_STANDARD 17)

set(SRC_FILES
    src/main.cpp
)

add_executable(${PROJECT_NAME} ${SRC_FILES})