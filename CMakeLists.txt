cmake_minimum_required(VERSION 3.27.0)
project(
    Cmake00
    VERSION 0.0.1
    LANGUAGE CXX
)
set(CMAKE_CXX_STANDARD 11)
set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_SOURCE_DIR}/bin)

##设置路径
set(Test01_Dir ${CMAKE_SOURCE_DIR}/src/test01)
set(Test02_Dir ${CMAKE_SOURCE_DIR}/src/test02)

##添加子目录
add_subdirectory(src)