cmake_minimum_required(VERSION 2.6)

set(CMAKE_CXX_FLAGS_RELEASE "-Wall -O2")

set(CMAKE_CXX_FLAGS_DEBUG "-g -O0")

set(CMAKE_BUILD_TYPE Release)

set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ..)


project(heap)

add_executable(main main.cpp)

target_link_libraries(main m)
