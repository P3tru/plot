cmake_minimum_required(VERSION 3.11)
project(plot)

set(CMAKE_CXX_STANDARD 11)

include_directories(include)

# ROOT
find_package(ROOT 6.16 CONFIG REQUIRED)
message(STATUS "ROOT version: ${ROOT_VERSION}")
include_directories(${ROOT_INCLUDE_DIRS})
