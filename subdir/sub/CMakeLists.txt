add_executable(${PROJECT_NAME}_exe main.cpp)
add_library(${PROJECT_NAME}_lib main.cpp)

target_link_libraries(${PROJECT_NAME}_exe PUBLIC base_lib)