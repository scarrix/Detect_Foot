cmake_minimum_required(VERSION 2.8.12 FATAL_ERROR)
project(detectfoot_bothCamera)
find_package(OpenCV REQUIRED)
include_directories(${PROJECT_BINARY_DIR})
add_executable (${PROJECT_NAME} detectfoot_bothCamera.cpp)
target_link_libraries (${PROJECT_NAME} ${OpenCV_LIBS})


