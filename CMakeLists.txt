cmake_minimum_required(VERSION 3.0.0)

project(LEGO_ADDRESS_DUMPER LANGUAGES CXX C)

add_subdirectory("${CMAKE_CURRENT_SOURCE_DIR}/deps/zydis")
add_subdirectory("${CMAKE_CURRENT_SOURCE_DIR}/src")
