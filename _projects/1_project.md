---
layout: page
title: Self Driving Car- Mapping, Path Planning & Navigation
description: Autonomous vehicle with ROS2, SLAM, and object detection
img: assets/img/1_autonomous_car_project/autonomous-car.png
importance: 1
category: College Projects
---

This project focuses on the development of a Self-Driving Car (SDC) emphasizing Mapping, Path Planning, Obstacle Detection and Avoidance. The system utilizes advanced Artificial Intelligence (AI) techniques, high-precision mapping using Lidar and Camera, and implements both PID controllers and Model Predictive Control (MPC) for optimal vehicle motion.

## Project Overview

<div class="row justify-content-sm-center">
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/1_autonomous_car_project/autonomous-car.png" title="System Overview" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The autonomous car test platform.
</div>

## Technical Implementation

The project integrates Robot Operating System (ROS) framework for enhanced system speed. Advanced algorithms process real-time data for path planning, calculating optimal routes while considering pedestrians on the road.

## Mapping and Perception

The system implements high-precision mapping using physical systems such as Lidar and Camera, enabling accurate environmental perception. SLAM (Simultaneous Localization and Mapping) algorithms generate accurate Lidar-based maps of static environments.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/1_autonomous_car_project/creating-map-in-ros-rviz-in-college-road-so-noone-is-in-the-road.jpg" title="Creating Map in ROS RViz" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/1_autonomous_car_project/picture-of-planned-path-around-robotics-club-for-sdc-to-run-autonmously.png" title="Planned Path Around Robotics Club" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Left: Creating map in ROS RViz on college road at night. Right: Planned path around robotics club for autonomous navigation.
</div>

## Dataset and Object Detection

The project involved creating a comprehensive dataset for object detection model training, enabling the car to recognize and avoid obstacles in real-time.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/1_autonomous_car_project/dataset-creating-object-detection-model-traning.png" title="Dataset Creation for Object Detection" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Dataset creation process for object detection model training.
</div>

## Navigation and Control

For optimal vehicle motion, the system implements both Proportional-Integral-Derivative (PID) controllers and Model Predictive Control (MPC). The nav2 stack is incorporated for autonomous navigation and real-time path planning.

## Development Videos

### Initial Testing Phase

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <video class="img-fluid rounded z-depth-1" controls autoplay loop>
            <source src="/assets/img/1_autonomous_car_project/red-car-working-with-rear-motor-and-servo-motor-in-steering-first-initialphase.mp4" type="video/mp4">
            Your browser does not support the video tag.
        </video>
    </div>
</div>
<div class="caption">
    Red car working with rear motor and servo motor steering in the initial testing phase.
</div>

### ROS Teleoperation

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <video class="img-fluid rounded z-depth-1" controls autoplay loop>
            <source src="/assets/img/1_autonomous_car_project/red-car-working-with-ros-telop-from-keyboard.mp4" type="video/mp4">
            Your browser does not support the video tag.
        </video>
    </div>
</div>
<div class="caption">
    Red car controlled via ROS teleoperation from keyboard.
</div>

### Dataset Creation for Road Detection

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <video class="img-fluid rounded z-depth-1" controls autoplay loop>
            <source src="/assets/img/1_autonomous_car_project/sdc_dataset_createion_for_road_detection1.mp4" type="video/mp4">
            Your browser does not support the video tag.
        </video>
    </div>
</div>
<div class="caption">
    Dataset creation process for road detection model training.
</div>

## Demo Video

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
    <video class="img-fluid rounded z-depth-1"
        style="max-height: 400px; width: auto; display: block; margin: 0 auto;"
        controls autoplay loop>
        <source src="/assets/img/1_autonomous_car_project/demo-video-of-overall-autonomous-car-projects.mp4" type="video/mp4">
    </video>
    </div>
</div>
<div class="caption">
    Demo video of the autonomous car project showcasing mapping, navigation, and obstacle avoidance capabilities.
</div>

## Additional Resources

### Documentation

- <a href="/assets/img/1_autonomous_car_project/SDC_PROPOSAL.pdf" target="_blank">Project Proposal (PDF)</a>
- <a href="/assets/img/1_autonomous_car_project/SDC_Final_Report.pdf" target="_blank">Final Project Report (PDF)</a>
- <a href="/assets/img/1_autonomous_car_project/SDC_Presentation.pdf" target="_blank">Project Presentation (PDF)</a>
- <a href="/assets/img/1_autonomous_car_project/SDC_PROGRESS_REPORT.pdf" target="_blank">Progress Report (PDF)</a>

### Technical Videos

- <a href="/assets/img/1_autonomous_car_project/turtle-bot-working-ros2-topics-publish-subscribe-model-from-laptop-keyboard.mp4" target="_blank">ROS2 Topics Demo (MP4)</a>

## Team

**Project Members:**
- Aarjan Budathoki (PUL077BEI004)
- Abhigyan Bhusal (PUL077BEI007)
- Manish Guruwacharya (PUL077BEI021)

**Submitted to:** Department of Electronics & Computer Engineering, Institute of Engineering, Pulchowk Campus, Tribhuvan University (March, 2024)