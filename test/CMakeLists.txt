cmake_minimum_required(VERSION 3.17)
project(chromium_test)

set(CMAKE_CXX_STANDARD 14)

include_directories(/Users/aqinn/CLionProjects/chromium-base/src)

link_directories(/Users/aqinn/CLionProjects/chromium-base/bin/base/Release)

add_executable(chromium_test test.cpp)

target_link_libraries(chromium_test base)