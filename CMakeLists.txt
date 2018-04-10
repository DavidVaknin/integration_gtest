cmake_minimum_required(VERSION 2.8)

project(myProject)
include(cppcheck.cmake)
enable_testing()

add_subdirectory(main)
add_subdirectory(test)
add_subdirectory(libfoo)
add_subdirectory(libbar)
