cmake_minimum_required(VERSION 3.7.2)

project(vs_dbg)

set(CMAKE_CXX_STANDARD 17)

add_subdirectory(test_lib)
add_executable(test_dbg test_dbg.cc)
add_dependencies(test_dbg test_lib)
target_link_libraries(test_dbg test_lib)