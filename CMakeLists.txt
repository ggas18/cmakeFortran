cmake_minimum_required (VERSION 2.6)
project (hello)
enable_language (Fortran)

file(GLOB SOURCES "src/*.f95")

add_executable (hello ${SOURCES})
