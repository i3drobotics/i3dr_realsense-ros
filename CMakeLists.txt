cmake_minimum_required(VERSION 2.8.3)
project(i3dr_realsense)

add_compile_options(-std=c++11)

find_package(catkin REQUIRED COMPONENTS
  roscpp
  rospy
  std_msgs
  realsense2_camera
)

catkin_package(
)

include_directories(
  ${catkin_INCLUDE_DIRS}
)