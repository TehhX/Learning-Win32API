cmake_minimum_required(VERSION 3.31)
project(EmptyWindow)
set(CXX_STANDARD 17)

set(SRC_FILES
    src/main.cpp
)

add_executable(${PROJECT_NAME} WIN32 ${SRC_FILES})