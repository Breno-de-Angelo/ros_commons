# ros_commons

Common utilities shared among ROS packages.

This package is a fork from [ros2amr ros_commons](https://github.com/ros2amr/ros_commons).

The main modifications are:

- Refactor of camera_link macro to stop creating the camera_link link. Only the optical link is created now.
- Creation of skid_controller based on libgazebo_ros_diff_drive.so as suggested by the [ros docs](https://github.com/ros-simulation/gazebo_ros_pkgs/wiki/ROS-2-Migration:-Skid-Steer-drive).
