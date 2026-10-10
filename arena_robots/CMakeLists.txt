cmake_minimum_required(VERSION 3.5)
project(arena_robots)

find_package(ament_cmake REQUIRED)
find_package(ament_cmake_python REQUIRED)

install(
  DIRECTORY robots/
  DESTINATION share/${PROJECT_NAME}/robots
)

ament_python_install_package(${PROJECT_NAME})

ament_package()
