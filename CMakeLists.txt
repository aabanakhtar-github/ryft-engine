cmake_minimum_required(VERSION 3.26)

project(RYFT_ENGINE)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED True)

set(RYFT_SRCS
        src/ryft.h
        src/ryft.cpp
)

add_library(RYFT_LIBRARY ${RYFT_SRCS})