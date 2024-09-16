cmake_minimum_required(VERSION 3.0.2)
project(ewellix_description)

find_package(catkin REQUIRED)

catkin_package()

install(DIRECTORY launch meshes robot rviz urdf
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
)
