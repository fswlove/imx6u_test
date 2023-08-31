cmake_minimum_required(VERSION 3.0.0)
project(topdir)

include_directories(inc demo/led)

add_subdirectory(src demo)

#aux_source_directory(src srcs)

#add_executable(vsmake ${srcs})

#target_link_libraries(vsmake ${bspLib})