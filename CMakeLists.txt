cmake_minimum_required (VERSION 3.8)

project(my_second_cmake_project)

add_executable(my_second_cmake_project.exe CMakeHierarchy.cpp Figure.h Figure.cpp Triangle.h Triangle.cpp Quadrangle.h Quadrangle.cpp Right_Triangle.h Right_Triangle.cpp Isosceles_Triangle.h Isosceles_Triangle.cpp Equilateral_Triangle.h Equilateral_Triangle.cpp Parallelogram.h Parallelogram.cpp Rectangle.h Rectangle.cpp Rhombus.h Rhombus.cpp Square.h Square.cpp)