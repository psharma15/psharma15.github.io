---
title: "CLEAR: Counting and Location Estimate using Ambient Radio signals"
excerpt: "This project implements novel high-resolution Radio-Frequency (RF) imaging in indoor environment to monitor untagged people or objects."
permalink: /projects/indoor-img
collection: projects
---
#### Cornell University, Graduate Research Assistant
*2015-2020*

This project implemented novel high-resolution Radio-Frequency (RF) imaging in the indoor environment to monitor untagged people or objects.

<p align="center">
  <img width="850" src="../images/arpae_setup_2_label.png?raw=true">
  <em align="center">ARPA-E summit occupant localization demonstration with a 1/6 scaled model The screen shows the detected locations of two figures in the model.</em>
</p>

**Project details and code can be found here: [CLEAR](https://psharma15.github.io/CLEAR/)**

* Implemented novel sparsity-based OMP and FISTA reconstruction algorithms for high-resolution RF imaging, using untagged-object backscattered phase from ambient low-cost passive UHF RFID tags.
* Developed simulation study in CST Microwave Studio to compare relative tag-receiver placement and algorithm performance.
* Designed a background-subtraction calibration algorithm with improved noise-cancellation, detecting one occupant presence with **100%** accuracy and low median error of **0.36** m in a 4 m × 4 m room.
* Developed ensemble algorithms to improve the performance and reduce parameter sensitivity for inverse methods with limited bandwidth
and spatial diversity.
* Implemented convex optimization and level-set approaches to extract object shape and size from the pixel reflectivity of the imaging domain.
* Developed an optimal frequency selection algorithm for a broad bandwidth, multi-frequency setup to generate improved Fourier-reconstructed
image based on K-space sampling.
* Tested super-resolution imaging based Capon and maximum entropy algorithms, which provided improved performance over matched filtering
for shape estimation with increased computational and time complexity.

<p align="center">
  <img src="../images/ompResultCalib42.gif?raw=true" width="800px">  
  <em align="center">Image shows true and detected occupant loacation using 3D image reconstruction in a small room.</em>
</p>

