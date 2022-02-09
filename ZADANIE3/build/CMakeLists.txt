cmake_minimum_required(VERSION 3.16)
project(myProgram)
install(DESTINATION ../zadanie)
add_executable(zadanie
        address.cpp
        address.h
        employee.cpp
        employee.h
        main.cpp)
