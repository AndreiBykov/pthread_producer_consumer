cmake_minimum_required(VERSION 3.6)
project(pthread_producer_consumer)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES main.cpp)
add_executable(pthread_producer_consumer ${SOURCE_FILES})
target_link_libraries(pthread_producer_consumer pthread)