cmake_minimum_required(VERSION 3.0)
project(MyLang)

# Устанавливаем стандарт C++11
set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

# Устанавливаем флаги компиляции
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall -O2")

# Добавляем исполняемый файл
file(GLOB_RECURSE SOURCES "src/*.cpp" "src/Actions/*.cpp" "src/utils/*.cpp")
add_executable(MyLang ${SOURCES})
