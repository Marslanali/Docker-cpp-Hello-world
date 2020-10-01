cmake_minimum_required(VERSION 3.5.1)
project(Docker-cpp-Hello-world)

set(CMAKE_CXX_STANDARD 11)

add_executable(Docker-cpp-hello-world ${PROJECT_SOURCE_DIR}/src/fibonacci.cpp)
