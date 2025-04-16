#[[
CMakeLists.txt

Build tool so I can manage external libraries

CHANGELOG
Date        User            Change Descritiption
4/15/23     Logan Lach      Initial Creation


]]

cmake_minimum_required(VERSION 4.0.1)
project(LoadBalancer)

set(MAIN_PATH "../src/main.cpp")
set(CMAKE_CXX_STANDARD 23)
set(CMAKE_CXX_STANDARD_REQUIRED TRUE)

include_directories("include")
add_executable(${PROJECT_NAME} ${MAIN_PATH})