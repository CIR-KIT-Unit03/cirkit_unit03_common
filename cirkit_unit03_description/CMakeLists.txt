cmake_minimum_required(VERSION 2.8.3)
project(cirkit_unit03_description)
find_package(catkin REQUIRED)

# Testing
find_package(roslaunch)
roslaunch_add_file_check(test/cirkit_unit03_description_demo.test.xml)
roslaunch_add_file_check(test/cirkit_unit03_description_demo2.test.xml)
roslaunch_add_file_check(test/cirkit_unit03.test.xml)
roslaunch_add_file_check(test/description.test.xml)
