#cmake_minimun_required(VERSION 3.5)

find_package(OpenCV REQUIRED)

project("Display Image")

set(CMAKE_CXX_STANDARD 11)

add_executable(DisplayImage DisplayImage.cpp)

target_link_libraries(DisplayImage ${OpenCV_LIBS})

