# OphthNeRF

This is a project for ophthalmic Surgery Scene Medical Image Reconstruction, implemented in Python.

[*[Read the detailed project description(中文)]*](/documents/申报书.pdf)

# Preview

### Demo 

<div style="display: flex; justify-content: space-between;">
  <div>
    <img src="/imgs/demo.png" width = "400">
  </div>
</div>



# Functionalities
+ **In microscope-based medical scenarios, the perspective is fixed.** The project first needs to acquire event-based video imagery. Then, improvements and adaptations will be made to event-based depth estimation models for medical scenarios. This aims to overcome the challenges of low light and high contrast in medical image data under the microscope, enabling detailed depth estimation in microscope scenes.
+ **Extracting three-dimensional information from microscope scenes** using depth and RGB information is another challenge that needs to be overcome in this project. The camera input has a single perspective, making it challenging to extract three-dimensional information from monocular images. Additionally, the scenes under the microscope are small, and there is minimal depth variation in the fundus, which can lead to inaccuracies in information extraction. The project needs to overcome these challenges to extract detailed and accurate three-dimensional information.
+ **Incorporate temporal information into traditional 3D reconstruction models to enhance the clarity of 3D reconstructions in medical scenarios.** The project will carefully study how to integrate temporal information into 3D reconstruction models, which is an innovative approach when applied to medical microscope surgical scenes. Therefore, effectively utilizing the temporal information of medical microscope surgical scenes to construct a four-dimensional reconstruction model will be a key challenge to address in this project.
+ **Accelerate model rendering speed** and reduce the time and cost of 3D model construction. Existing 3D rendering speeds are generally slow, so the project plans to optimize the rendering models for 3D reconstruction to improve rendering speed. This is the key issue the project aims to address.

# Contributors
+ [Bingwen Dong](https://github.com/SheepDoctor)
+ [Gan Lau](https://github.com/GanLiuuuu)
+ [Haotian Ding](https://github.com/SustechSKY)
  
