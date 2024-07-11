CMAKE_MINIMUM_REQUIRED(VERSION 3.15)
PROJECT(xapian_wrapper)

SET(CMAKE_MODULE_PATH "${CMAKE_CURRENT_SOURCE_DIR}/cmake;${CMAKE_MODULE_PATH}")


add_subdirectory(core)
add_subdirectory(test)