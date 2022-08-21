# LIO-FUSION

** A reinforced LiDAR inertial odometry system that optimally fuses GPS/relocalization and wheel odometry to provide accurate and robust 6-DoF movement estimation under challenging perceptual conditions. A video of the demonstration of the method can be found on [YouTube](https://youtu.be/1I6E1_3VOVo).**


## Menu

  - [**System architecture**](#system-architecture)

  - [**Package dependency**](#dependency)

  - [**Package install**](#install)

  - [**Prepare lidar data**](#prepare-lidar-data) (must read)

  - [**Prepare IMU data**](#prepare-imu-data) (must read)

  - [**Sample datasets**](#sample-datasets)

  - [**Run the package**](#run-the-package)

  - [**Other notes**](#other-notes)

  - [**Issues**](#issues)

  - [**Paper**](#paper)

  - [**TODO**](#todo)

  - [**Related Package**](#related-package)

  - [**Acknowledgement**](#acknowledgement)

## System architecture


We design a system that maintains main factor graph and sub factor graph. 

## Dependency

This is the original ROS1 implementation of LIO-Fusion. 

- [ROS](http://wiki.ros.org/ROS/Installation) (tested with Kinetic and Melodic. Refer to [#206](https://github.com/TixiaoShan/LIO-SAM/issues/206) for Noetic)
  ```
  sudo apt-get install -y ros-kinetic-navigation
  sudo apt-get install -y ros-kinetic-robot-localization
  sudo apt-get install -y ros-kinetic-robot-state-publisher
  ```
- [gtsam](https://gtsam.org/get_started/) (Georgia Tech Smoothing and Mapping library)
  ```
  sudo add-apt-repository ppa:borglab/gtsam-release-4.0
  sudo apt update
  sudo apt install libgtsam-dev libgtsam-unstable-dev
  ```

## Install

Use the following commands to download and compile the package.

```
cd ~/catkin_ws/src
git clone 
cd ..
catkin_make
```

## Prepare lidar data


## Prepare IMU data


## Prepare Encoder data


## Sample datasets


## Run the package

1. Run the launch file:
```
roslaunch lio_fusion run.launch
```

2. Play existing bag files:
```
rosbag play your-bag.bag 
```

## Other notes

 

## Service


## Issues


## Paper 



## TODO


## Related Package



## Acknowledgement

  - LIO-Fusion is based on LIO-SAM (J. Zhang and S. Singh. LOAM: Lidar Odometry and Mapping in Real-time).
