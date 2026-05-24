cmake_minimum_required(VERSION 3.10)

project(LynxDB)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED True)

message("Hello from Lynx Database")

add_executable(${PROJECT_NAME} bin/main.cc)
