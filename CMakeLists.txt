# CMakeLists.txt
cmake_minimum_required(VERSION 3.6)   # CMake version check
project(FinalProject)

set(CMAKE_CXX_STANDARD 11)            # Enable c++11 standard

set(SOURCE_FILES main.c level.c room.c player.c pathfinding.c queue.h utils.h wretch.h )
add_executable(FinalProject ${SOURCE_FILES})
