cmake_minimum_required(VERSION 2.8.3)
project(adaptive_clustering_gpu)

find_package(catkin REQUIRED COMPONENTS roscpp std_msgs sensor_msgs visualization_msgs geometry_msgs pcl_conversions pcl_ros)

find_package(PCL 1.12 REQUIRED)

include_directories(include /opt/ros/melodic/include /usr/local/include/eigen3 /usr/local/include/pcl-1.12)

add_message_files(FILES ClusterArray.msg)

generate_messages(DEPENDENCIES std_msgs sensor_msgs)

catkin_package()

add_executable(adaptive_clustering_gpu src/adaptive_clustering_gpu.cpp)
target_link_libraries(adaptive_clustering_gpu ${catkin_LIBRARIES} ${PCL_LIBRARIES})
if(catkin_EXPORTED_TARGETS)
  add_dependencies(adaptive_clustering_gpu ${catkin_EXPORTED_TARGETS})
endif()
