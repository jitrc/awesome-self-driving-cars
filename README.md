# Awesome Self Driving Cars: [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A curated list of awesome self driving cars resources, inspired by many including [awesome-autonomous-vehicles](https://github.com/takeitallsource/awesome-autonomous-vehicles/).

## Table of Contents
* [Basics](#bascis)
* [Basic Software Library](#basic-software-library)
* [Datasets](#datasets)
* [Open Source Software](#open-source-software)
* [Related Links](#related-links)

## Bascis
Developing self driving cars requires many skill which mostly revolves around mobile robotics (percption, localization, path planning, controls, simulations) but can be very different, like end-to-end Deep Learning. I also sometimes requires knowledge of vehicle design, safety ... 

## Basic Software Library
1. [ROS](http://www.ros.org/) - Platform for easy development, visulization, logging and lots of community code in this platform
2. [OpenCV](http://opencv.org/) - Computer Vision
3. [PCL](http://pointclouds.org) - 3D point cloud processing

## Datasets
* [KITTI Vision Benchmark Suite](http://www.cvlibs.net/datasets/kitti/raw_data.php) - 6 hours of traffic scenarios at 10-100 Hz using a variety of sensor modalities such as highresolution
* [Udacity](https://github.com/udacity/self-driving-car/tree/master/datasets) - Udacity driving datasets released for [Udacity Challenges](https://www.udacity.com/self-driving-car). Contains ROSBAG training data. .
* [Oxford's Robotic Car](http://robotcar-dataset.robots.ox.ac.uk/) - over 100 repetitions of a consistent route through Oxford, UK, captured over a period of over a year. The dataset captures many different combinations of weather, traffic and pedestrians, along with longer term changes such as construction and roadworks.
* [Caltech Pedestrians](http://www.vision.caltech.edu/Image_Datasets/CaltechPedestrians/) - approximately 10 hours of 640x480 30Hz video taken from a vehicle driving through regular traffic in an urban environmen

### Dataset Collection 
* [OpenCV list](http://docs.opencv.org/3.0-beta/modules/datasets/doc/datasets.html)

## Open Source Software

* [Autoware](https://github.com/CPFL/Autoware) - Integrated open-source software for urban autonomous driving.
* [Comma.ai Openpilot](https://github.com/commaai/openpilot) - an open source driving agent.
* [Stanford Driving Software](https://sourceforge.net/projects/stanforddriving/) - Software Infrastructure for Stanford's Autonomous Vehicles.
* [GTA Robotics SDC Environment](https://github.com/OSSDC/self-driving-car-1) - development environment ready for Udacity Self Driving Car (SDC) Challenges.
* [The OSCC Project](http://oscc.io/) - A by-wire control kit for autonomous vehicle development.

### Calibration 
#### Camera 
* [ROS Camera Calibration](http://wiki.ros.org/camera_calibration)
* [Calibration board](https://github.com/jsk-ros-pkg/calibboard_sheet)
#### Lidar and Camera
* [but_calibration_camera_velodyne](https://github.com/robofit/but_velodyne/tree/master/but_calibration_camera_velodyne)
* [Autoware-calibration_camera_lidar](https://github.com/CPFL/Autoware/tree/master/ros/src/sensing/fusion/packages/calibration_camera_lidar)

### Visualization
* [jsk-visualization](http://jsk-visualization.readthedocs.io/en/latest/jsk_rviz_plugins)

### Mobile Apps (Android)
* [jsk_android_apps](https://github.com/jsk-ros-pkg/jsk_smart_apps/tree/master/jsk_android_apps)

### Mapping/Localizing/Odometry 
* [ethz-asl libpointmatcher](https://github.com/ethz-asl/libpointmatcher)
* [But Velodyne](https://github.com/robofit/but_velodyne_lib)

### Perception
* [jsk-recognition](https://jsk-recognition.readthedocs.io)


### Using Deep Learning
#### Obejct Detection
* [YOLO 2 in ROS](https://github.com/kunle12/dn_object_detect)


## Related Links
* [awesome-autonomous-vehicles](https://github.com/takeitallsource/awesome-autonomous-vehicles/)
* [awesome-vehicle-security](https://github.com/jaredthecoder/awesome-vehicle-security)
