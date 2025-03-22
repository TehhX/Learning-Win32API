cmake_minimum_required(VERSION 3.31)
project(EmptyWindow)
set(CXX_STANDARD 17)

set(CMAKE_CXX_FLAGS "-municode")

set(SRC_FILES
    src/main.cpp
)

add_executable(${PROJECT_NAME} ${SRC_FILES})