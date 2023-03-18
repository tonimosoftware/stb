cmake_minimum_required(VERSION 3.23)

project(stb)

add_library(${PROJECT_NAME} STATIC
    stb_vorbis.c
)

target_include_directories(${PROJECT_NAME} PUBLIC ../stb)