cmake_minimum_required(VERSION 2.8.11)
project(cmake_wrapper)

ADD_DEFINITIONS( "-std=c++11" )

include(conanbuildinfo.cmake)
conan_basic_setup()

add_subdirectory("source_subfolder")
