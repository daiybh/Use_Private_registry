cmake_minimum_required (VERSION 3.8)
list(APPEND CMAKE_MODULE_PATH ${CMAKE_CURRENT_SOURCE_DIR}/cmake)


project("DNxGPU"  CXX)




add_executable(DNxGPU t.cpp)