---
title: "OpenQuad"
description: "Open-souce platform for drone automation"
dateString: Jul 2020 - Mar 2021
draft: false
tags: ["Drone", "Raspberry Pi", "Python", "Computer Vision", "Automation", "docker"]
showToc: false
weight: 206
cover:
    image: "projects/openquad/cover.jpg"
--- 
<div style="text-align: justify">

<h1>Project Overview</h1>
As the primary member leading this project, the focus is on developing an open-source quadcopter platform for advancing research in drone autonomy. The project encompasses the implementation of various deep learning and computer vision algorithms, including person tracking, gesture control using human pose estimation, optical flow stabilization, obstacle avoidance, and depth estimation using monocular vision.

<h2> Objectives and Contributions </h2>

The primary objectives of this project include:

- Building an open-source quadcopter platform for research in drone autonomy.
- Implementing deep learning and computer vision algorithms for person tracking, gesture control, optical flow stabilization, obstacle avoidance, and depth estimation.
- Utilizing a Pixhawk flight controller with Raspberry Pi as a companion computer for efficient control.
- Employing DJI Flame Wheel-450 for the quadcopter frame, customized with additional mountings for extra components.
![](/projects/openquad/img1.jpg)

<h2> Technology Stack</h2>

The technology stack for this project includes:

- **Pixhawk Flight Controller**
- **Raspberry Pi**
- **ROS (Robot Operating System)**
- **Gazebo Simulation**
- **Docker Containers**

<h2> Project Implementation</h2>

The Raspberry Pi runs a ROS node, establishing communication with another ROS node on the host PC to transfer videos over Wi-Fi. To ensure the project's open-source nature and ease of development, the simulation environment setup is dockerized using Docker containers. The ongoing development involves implementing and testing algorithms within the Gazebo Simulation.

<h2> Conclusion</h2>

This project contributes to the field of drone autonomy research by providing an open-source platform with advanced features such as person tracking, gesture control, optical flow stabilization, obstacle avoidance, and depth estimation. The utilization of industry-standard components like Pixhawk and Raspberry Pi enhances the project's accessibility and reproducibility.

</div>


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
    <a href="https://github.com/RMI-NITT/openquad"><img src="/icons/github.png" width="50" height="50" style="justify-content: space-between;"  /></a>
  </div>

</div>
