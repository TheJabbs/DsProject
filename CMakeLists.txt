cmake_minimum_required(VERSION 3.26)
project(DsProject)

set(CMAKE_CXX_STANDARD 17)

add_executable(DsProject main.cpp
        Course.cpp
        Course.h
        Student.cpp
        Student.h
        DoublyLinkedList.h
        LListWithDummyNode.h
)
