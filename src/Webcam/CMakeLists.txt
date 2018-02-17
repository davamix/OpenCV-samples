#cmake_minimun_required(VERSION 3.5)

find_package(OpenCV REQUIRED)

project("Webcam capture")

set(CMAKE_CXX_STANDARD 11)

add_executable(Webcam Webcam.cpp)

target_link_libraries(Webcam ${OpenCV_LIBS})

