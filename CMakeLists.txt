cmake_minimum_required(VERSION 3.28.0)

project(OLAS)

add_executable(${PROJECT_NAME} main.cpp)

install(TARGETS ${PROJECT_NAME} DESTINATION bin)