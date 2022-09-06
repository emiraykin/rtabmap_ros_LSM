# rtabmap_ros_faster
RTAB-Map's ROS package.

Please make sure you have all the dependencies before you start. The dependencies above are for noetic-devel. 
!! For the fastest solution, You definetly need to use pointcloud_to_laserscan package in this project. Please do not try to get it externally.

## Principle of Work

The package use 2D lidar odometry to localize, so if you are only using an RGBD Camera as sensor, you first need to obtain a laser message and then obtain an odometry with this laser message.

Here is the diagram of packages.

![diagram](images/diagram.jpeg)
