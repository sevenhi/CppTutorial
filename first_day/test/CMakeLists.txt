cmake_minimum_required(VERSION 3.16.3)
project(CppFirstDayTest)

set(TEST_INC_DIR inc)
set(TEST_SRC_DIR src)

include_directories(${TEST_INC_DIR})

add_executable(cppFirstDayTest ${TEST_SRC_DIR}/main.cpp)