cmake_minimum_required(VERSION 3.15)
project(core_calculator)

set(CMAKE_CXX_STANDARD 17)

include_directories(include)

file(GLOB SOURCES "*.cpp")

add_library(
core_calculator
SHARED
${SOURCES}
)
