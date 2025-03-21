cmake_minimum_required(VERSION 3.30)
project(Teczak_Engine)

set(CMAKE_CXX_STANDARD 20)

add_executable(${PROJECT_NAME} main.cpp)

target_link_libraries(${PROJECT_NAME} mylib)

add_subdirectory(lib)
