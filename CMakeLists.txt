cmake_minimum_required(VERSION 3.10)
project(PRT7 CXX)
set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
add_executable(prt7
    src/main.cpp
    src/TramaBase.h
    src/TramaLoad.h
    src/TramaMap.h
    src/RotorDeMapeo.h
    src/ListaDeCarga.h
)
