project(HelloWorld)

cmake_minimum_required(VERSION 3.10)
add_executable(Test main.cpp)
set_target_properties(
  Test
  PROPERTIES CXX_STANDARD 17 CXX_STANDARD_REQUIRED ON)