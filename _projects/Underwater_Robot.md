---
name: Underwater Robot
tools: [Solidworks, Additive Manufacturing (Fused Deposition Modeling), Arduino Nano, ESP 32]
image: https://naitikdalwadi.github.io/assets/images/underwater_thumbnail.png
description: It is a 3-DoF underwater robot powered by an onboard power supply. The command signals are received by a floating receiver, which then transmits these signals to the robot via a cable.
---

# Underwater Robot

- The mechanical design of this robot features a hydrodynamic shape to minimize the drag force acting on it. It comprises the main body, an acrylic base plate, and propellers. Both the body and propellers are manufactured using the Fused Deposition Modeling (FDM) 3D-printing technique. A gasket, placed between the robot body and base plate, is used to ensure waterproofing. 
- The robot operates according to a predefined vector diagram to move forward, backward, right, and left. 
- Command signals are transmitted wirelessly to a floating receiver, which then sends the signals via cable to the ESP32 microcontroller. The ESP32 forwards the signals to the corresponding ESCs to control the speed and direction of the propellers, ultimately maneuvering the robot. The salient features of the robot are as follows:
1. Easily attachable and detachable battery box
2. High Resolution Camera
3. Waterproof spot light

- This robot can be used for underwater shooting, bathymetry survey and underwater inspection.


![underwater robot drawing](/assets/images/underwater_motion.png)

## Problem Statement

This project is part of the state-level robotics competition Robofest 2.0, organized by the Gujarat Council on Science and Technology, Government of Gujarat, India. The objectives specified for the Underwater Robot category are as follows:

- An underwater robot which has the ability to be completely submerged and has the ability to move in 3 degrees of freedom (up, down, front back and left right). Needs to be immersed at least 4 feet depth.

- Wirelessly controlled and battery-operated underwater robot which stays below 4 feet depth for at least 5 minutes.


## My Role

- Propeller Design and Simulation: Designed propellers and conducted simulations to evaluate multiple configurations for optimal thrust.

- Manufacturing: Manufactured the robot body and propellers using the Fused Deposition Modeling (FDM) 3D printing technique.

- Waterproofing: Implemented waterproofing solution to ensure reliable operation in under-water environments.

- Motion Planning: Designed a vector diagram to define and control robot motion in multiple directions.

## Achievement/Recognition

- Secured 1st place in the Underwater Robot category at Robofest 2.0 and won a prize of 5,00,000 INR.
- Inventor 1, Naitik Dalwadi, Inventor 2, Darshit Darji et al. Underwater Robot. Indian Patent Office, Patent No. 356337-001 Registration Date: 07/01/2022, Grant Date: 12/09/2023.


<p class="text-center">
{% include elements/button.html link="https://www.youtube.com/watch?v=d-sza2mzV4o" text="Working Video" %}
</p>