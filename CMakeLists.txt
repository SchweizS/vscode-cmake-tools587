cmake_minimum_required (VERSION 3.0)

project ("vscode-cmake-tools587" LANGUAGES CXX)

add_subdirectory(base)
add_subdirectory(subdir) # fails in combination with base
add_subdirectory(duplicate_project)  # fails in combination with base
