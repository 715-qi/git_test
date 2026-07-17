cmake_minimum_required(VERSION 4.0)
project(git_test)

set(CMAKE_CXX_STANDARD 20)

add_executable(git_test main.cpp
        cmake-build-debug/test.h
        test.cpp
        test.h)
