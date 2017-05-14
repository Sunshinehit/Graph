cmake_minimum_required(VERSION 3.7)
project(Graph)

set(CMAKE_C_STANDARD 99)

set(SOURCE_FILES main.c Graph.c Graph.h WeightGraph.c WeightGraph.h Graph_tools.c Graph_tools.h Binaryheap.c Binaryheap.h)
add_executable(Graph ${SOURCE_FILES})