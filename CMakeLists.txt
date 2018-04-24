cmake_minimum_required(VERSION 3.5.0 FATAL_ERROR)

project(lp_libs VERSION 0.1.0 LANGUAGES CXX)

set(BUILD_TESTING "YES")

add_subdirectory(lp_cc_lib)
add_subdirectory(lp_hal)
