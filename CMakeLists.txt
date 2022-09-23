cmake_minimum_required(VERSION 3.22)

project(fastmod C CXX)

add_library(fastmod INTERFACE)
target_include_directories(fastmod INTERFACE include)
