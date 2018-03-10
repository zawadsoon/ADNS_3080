cmake_minimum_required(VERSION 2.8)
project(ADNS_5050)
cmake_policy(SET CMP0015 NEW)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_BINARY_DIR}/bin)

add_executable(main main.cpp ${ADNS_5050})