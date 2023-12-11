---
title: "SPARO"
description: "NeRF-based system for creating editable 3D models from minimal images using Tensorflow and Pytorch."
dateString: Nov 2021 - May 2022
draft: false
tags: ["Python", "PyTorch", "DL", "NeRF"]
showToc: false
weight: 203
cover:
    image: "/projects/sparo/cover.png"
--- 
<div style="text-align: justify">


<h1> Objective</h1>
As the mentor for this project, I provided guidance in developing a system for creating editable 3D models of real-world objects using a minimal set of images, with a focus on leveraging Structure from Motion and Neural Radiance Fields.

<h2> Technology Stack</h2>

- **NeRF**
- **Tensorflow**
- **Pytorch**
- **Deep Learning**
![](/projects/sparo/img1.jpg)

<h2> Key Features </h2>
The project aims to revolutionize 3D reconstruction in virtual space, finding applications in scene rendering and self-driving cars. Key features include:

- **User-Input Image Processing:** Users provide images of the object, initiating the process.
- **Structure from Motion (SfM):** Determines the camera's relative position from the object, calculating relative poses.
- **Neural Radiance Fields (NeRF):** Utilizes deep learning concepts to output RGB color and opacity alpha of each voxel in 3D space.
- **Rendering Equation:** Integrates NeRF output to render the item's volume in the 3D space.
- **Editable 3D Models:** Creates editable 3D models from limited input images.

This project, powered by NeRF, Tensorflow, Pytorch, and Deep Learning, stands at the forefront of 3D reconstruction technology, offering a versatile solution for generating detailed and editable 3D models from minimal visual input.

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
    <a href="https://youtu.be/If1SxSkwnWg"><img src="/icons/youtube.png" width="50" height="50" style="justify-content: space-between;" /></a>
  </div>
  <div class="grid-item">
    <a href="https://github.com/Adithya-187326/PL_NeRF"><img src="/icons/github.png" width="50" height="50" style="justify-content: space-between;"  /></a>
  </div>

</div>
