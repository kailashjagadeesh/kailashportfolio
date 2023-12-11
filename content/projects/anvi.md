---
title: "ANVI"
description: "Affordable wearable for visually impaired: integrates deep learning, LIDAR, safety features, providing audio instructions for enhanced accessibility."
dateString: Dec 2021 - May 2022
draft: false
tags: ["Python", "OpenCV", "CNN", "Transformers", "DL", "Sensor Fusion", "Microcontrollers"]
showToc: false
weight: 204
cover:
    image: "projects/anvi/cover.png"
--- 
<div style="text-align: justify">

<h1> Objective </h1>
As the primary mentor for this project, our goal was to cater to the needs of visually impaired individuals by creating a wearable, cost-effective device that provides audio instructions based on the user's surroundings.

<h2> Tech Stack </h2>

- **Deep Learning Models:** CLIP and LXMERT
- **Computation Platforms:** Raspberry Pi, Jetson Nano
- **Sensors:** Time-of-flight-based LIDAR, MPU6050
- **Safety Features:** Fall detection, GPS tracking, Obstacle detection
- **Power Source:** Li-Po Battery
![](/projects/anvi/img1.jpg)

<h2> Key Features </h2>

- Wearable prototype offering audio instructions for enhanced user understanding.
- Utilizes CLIP and LXMERT deep learning models for image captioning and visual question answering.
- Wireless camera on the headband captures images, processed on Raspberry Pi or Jetson Nano.
- Safety features include fall detection via MPU6050 and obstacle detection through LIDAR.
- Vibration feedback from haptic motors helps users navigate obstacles effectively.
- GPS tracking for location-based services and emergency contacts notified in case of a fall.

This device not only addresses the accessibility needs of the visually impaired but does so with an emphasis on safety and affordability. The combination of cutting-edge technology and thoughtful design makes it a promising solution in assistive technology.

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
    <a href="https://youtu.be/qKCRdq6o9OM"><img src="/icons/youtube.png" width="50" height="50" style="justify-content: space-between;" /></a>
  </div>
  <div class="grid-item">
    <a href="https://github.com/RMI-NITT/ANVI"><img src="/icons/github.png" width="50" height="50" style="justify-content: space-between;"  /></a>
  </div>

</div>
