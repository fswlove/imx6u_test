#cmake_minimum_required(VERSION 3.0.0)

#include_directories(../../inc/bsp)
project(demo)

include_directories(./led)
aux_source_directory(. ./led demos)

#add_library(${PROJECT_NAME} ${bsps})

#add_library(bsp ALIAS ${PROJECT_NAME})