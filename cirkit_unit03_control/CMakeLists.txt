cmake_minimum_required(VERSION 2.8.3)
project(cirkit_unit03_control)
find_package(catkin REQUIRED)

# Testing
find_package(roslaunch)
roslaunch_add_file_check(test/control.test.xml)
roslaunch_add_file_check(test/control_gazebo.test.xml)
roslaunch_add_file_check(test/laserscan_merger.test.xml)
roslaunch_add_file_check(test/lower_step_detector.test.xml)
roslaunch_add_file_check(test/urg_laser_filter.test.xml)
