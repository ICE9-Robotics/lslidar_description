cmake_minimum_required(VERSION 3.5)
project(lslidar_description)

find_package(ament_cmake REQUIRED)

# Install files
install(DIRECTORY
        meshes
        urdf
        DESTINATION share/${PROJECT_NAME})

ament_package()