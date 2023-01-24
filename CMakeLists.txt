cmake_minimum_required(VERSION 3.24)
project(helloSFML)

set(CMAKE_CXX_STANDARD 17)

add_executable(helloSFML main.cpp)

set(SFML_STATIC_LIBRARIES TRUE)
set(SFML_DIR C:/SFML/bin)
find_package(SFML COMPONENTS)

include_directories(c:/SFML/include)