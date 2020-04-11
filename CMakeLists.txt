cmake_minimum_required (VERSION 3.0)

project ("vscode-cmake-tools587" LANGUAGES CXX)

add_subdirectory(base)
add_subdirectory(project_1) # fails in combination with base
add_subdirectory(project_2)
add_subdirectory(project_3)
add_subdirectory(project_4)
