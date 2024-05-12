cmake_minimum_required(VERSION 3.25)
project(MemberVariableOfSelfType)

set(CMAKE_CXX_STANDARD 20)

set(SOURCES
    main.cpp
    point.cpp
    point.h
)

add_executable(cmake_rooster ${SOURCES})