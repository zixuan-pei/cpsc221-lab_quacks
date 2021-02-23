cmake_minimum_required(VERSION 3.17)
project(lab_quacks)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(lab_quacks
        catch.hpp
        catch_config.h
        exercises.cpp
        exercises.h
        main.cpp
        quackfun.cpp
        quackfun.h)
