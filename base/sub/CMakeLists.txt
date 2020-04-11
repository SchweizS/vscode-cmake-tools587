# if this file starts with project declaration no bug appears
project(base2)
add_library(${PROJECT_NAME}_lib main.cpp inc/main.hpp)
target_include_directories(${PROJECT_NAME}_lib PUBLIC .)
