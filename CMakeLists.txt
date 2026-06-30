cmake_minimum_required(VERSION 3.15...4.0)
project(vergesort VERSION 1.0 LANGUAGES CXX)

add_library(vergesort INTERFACE vergesort.h)
target_compile_features(vergesort INTERFACE cxx_std_11)
target_include_directories(vergesort INTERFACE include)
