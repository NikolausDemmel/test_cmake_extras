cmake_minimum_required(VERSION 2.8.3)
project(b_pkg)
#message("CMakeLists B before find_package")
find_package(catkin REQUIRED)
#message("CMakeLists B after find_package")
catkin_package(
    CFG_EXTRAS b_pkg-extras.cmake
)
