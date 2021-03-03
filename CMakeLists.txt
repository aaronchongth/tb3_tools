cmake_minimum_required(VERSION 3.5.0)

project(tb3_tools)

find_package(catkin)

catkin_package()

install(
  DIRECTORY rviz
  DESTINATION share/${PROJECT_NAME}
)

install(
  DIRECTORY launch
  DESTINATION share/${PROJECT_NAME}
)

install(
  DIRECTORY maps
  DESTINATION share/${PROJECT_NAME}
)
