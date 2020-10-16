cmake_minimum_required(VERSION 3.1)

project(CRUD)

set(SOURCE_LIB create.c)

add_library(foo STATIC ${SOURCE_LIB})