cmake_minimum_required(VERSION 3.14)
project(PathTracer)
SET(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall -Wextra")

add_executable( pathtracer pathtracer.cpp bvh.h util.h)
target_compile_features(pathtracer PUBLIC cxx_lambdas)

