cmake_minimum_required(VERSION 3.21)
project(AzureBuildStage LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENSIONS OFF)

add_subdirectory(src/my_lib)
add_subdirectory(src/my_program)


