#
# THIS FILE CAN BE CONSIDERED PUBLIC DOMAIN.
# This does not extend to lodepng.h/cpp files.
#
# Created by Bartłomiej Janowski, 2022
#

cmake_minimum_required(VERSION 3.1)

project(
  lodepng
  LANGUAGES CXX)

set(PROJECT_SOURCES lodepng.cpp)

add_library(${PROJECT_NAME} ${PROJECT_SOURCES})

target_include_directories(${PROJECT_NAME} PUBLIC include/)
