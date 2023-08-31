#cmake_minimum_required(VERSION 3.0.0)
project(imx6u_test)

#include_directories(${PROJECT_SOURCE_DIR}/inc ${PROJECT_SOURCE_DIR}/inc/bsp)

#add_subdirectory(bsp)

aux_source_directory(. srcs)
aux_source_directory(../demo demos)

add_executable(${PROJECT_NAME} ${srcs} ${demos})

#target_link_libraries(${PROJECT_NAME} bsp)