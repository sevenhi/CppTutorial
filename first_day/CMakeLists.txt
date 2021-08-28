cmake_minimum_required(VERSION 3.16.3)
project(CppFirstDay)

option(BUILD_TESTS "build tests for project" OFF)
if (BUILD_TESTS)
    add_subdirectory(test)
endif()

set(INC_DIR inc/)
set(SRC_DIR src)

include_directories(INC_DIR)

add_executable(cppFirstDay ${SRC_DIR}/main.cpp)