cmake_minimum_required(VERSION 3.15)
project(link_core_calculator)

set(CMAKE_CXX_STANDARD 17)

include_directories(include)

set(PROJECT_LINK_LIB libcore_calculator.dll)
link_directories(core_lib)

add_executable(
cpp-electric-bill-calculator 
main.cpp 
)

target_link_libraries(
cpp-electric-bill-calculator 
${PROJECT_LINK_LIB}
)
