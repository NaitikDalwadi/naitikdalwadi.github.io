---
name: Autonomous Delivery Robot with Real-time Obstacle Avoidance
tools: [ROS, Python, Jetson Nano, Additive Maufacturing (Fused Deposition Modeling), Arduino,Solidworks, Fusion360]
image: https://www.sketchappsources.com/resources/source-image/movie-badges-jurajjurik.png
description: This robot aims to autonomously deliver items in indoor environments such as hospitals, malls, offices, restaurants, warehouses, etc. from one point to another.
---

# Autonomous Delivery Robot with Real-time Obstacle Avoidance

The robot aims to deliver items autonomously without any need for human interference in indoor environment. It can deliver items
safely and securely and avoid static and dynamic obstacles in real-time. Also, the camera inside the robot provides a live video
feed that can be seen by the user. For secure delivery, a servo locking mechanism is provided which unlocks the specific door when
an authorized QR code is shown in front of the camera. A buzzer sounds if any unknown QR code is detected, indicating that someone
has tried to gain unauthorized access and take the delivery items.

![preview](https://www.sketchappsources.com/resources/source-image/we-were-soldiers-landing-page-dbruggisser.jpg)

## Problem Statement

In places such as malls, offices, hospitals, etc. if there is a need to deliver some items from one point to another, people need to
deliver it manually or some person is hired for this job. The manual delivery process can be tiresome and exhausting if the area is
very large. Hence, we have made an autonomous delivery robot based on ROS (Robot Operating System) to tackle this problem.

## My Role

- Hardware Setup: Configured the Jetson Nano and deployed it as the onboard computing unit.

- Sensor Integration: Integrated a 2D-LIDAR sensor with Jetson Nano for environment perception.

- Robot Fabrication: 3D printed all robot components using the Fused Deposition Modeling (FDM) technique.

- Mobility & Mapping: Implemented a differential drive mechanism and generated indoor environment map through teleoperation.

- Autonomous Navigation: Deployed and fine-tuned the ROS Navigation Stack to enable real-time obstacle avoidance and autonomous path planning.

## Achievement

- Secured 2nd position in the Mechanical Engineering Department at the Project Expo organized by the Industry Institute Interaction Cell of our college.


<p class="text-center">
{% include elements/button.html link="https://github.com/yousinix/portfolYOU" text="Learn More" %}
</p>