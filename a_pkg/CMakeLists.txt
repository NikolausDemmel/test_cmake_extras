cmake_minimum_required(VERSION 2.8.3)
project(a_pkg)
message("CMakeLists A before find_package")
find_package(catkin REQUIRED)
message("CMakeLists A after find_package")
catkin_package(
    CFG_EXTRAS a_pkg-extras.cmake
)
