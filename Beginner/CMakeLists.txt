cmake_minimum_required(VERSION 2.8)
project( Beginner )
find_package( OpenCV REQUIRED )

set (CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_CURRENT_SOURCE_DIR}/dist)

#C++11
set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_subdirectory(image image/obj)
add_subdirectory(UnitTest UnitTest/obj)


