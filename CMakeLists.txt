cmake_minimum_required(VERSION 3.31)
project(PHY277project01)
enable_testing()
add_subdirectory(libProject01)

add_test(NAME mainXor COMMAND mainXor)
add_executable(mainXor mainXor.cpp)