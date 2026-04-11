cmake_minimum_required(VERSION 3.8)
project(justina_hardware)

# Paquete base de CMake para ROS 2
find_package(ament_cmake REQUIRED)

install(
  DIRECTORY launch
  DESTINATION share/${PROJECT_NAME}
)

install(
  FILES package.xml
  DESTINATION share/${PROJECT_NAME}
)

ament_package()

