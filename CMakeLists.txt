cmake_minimum_required(VERSION 3.5)

project(rmf_pinklab_assets)

find_package(ament_cmake REQUIRED)

install(
  DIRECTORY models urdf meshes config
  DESTINATION share/${PROJECT_NAME}
)

ament_package()
