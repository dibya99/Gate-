cmake_minimum_required(VERSION 2.8)

project(AUV_TASKS)

find_package( OpenCV 3.2 REQUIRED )


add_executable(gd src/gatedetect.cpp)
target_link_libraries(gd ${OpenCV_LIBS})

