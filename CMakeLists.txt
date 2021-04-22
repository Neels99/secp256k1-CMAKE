project(te)
cmake_minimum_required(VERSION 3.16)

include_directories(${CMAKE_SOURCE_DIR})
set (CMAKE_MODULE_PATH "${CMAKE_MODULE_PATH};${CMAKE_CURRENT_SOURCE_DIR}/cmake")

include(ProjectSecp256k1)

add_subdirectory(libs)
add_subdirectory(src)
