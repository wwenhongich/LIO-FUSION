# LIO-FUSION

**A reinforced LiDAR inertial odometry system that optimally fuses GPS/relocalization and wheel odometry to provide accurate and robust 6-DoF movement estimation under challenging perceptual conditions. A video of the demonstration of the method can be found on [YouTube](https://youtu.be/xn7mffXxrPo).**


## Menu

  - [**System architecture**](#system-architecture)

  - [**Package dependency**](#dependency)

  - [**Package install**](#install)
  
  - [**Gazebo simulation**](#install)

  - [**Sample datasets**](#sample-daasets)

  - [**Run the package**](#run-the-package)

## System architecture

We design a system that maintains main factor graph and sub factor graph. 

## Dependency

This is the original ROS1 implementation of LIO-Fusion. 

## Install

Use the following commands to download and compile the package.

```
cd ~/catkin_ws/src
git clone wwenhong/LIO-FUSION.git
cd ..
catkin_make
```

## Sample datasets


## Run the package

1. Run the launch file:
```
roslaunch lio_fusion fusion.launch
```

2. Play existing bag files:
```
rosbag play your-bag.bag 
```

