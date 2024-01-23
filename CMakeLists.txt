cmake_minimum_required(VERSION 3.0.2)
project(graspnet_ros)

find_package(catkin REQUIRED COMPONENTS
  roscpp
  rospy
)

catkin_package(
 INCLUDE_DIRS include
 LIBRARIES graspnet_ros
 CATKIN_DEPENDS
 roscpp
 rospy
)

include_directories(
include
  ${catkin_INCLUDE_DIRS}
)
