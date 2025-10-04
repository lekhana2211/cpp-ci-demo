cmake_minimum_required(VERSION 3.10)
project(HotelManagement)

set(CMAKE_CXX_STANDARD 17)

include_directories(include)

add_executable(hms src/main.cpp)
