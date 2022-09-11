# LIO-FUSION

**A reinforced LiDAR inertial odometry system that optimally fuses GPS/relocalization and wheel odometry to provide accurate and robust 6-DoF movement estimation under challenging perceptual conditions. A video of the demonstration of the method can be found on [YouTube](https://youtu.be/1I6E1_3VOVo).(RAL2023)**

**Authors:** Wenhong Wu, Xunyu Zhong*, Dongjie Wu, Bushi Chen, Xungao Zhong and Qiang Liu

## Menu

  - [**System architecture**](#system-architecture)

  - [**Package dependency**](#dependency)

  - [**Package install**](#install)
  
  - [**Gazebo simulation**](#Gazebo_simulation)

  - [**Sample datasets**](#sample-daasets)

  - [**Run the package**](#run-the-package)

## System architecture

## Dependency

## Install

Use the following commands to download and compile the package.

```
cd ~/catkin_ws/src
git clone wwenhong/LIO-FUSION.git
cd ..
catkin_make
```

## Gazebo_simulation

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

