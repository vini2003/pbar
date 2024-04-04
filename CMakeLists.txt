cmake_minimum_required(VERSION 3.10)

project(pbar)

option(PBAR_INCLUDE_EXAMPLES "Include pbar examples" ON)

if(PBAR_INCLUDE_EXAMPLES)
    add_subdirectory(examples)
endif()