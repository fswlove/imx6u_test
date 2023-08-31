#cmake_minimum_required(VERSION 3.0.0)

#include_directories(../../inc/bsp)
project(led)

include_directories(.)

aux_source_directory(. leds)

#add_library(${PROJECT_NAME} ${bsps})

#add_library(bsp ALIAS ${PROJECT_NAME})