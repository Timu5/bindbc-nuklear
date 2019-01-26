cmake_minimum_required(VERSION 3.0)

project(nuklear VERSION 4.00.2 DESCRIPTION "Nuklear GUI library")

add_library(nuklear SHARED nuklear.c)

set_target_properties(nuklear PROPERTIES VERSION ${PROJECT_VERSION})

set_target_properties(nuklear PROPERTIES PUBLIC_HEADER nuklear.h)