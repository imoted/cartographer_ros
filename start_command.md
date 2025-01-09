#! /bin/bash

# 2D
roslaunch cartographer_ros demo_backpack_2d.launch bag_filename:=/home/ros/bag/3DSLAM_bag/cartographer_paper_deutsches_museum.bag
# 3D
roslaunch cartographer_ros demo_backpack_3d.launch bag_filename:=/home/ros/bag/3DSLAM_bag/b3-2016-04-05-14-14-00.bag

# 自分の家3D
roslaunch cartographer_ros mid360_demo.launch bag_filename:=/home/ros/bag/3DSLAM_bag/_2023-01-16-12-59-04.bag
