cmake_minimum_required (VERSION 3.0)

project ("base" LANGUAGES CXX)

add_executable(${PROJECT_NAME}_exe2 main.cpp)
add_library(${PROJECT_NAME}_lib2 main.cpp)

target_link_libraries(${PROJECT_NAME}_exe2 PRIVATE base_lib)