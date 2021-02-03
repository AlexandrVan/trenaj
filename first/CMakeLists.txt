# CMakeList.txt: проект CMake для first; включите исходный код и определения,
# укажите здесь логику для конкретного проекта.
#
cmake_minimum_required (VERSION 3.8)

project ("first")

# Добавьте источник в исполняемый файл этого проекта.
add_executable (first "first.cpp" "first.h")

# TODO: Добавьте тесты и целевые объекты, если это необходимо.
