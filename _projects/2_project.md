---
layout: page
title: ABU Robocon 2023 - Elephant & Rabbit Robots
description: Asia-Pacific Robotics Competition 2023, Cambodia
img: assets/img/2_abu_robocon_2023_robot_contest/robocon2023-theme-wallpaper.png
importance: 3
category: College Projects
---

This project was developed for ABU Robocon 2023, the Asia-Pacific Robotics Competition held in Cambodia. Our team created two robots: the **Elephant Robot** and the **Rabbit Robot**, using advanced computer vision and LiDAR-based pole detection for autonomous navigation and object identification.

## The Robots

<div class="row justify-content-sm-center">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/2_abu_robocon_2023_robot_contest/rabbit-robot.jpg" title="Rabbit Robot" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/2_abu_robocon_2023_robot_contest/elephant-robot1.jpg" title="Elephant Robot" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Left: The Rabbit Robot with omni-wheel kinematics for agile movement. Right: The Elephant Robot designed for ring-throwing tasks.
</div>

## Rabbit Robot Design

The Rabbit Robot features a 4-wheel omni-wheel kinematics system for agile movement and precise positioning. It uses advanced computer vision and LiDAR-based pole detection for autonomous navigation.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/2_abu_robocon_2023_robot_contest/rabbit-robot-1.jpg" title="Rabbit Robot Front View" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/2_abu_robocon_2023_robot_contest/rabbit-robot-2.jpg" title="Rabbit Robot Side View" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/2_abu_robocon_2023_robot_contest/rabbit-robot-base-4-wheel-omni-kinematics.jpg" title="Omni-Wheel Base" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Rabbit robot design featuring omni-wheel kinematics for precise movement control.
</div>

## Elephant Robot Design

The Elephant Robot was designed for the ring-throwing task, incorporating mechanical systems and precision control mechanisms.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/2_abu_robocon_2023_robot_contest/elephant-robot-throws-ring.jpg" title="Ring Throwing Mechanism" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/2_abu_robocon_2023_robot_contest/me-with-elephant-robot-tuning-parameters.jpg" title="Parameter Tuning" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Left: Elephant robot ring-throwing mechanism in action. Right: Fine-tuning robot parameters.
</div>

## Rabbit Robot Slope Climbing Demo

The Rabbit Robot demonstrates its climbing capabilities on inclined surfaces during testing.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <video class="img-fluid rounded z-depth-1" controls autoplay loop>
            <source src="/assets/img/2_abu_robocon_2023_robot_contest/rabbit-robot-learning-to-climb-sleop.mp4" type="video/mp4">
            Your browser does not support the video tag.
        </video>
    </div>
</div>
<div class="caption">
    Rabbit robot learning to climb slopes during testing phase.
</div>

## Technical Implementation

Both robots utilized the scikit-learn framework's DBSCAN clustering algorithm and Nearest Neighbors library for detecting field poles using 2D LiDAR point cloud data, enabling accurate identification and localization of the nearest pole within the game environment.

<div class="row justify-content-sm-center">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/2_abu_robocon_2023_robot_contest/robocon2023-matches-schedule.jpg" title="Competition Schedule" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/2_abu_robocon_2023_robot_contest/team-with-rabbit-robot.jpg" title="Team with Robot" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The competition schedule and our team posing with the rabbit robot.
</div>

## Competition Experience

The Nepal team participated in ABU Robocon 2023 held in Phnom Penh, Cambodia. The team worked tirelessly to prepare for the international competition, demonstrating advanced robotics capabilities and teamwork.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/2_abu_robocon_2023_robot_contest/cambodia-intro-opening-ceremony.jpg" title="Opening Ceremony" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/2_abu_robocon_2023_robot_contest/nepal-team-in-phnom-phenh.jpg" title="Nepal Team in Cambodia" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/2_abu_robocon_2023_robot_contest/nepal-team-ready-for-match-competition.jpg" title="Ready for Competition" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Opening ceremony, team arrival in Cambodia, and preparation for matches.
</div>

## Achievement

The project earned the prestigious Mabuchi Motor Award at ABU Robocon 2023, recognizing the team's technical excellence and innovation in robotics design and implementation.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/2_abu_robocon_2023_robot_contest/nepal-team-receiving-mabuchi-motor-award.jpg" title="Receiving Mabuchi Motor Award" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/2_abu_robocon_2023_robot_contest/me_carrying_mabuch_motor_award.jpg" title="With Mabuchi Motor Award" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The Nepal team receiving the Mabuchi Motor Award and proudly displaying the achievement.
</div>

## Team Collaboration

The project showcased excellent teamwork and international collaboration, with the Nepal team engaging with other participating teams and supporters during the competition.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/2_abu_robocon_2023_robot_contest/nepal-team-with-veitname-team.jpg" title="With Vietnam Team" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/2_abu_robocon_2023_robot_contest/nepal-team-supporter-in-stadium.jpg" title="Supporters in Stadium" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/2_abu_robocon_2023_robot_contest/717247914_969685699276982_2152772285288802424_n.jpg" title="Competition Moment" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    International collaboration with other teams, supporter engagement, and memorable competition moments.
</div>

## Debug Sessions

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/2_abu_robocon_2023_robot_contest/rabbit-robot-debug-session-after-first-match.jpg" title="Debug Session After First Match" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Debug session after the first match to analyze performance and improve robot functionality.
</div>

## External Resources

### Competition Websites

- <a href="https://robotics.pcampus.edu.np/robocon/2023/" target="_blank">ABU Robocon 2023 Nepal Team Website</a>
- <a href="https://robotics.pcampus.edu.np/" target="_blank">Robotics Club, Pulchowk Campus</a>
- <a href="https://en.wikipedia.org/wiki/ABU_Robocon" target="_blank">ABU Robocon Wikipedia</a>

### Competition Match Videos

- <a href="https://www.youtube.com/watch?v=uhSunMUO-Mk" target="_blank">Nepal vs China Match - ABU Robocon 2023</a>
- <a href="https://www.youtube.com/watch?v=x6yWKgoqcsk" target="_blank">Nepal vs Hong Kong Match - ABU Robocon 2023</a>
- <a href="https://www.youtube.com/watch?v=XVBwyUMJKO4" target="_blank">Nepal vs Egypt Match - ABU Robocon 2023</a>
- <a href="https://www.youtube.com/watch?v=2JjJlKdaBr4" target="_blank">Practice Session - Robotics Club Pulchowk Campus</a>