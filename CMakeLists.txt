﻿
cmake_minimum_required (VERSION 3.8)

SET(CMAKE_INSTALL_RPATH_USE_LINK_PATH TRUE)

project ("HPX-Scaling-Benchmarks")

find_package(HPX REQUIRED)
add_subdirectory("src")