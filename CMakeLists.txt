cmake_minimum_required(VERSION 3.8)
project(Emoh_Libraries)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES Device.cpp Device.h MQTTConnection.cpp MQTTConnection.h MQTTException.cpp MQTTException.h)
add_library(Emoh_Libraries SHARED ${SOURCE_FILES})