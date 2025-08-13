---
name: Design and 3D printing of externally powered prosthetic arm controlled by Brain Computer Interface for below elbow amputees
tools: [EMOTIV EPOCX, EMOTIV PRO, PsychoPy, Python, MNE-Python]
image: https://naitikdalwadi.github.io/assets/images/BCI_thumbnail.png
description: machine learning-driven brain-computer interface (BCI) framework for controlling a 3D-printed prosthetic arm based on electroencephalography (EEG) signals.
---

# Design and 3D printing of externally powered prosthetic arm controlled by Brain Computer Interface for below elbow amputees

Brain activity originating from the somatosensory and motor areas is referred to as sensorimotor rhythms (SMR). Both actual limb movement and the imagination of movement lead to changes in SMR. Brain oscillations are classified into frequency bands as follows: delta (<4 Hz), theta (4–7 Hz), alpha (8–12 Hz), beta (12–30 Hz), and gamma (>30 Hz). In the sensorimotor area, alpha activity is typically recorded.

The brain activity is recorded non-invasively using the EMOTIV EPOCX 14-channel brain sensor. To capture human brain activity during motor tasks, a synchronous-BCI experiment is designed in PsychoPy, in which visual stimuli of the right and left hand are presented alternately for a specific duration. During each stimulus, the subject closes and opens the fist of the corresponding hand. In this experiment, 15 visual stimuli for the right hand and 15 for the left hand are presented to 30 subjects of varying age groups and genders. The brain activity data is recorded using the EMOTIV PRO software.

After collecting the brain activity data from the 30 subjects, exploratory data analysis was performed to prepare it for training a classification model, which is capable of detecting specific patterns characterized by certain amplitudes and frequencies. The trained model is then used to classify any unlabeled patterns. Subsequently, the BCI system translates these classifications into appropriate commands, which actuate the prosthetic arm into a predefined grip.

<!-- ![feeding arm drawing](/assets/images/feeding_arm.png) -->

## Problem Statement

Upper limb amputees often face challenges in performing daily routine tasks. The major causes of upper limb amputation include crush injuries, accidents, electric shocks, and diseases such as gangrene. In India alone, there are more than 0.5 million amputees, with approximately 23,500 new cases reported each year. This presents a significant concern, highlighting the need for efforts to improve the quality of life for amputees. Through the use of brain-computer interface (BCI) technology, direct interaction between the brain and an externally powered prosthetic arm can be established.

## My Role

- BCI Experiment Design: Designed a synchronous Brain-Computer Interface (BCI) experiment using PsychoPy, presenting sequential visual cues of right and left hands to indicate corresponding fist movements to the subject.

- Data Acquisition: Collected brain activity data from 30 subjects during motor imagery and actual motor tasks using the EMOTIV EPOCX 14-channel EEG headset.

- Data Analysis: Conducted exploratory data analysis (EDA) on the recorded EEG signals using pandas and NumPy for preprocessing.

## Achievement/Recognition

- Presented the paper *Machine Learning-Based Electroencephalography Signal Processing for Prosthetic Arm Control* at the 7th International Conference – Advances in Robotics, organized by the Robotics Society of India.

<!-- 
<p class="text-center">
{% include elements/button.html link="https://www.linkedin.com/feed/update/urn:li:activity:7283171170512769024/" text="Working Video" %}
</p>
-->