cmake_minimum_required(VERSION 3.23)
project(project4_main_2)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(project4_main_2
        Test-Cases/auto_test1.cpp
        auto_test1.cpp
        autocomplete.cpp
        autocomplete.h
        bst_depth.cpp
        bst_lca.cpp
        bst_validator.cpp
        tree_node.h)
