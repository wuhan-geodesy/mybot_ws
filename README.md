# mybot_ws
URDF model for Gazebo integrated with ROS

This repository has several branches. Please checkout the appropriate branch for your needs. <br>
1) <strong>base</strong> - create simple URDF model <br>
2) <strong>base_sensors</strong> - add sensors to robot <br>
3) <strong>navigation</strong> - enable autonomous navigation (now updated for [ROS Melodic Morenia](http://wiki.ros.org/melodic))

For more information on running the code:  <br>
http://moorerobots.com/blog/post/6

# Install dependencies
```
sudo apt-get install ros-melodic-hector-gazebo-plugins
```

# Build
```
catkin build
```

# Test

tested on Ubuntu 18.04 ROS Melodic Gazebo 9.0
One terminal,
```
./run_gazebo.sh
```
Another terminal,
```
./run_cmd.sh
```
Third terminal,
```
./run_rviz.sh
```
