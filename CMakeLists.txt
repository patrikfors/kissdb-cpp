cmake_minimum_required(VERSION 3.15)

project(kissdb-cpp)

add_executable(kissdb-test kissdb.cpp)
target_compile_definitions(kissdb-test PRIVATE KISSDB_TEST)
