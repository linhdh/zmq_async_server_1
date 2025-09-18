cmake_minimum_required(VERSION 4.0)
project(zmq_async_server_1)

set(CMAKE_CXX_STANDARD 17)

add_executable(zmq_async_server_1 main.cpp)

target_link_libraries(zmq_async_server_1 zmq)

