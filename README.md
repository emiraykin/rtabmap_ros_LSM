# rtabmap_ros_faster
RTAB-Map's ROS package.

Please make sure you have all the dependencies before you start. The dependencies above are for noetic-devel. 

## Principle of Work

The package use 2D lidar odometry to localize, so if you use only RGBD Camera sensor you first need to obtain a laser message and obtain an odometry with this laser message.
Here is the diagram of packages:

![diagram](images/diagram.jpeg)
