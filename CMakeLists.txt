cmake_minimum_required(VERSION 3.10)
project(Testing)
set(CMAKE_WINDOWS_EXPORT_ALL_SYMBOLS ON)
add_subdirectory(Catch2)
add_executable(Testing HomeworkPP_4.1.cpp)
target_link_libraries(Testing PRIVATE Catch2::Catch2)