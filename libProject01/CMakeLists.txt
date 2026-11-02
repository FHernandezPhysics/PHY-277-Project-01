message(STATUS "Build libProject01")

add_library(Project01 helloWorld.cpp)

target_include_directories(Project01
    PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})