set(CMAKE_SYSTEM_NAME Linux)

cmake_minimum_required(VERSION 3.10)

project(hellocpp-linux)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_SYSTEM_PROCESSOR aarch64)

add_executable(hellocpp-linux main.cpp)