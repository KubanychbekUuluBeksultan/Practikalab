﻿# CMakeList.txt: файл проекта CMake верхнего уровня; проведите глобальную конфигурацию
# и включите сюда подпроекты.
#
cmake_minimum_required (VERSION 3.8)
project("CMakeProject1")
# Включите подпроекты.

add_subdirectory ("Alllab/lab1/lab1")
add_subdirectory ("Alllab/lab2/lab2")
add_subdirectory ("Alllab/lab3/Sol1/do_while")
add_subdirectory ("Alllab/lab3/Sol1/if")
add_subdirectory ("Alllab/lab3/Sol1/while")
add_subdirectory ("Alllab/lab4/lab4")
add_subdirectory ("Alllab/lab5/lab5")
add_subdirectory ("Alllab/lab6/lab6")
add_subdirectory ("Alllab/lab7/lab7")
