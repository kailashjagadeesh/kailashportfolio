---
title: "Pepper"
description: "an advanced personal assistant with SLAM, Microsoft Kinect, ROS Gazebo, and Deep Learning for efficient navigation and intelligent object interaction."
dateString: Dec 2020 - May 2021
draft: false
tags: ["Python", "PyTorch", "CNN", "SLAM", "Object Recognition", "DL", "Multi-agent system"]
showToc: false
weight: 205
cover:
    image: "/projects/pepper/cover.jpg"
--- 
# Objective
As a dedicated member of this project, I played a crucial role in developing Pepper, a versatile personal assistant platform utilizing various artificial intelligence algorithms.

<h2> Technology Stack</h2>
 
- **SLAM**
- **Microsoft Kinect**
- **ROS Gazebo**
- **Deep Learning**
![](/projects/pepper/img1.png)

<h2> Robot Design</h2>
The robot's chassis, designed using Autocad and fabricated with acrylic, features three layers housing components such as the battery, driver, gripper arm, and onboard computer. Microsoft Kinect is mounted on the top pedestal, while high-torque motors and a castor wheel ensure stable movement.

<h2> Mapping</h2>
Pepper optimally navigates its environment by creating a map using the onboard Kinect sensor and the gmapping ROS package, employing the Simultaneous Localisation and Mapping Algorithm (SLAM).

<h2> Localisation</h2>
To address wheel drift, we implemented the Kalman filter algorithm, combining data from multiple sensors, including encoders and a gyroscope, for accurate pose estimation.

<h2> Speech Recognition</h2>
Utilizing a text-independent machine learning algorithm, Pepper identifies speakers through voice samples, employing Mel Frequency Cepstral Coefficient (MFCC) Vectors for training and real-time recognition.

<h2> Object Recognition and Pick up</h2>
Trained with a Convolutional Neural Network (CNN) on 1000 object classes, Pepper captures and measures object depth using Kinect. The robotic arm, equipped with 3 degrees of freedom, approaches objects based on depth, and the gripper, with 1 DoF, picks up recognized objects.

This project seamlessly integrates SLAM, Microsoft Kinect, ROS Gazebo, and Deep Learning to empower Pepper as an advanced personal assistant, capable of efficient navigation, speech recognition, and intelligent object interaction.

<h3> Quick Links </h3>
<!--- this is for the link icons  --->
<meta name="viewport" content="width=device-width, initial-scale=1" />
<style>
  /* styles for grid container */
  .grid-container {
    display: grid;
    grid-template-columns: 60px 1fr;
    
    position: relative;
  }

  .grid-item {
    overflow: hidden;
  }
</style>
<div class="grid-container">
  <div class="grid-item">
    <a href="https://www.youtube.com/watch?v=RHS6B5DbNY4"><img src="/icons/youtube.png" width="50" height="50" style="justify-content: space-between;" /></a>
  </div>
  <div class="grid-item">
    <a href="https://github.com/RMI-NITT/Pepper_DRL_MAExploration"><img src="/icons/github.png" width="50" height="50" style="justify-content: space-between;"  /></a>
  </div>

</div>
