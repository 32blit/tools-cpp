cmake_minimum_required(VERSION 3.9)
project(32blit-cpp-tools)

if(CMAKE_C_COMPILER_ID MATCHES "MSVC")
    set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -wd4244")
endif()

add_subdirectory(tools/src)
