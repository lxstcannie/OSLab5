# CMakeList.txt: проект CMake для OSLab5; включите исходный код и определения,
# укажите здесь логику для конкретного проекта.
#
cmake_minimum_required (VERSION 3.8)
project(Server)

set(CMAKE_CXX_STANDARD 98)
add_executable (OSLab5 "Client.cpp" "OSLab5.h")

# TODO: Добавьте тесты и целевые объекты, если это необходимо.
