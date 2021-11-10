cmake_minimum_required(VERSION 3.20)
project(Mir2_V2_Networking)

set(CMAKE_CXX_STANDARD 14)

TARGET_INCLUDE_DIRECTORIES(
        asio PUBLIC "${CMAKE_SOURCE_DIR}/include/asio/include/asio"
)

#Packet is headers only path is: /Users/rob/CMake Libs/asio-1.20.0/include

            ####Contents####
#Makefile.am
#Makefile.in
#asio
#asio.hpp


add_executable(Mir2_V2_Networking main.cpp)