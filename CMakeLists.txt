cmake_minimum_required(VERSION 3.0)

project(game)

add_executable(game main.cpp)

install(TARGETS game RUNTIME DESTINATION bin)
