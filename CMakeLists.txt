cmake_minimum_required(VERSION 3.13)
project(farms2)

set(CMAKE_CXX_STANDARD 11)

add_executable(farms2 library2.cpp DataCenterManager.h library2.h AVLtree.h UpTree.h DataCenterManager.cpp HashTable.h main.cpp)