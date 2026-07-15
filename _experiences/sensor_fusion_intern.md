---
layout: page
title: ADAS Perception Intern
description: LiDAR-based perception algorithms for autonomous driving systems
img: assets/img/experience/sensor_fusion_intern.jpg
importance: 1
category: Research Experience
---

3-month internship (18 hrs/week) focusing on ADAS perception algorithms, sensor fusion, and autonomous driving systems using Velodyne LiDAR technology at LogicTronix.

## Company Information

**Position:** ADAS Perception Intern  
**Company:** LogicTronix [FPGA Design & Machine Learning Company]  
**Location:** Lalitpur, Nepal  
**Duration:** Dec 2024 - Mar 2025 (18 hrs/week)  
**Focus Areas:** SDC, Perception, ADAS

## Overview

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/aarjan-hwf.JPG" title="ADAS Perception Work" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Working with Velodyne LiDAR sensors for ADAS perception algorithm development.
</div>

## Key Responsibilities

### Data Acquisition & Visualization
- Developed robust pipelines for data acquisition & visualization of Velodyne 3D LiDAR sensor data using the Point Cloud Library (PCL)
- Implemented real-time data processing pipelines for efficient point cloud handling

### Dataset Creation & Annotation
- Annotated custom 3D point cloud datasets using 3D bounding box labeling tools (Latte)
- Created labeled datasets for training object detection models targeting pedestrians, vehicles, and traffic objects

### Point Cloud Processing & Optimization
- Implemented voxel grid down-sampling algorithms to optimize point cloud density for computationally efficient processing
- Developed Kd-Tree data structure from scratch in C++ to accelerate nearest-neighbor search operations on large-scale point clouds

### Ground Plane Segmentation
- Implemented RANSAC-based ground plane segmentation in C++ to effectively isolate dynamic objects such as pedestrians and vehicles from static ground surfaces
- Optimized segmentation algorithms for real-time performance in autonomous driving scenarios

### Object Detection & Classification
- Implemented DBSCAN clustering algorithm in C++ for object detection and classification
- Developed clustering pipelines targeting pedestrians, vehicles, and traffic objects for ADAS applications

## Technical Skills

**Programming Languages:**
- C++
- Python
- Shell scripting

**Technologies & Tools:**
- Velodyne LiDAR sensors
- Point Cloud Library (PCL)
- ROS2 (Robot Operating System 2)
- Linux operating systems
- Git version control
- 3D bounding box labeling tools (Latte)
- Gazebo simulation environment

**Algorithms & Data Structures:**
- RANSAC (Random Sample Consensus)
- DBSCAN (Density-Based Spatial Clustering)
- Kd-Tree implementation
- Voxel grid down-sampling
- Ground plane segmentation

## Internship Documentation

### Complete Work Report
- [ROS_ADAS_Intern_Complete_Work_Report.pdf](/assets/pdf/adas-intern-documentation/ROS_ADAS_Intern_Complete_Work_Report%20.pdf) - Comprehensive documentation of all work completed during the 3-month internship

### ADAS Systems & Autonomous Driving Research

**Advanced Driver Assistance Systems (ADAS) Industry Overview**
- Studied autonomous driving platforms including [Waymo's EMMA](https://waymo.com/) (End-to-End Multimodal Model for Autonomous Driving) using Google's Gemini for processing sensor data and generating future trajectories
- Analyzed Mercedes MB.OS with NVIDIA DRIVE platform integration for AI/ML components and over-the-air updates
- Researched NVIDIA DriveOS with CUDA libraries, TensorRT for real-time AI inference, and NvMedia for sensor processing
- Examined Tesla Autopilot's 8-camera fusion system using RegNet, biFPN, and transformer models for feature extraction and vector space creation
- Investigated 4D-Net for learned multimodal alignment combining 3D point clouds and RGB camera images for 3D object detection

**CARLA Simulator & ROS Integration**
- Studied [CARLA](https://carla.org/) platform for autonomous vehicle simulation with unlimited sample generation for LiDAR training data
- Analyzed lane finding using polynomial fitting, waypoint navigation, and object detection using CNN
- Explored classical PID control and Stanley method for lateral and longitudinal vehicle control
- Implemented carla-ros-bridge library for ROS communication and cv-bridge for OpenCV image conversion

### ROS2 Fundamentals & Simulation

**ROS2 Core Concepts**
- Mastered [ROS2](https://docs.ros.org/en/humble/) fundamentals including nodes, topics, publishers, subscribers, and launch files
- Learned RViz vs Gazebo distinction: RViz visualizes robot's perception, Gazebo simulates physical world with forces
- Implemented Gazebo simulation environment with URDF/SDF robot models and sensor plugins
- Configured Gazebo-specific tags and plugins for ROS integration and sensor data publishing

**ROS2 Control Framework**
- Studied ros2_control framework as kernel for ROS2 robotics systems
- Implemented Controller Manager, Resource Manager, Hardware Components (System, Sensor, Actuator)
- Worked with common controllers: diff_drive_controller for mobile robots, joint_trajectory_controller for articulated arms
- Configured transmission elements for joint movement control and friction simulation

**MoveIt2 Motion Planning**
- Installed and configured [MoveIt2](https://moveit.picknik.ai/) for motion planning of industrial robots (Panda, Doosan, ABB, Fanuc, Kuka)
- Implemented C++ motion planning using MoveIt2 interfaces without complex lambda expressions
- Created trajectory planning with FollowJointTrajectory controllers and GripperCommand for end-effectors
- Configured robot_state_publisher for URDF processing and TF broadcasting

### LiDAR Sensor Technology & Integration

**Velodyne LiDAR Systems**
- Studied Velodyne product line: [VLP-16](https://velodynelidar.com/products/vlp-16/) (100m range, 360°×30° FoV), Ultra Puck, HDL-32E, and solid-state Velarray
- Analyzed VLP-16 specifications: 300,000 points/sec, 16 channels, 2° vertical resolution, 5-20 Hz rotation rate
- Configured VLP-16 interface with UDP packet processing, GPS synchronization, and web server monitoring
- Implemented VeloView for real-time 3D LiDAR data visualization and processing

**LiDAR Performance Metrics**
- Studied detection range (100m+ for VLP-16), range precision/accuracy, field-of-view considerations
- Analyzed angular resolution, scan patterns, cross-talk immunity, and detection rates
- Implemented time synchronization with GPS/PPS signals for precise data timestamps
- Configured multiple return modes for object height measurement and vegetation analysis

**ROS2 Sensor Integration**
- Integrated Velodyne LiDAR with ROS2 using velodyne_pointcloud and pointcloud_to_laserscan packages
- Implemented laser_scan_matcher for scan matching with point cloud and IMU inputs
- Configured sensor_msgs/PointCloud2 and sensor_msgs/LaserScan message types
- Developed USB camera integration with ROS2 for multi-sensor fusion
- **Demo Output:** [3D coordinates from 2D A1 RP LIDAR](https://www.youtube.com/watch?v=d6VZ-Dzqsio)

### Point Cloud Processing & Algorithms

**Voxel Grid Downsampling**
- Implemented [voxel grid filtering](https://pcl.readthedocs.io/projects/tutorials/en/master/voxel_grid.html) using [Point Cloud Library (PCL)](https://pointclouds.org/) to reduce point cloud density for computational efficiency
- Optimized processing pipeline for real-time performance on large-scale point clouds
- Balanced data reduction with preservation of important geometric features

**RANSAC Ground Plane Segmentation**
- Implemented [RANSAC](https://en.wikipedia.org/wiki/Random_sample_consensus)-based [ground plane segmentation](https://www.thinkautonomous.ai/blog/ransac-algorithm/) in C++ to isolate dynamic objects
- Used MSAC (M-estimator Sample Consensus) variant for robust ground extraction
- Processed point clouds to separate pedestrians, vehicles from static ground surfaces
- Evaluated ground removal as essential preprocessing step for object detection

**DBSCAN Clustering Implementation**
- Implemented [DBSCAN](https://en.wikipedia.org/wiki/DBSCAN) (Density-Based Spatial Clustering of Applications with Noise) in C++
- Configured parameters: epsilon (radius) and minimum points (m=6 for 3D data)
- Applied K-distance graph analysis for optimal epsilon parameter selection
- Achieved clustering of 167 objects with 832 noise points in H3D dataset testing
- **Demo Outputs:**
  - [DBSCAN Clustering of Kitti 3D Point Cloud Data](https://www.youtube.com/shorts/PsrChUrvEMU)
  - [Euclidean Clustering of Kitti 3D Point Cloud Data](https://www.youtube.com/shorts/BWSfETNt8Wk)

**Kd-Tree Data Structure**
- Developed [Kd-Tree](https://en.wikipedia.org/wiki/K-d_tree) from scratch in C++ for accelerated nearest-neighbor search operations
- Optimized spatial indexing for large-scale point cloud processing
- Improved computational efficiency for real-time clustering applications

### Dataset Creation & Annotation

**Custom 3D Point Cloud Dataset**
- Created custom LiDAR point cloud datasets focusing on pedestrian and vehicle detection
- Collected and processed VLP-16 data with quality assessment using Veloview visualization
- Addressed sparse point cloud challenges at different distances (density variation formula: d = 2 × r × tan(θ/2))

**LiDAR Annotation Tools**
- Evaluated annotation tools: LabelCloud (Velodyne official), Autoware.AI, Scale AI, CVAT, [Latte](https://github.com/bernwang/latte)
- Implemented Latte (3D-bat fork) for single-click 3D bounding box annotation on point clouds
- Used sensor fusion approach with image-based detection algorithms for pre-labeling
- Projected 2D image segmentation masks to 3D point clouds for automated labeling

**KITTI Dataset Format**
- Converted custom datasets to KITTI format with 14-field array structure
- Implemented 3D bounding box format: height, width, length, x, y, z, rotation_y
- Added 2D bounding boxes for camera images and shared fields (truncation, occlusion, class)
- Validated annotation quality through visualization and comparison with KITTI labeled data

**LiDAR Calibration**
- Studied intrinsic calibration for internal timing and distortion corrections
- Analyzed extrinsic calibration for sensor alignment with cameras and IMUs
- Addressed VLP-16 systematic errors: vertical/horizontal rotation offsets, distance offsets
- Implemented calibration procedures for improved localization and mapping precision

### Deep Learning Frameworks for 3D Object Detection

**PointPillars Architecture**
- Studied PointPillars: lightweight 3D object detection using pseudo-image conversion and 2D CNN
- Analyzed feature encoder using PointNets for point cloud representation in vertical pillars
- Examined 2D CNN backbone for high-level feature processing and detection head for 3D box generation
- Compared with PV-RCNN (accurate but expensive) and SECOND (sparse 3D CNNs)

**OpenPCDet & MMDetection3D**
- Explored deep learning frameworks: OpenPCDet (PyTorch-based), MMDetection3D
- Studied data format requirements: voxelized format for SECOND, BEV for PointPillars, raw point cloud for PointRCNN
- Analyzed model architectures and computational trade-offs for real-time applications

### Research Findings & Performance Analysis

**Clustering Algorithm Comparison**
- DBSCAN outperformed K-means for arbitrarily shaped clusters (vehicles, pedestrians)
- K-means showed better internal validation indexes but visually over-segmented objects
- DBSCAN struggled with closely spaced objects, merging them into single clusters
- Ground removal (RANSAC/MSAC) significantly improved clustering quality in all scenarios
- DBSCAN preferred for urban scenarios with multiple objects; K-means less suitable for highway scenes

**Distance-Based Clustering Challenges**
- Identified point cloud density variation with distance: 8.38cm at 2.4m vs 39.5cm at 11.3m for VLP-16
- Analyzed under-segmentation (threshold too large) and over-segmentation (threshold too small) issues
- Implemented circular zone division approach: nested circular regions with adaptive distance thresholds
- Applied ring-based segmentation with 2.8m width and 0.1m increments for reliable human detection

**Technical Challenges & Solutions**
- Resolved network configuration issues in Gazebo by editing /etc/hosts file
- Fixed MoveIt2 installation errors by installing missing packages and header files
- Addressed git conflicts using rebase and resolved large file upload issues with Git LFS
- Implemented proper rosdep update procedures without sudo to avoid permission errors

## Key Learnings

- Hands-on experience with industrial-grade Velodyne LiDAR sensors and point cloud processing
- Deep understanding of autonomous driving perception algorithms and ADAS systems
- Real-time C++ development for safety-critical applications
- Professional software development practices in FPGA and ML company environment
- Practical implementation of advanced algorithms (RANSAC, DBSCAN, Kd-Tree) for perception tasks
- Experience with ROS2 ecosystem and sensor integration for autonomous systems

---

*This internship provided comprehensive experience in ADAS perception development, from raw sensor data processing to object detection and classification, essential for autonomous driving systems.*