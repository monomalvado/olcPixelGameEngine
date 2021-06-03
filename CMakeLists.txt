cmake_minimum_required(VERSION 3.19)
project(olcPixelGameEngine)

set(CMAKE_CXX_STANDARD 17)

include_directories(. Extensions)
include_directories(C:/Developer/C_CPP/asio-1.18.2/include)

add_library(${PROJECT_NAME} olcPixelGameEngine.cpp)