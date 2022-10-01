cmake_minimum_required(VERSION 3.23.2)

# SET PROJECT
project(Obf C)
set(CMAKE_CXX_STANDARD 14)
# Source Files
set(SOURCE_FILES main.c)
# executable main.c to Obf
add_executable(Obf ${SOURCE_FILES})
