cmake_minimum_required(VERSION 3.1)

project(hello_world)

set(SOURCE_EXE main.c )

include_directories(create.h)

add_executable(main ${SOURCE_EXE})

add_subdirectory(CRUD ConfigDB)

target_link_libraries(main create)