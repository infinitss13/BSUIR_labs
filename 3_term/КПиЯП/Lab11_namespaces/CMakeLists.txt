cmake_minimum_required(VERSION 3.20)
project(Lab11_namespaces)

set(CMAKE_CXX_STANDARD 14)

add_executable(Lab11_namespaces main.cpp src/Transport.cpp src/Transport.h src/Engine.cpp src/Engine.h src/Engine_oil.cpp src/Engine_oil.h src/Wheel.cpp src/Wheel.h src/Headlight.cpp src/Headlight.h src/Lamp.cpp src/Lamp.h src/Car.cpp src/Car.h "Menu functions/Menu_functions.cpp" "Menu functions/Menu_functions.h")
