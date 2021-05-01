cmake_minimum_required(VERSION 3.12.4)
project(ripassone VERSION 0.0.1 LANGUAGES CXX)

add_executable(TripleX)
target_sources(TripleX PRIVATE src/TripleX.cpp)
target_compile_features(TripleX PUBLIC cxx_std_17)