cmake_minimum_required(VERSION 3.0)
project(MyLang)

# ������������� �������� C++11
set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

# ������������� ����� ����������
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall -O2")

# ��������� ����������� ����
file(GLOB_RECURSE SOURCES "src/*.cpp" "src/Actions/*.cpp" "src/utils/*.cpp")
add_executable(MyLang ${SOURCES})
