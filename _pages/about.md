---
permalink: /
title: "About"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
  
---

I'm a fifth year Phd Student at School of Electrical and Computer Engineering, Cornell University, advised by [Prof. Edwin Kan](https://kan.ece.cornell.edu/). My current research projects are on RF sensor systems for indoor people tracking and cardiopulmonary monitoring, focusing on RF system design and signal processing. *I'm currently looking for work opportunities in the field of data analysis, algorithm development, biomedical electronics and wireless system applications.*

Link to my [**CV**](https://github.com/psharma15/psharma15.github.io/blob/master/files/Pragya_Sharma_CV.pdf).

Publications
=====
  * **P. Sharma**, G. Xu, D. L. Hysell and E. C. Kan, “Multistatic 3D Indoor RF Imaging With Sparsity-Based Reconstruction,” 2020. _(Under Submission)_

  * **P. Sharma**, J. Zhou, X. Hui and E. C. Kan, “Long-Term Continuous Cardiopulmonary Monitoring Using Wearable RF Sensor,” 2020. _(Under Submission)_

  * G. Xu, **P. Sharma**, X. Hui and E. C. Kan, “3D Device-Free Object Locating Using Passive Radio-Frequency Identification,” 2020. _(Under Submission)_

  * **P. Sharma**, X. Hui and E. C. Kan, “A Wearable RF Sensor for Monitoring Respiratory Patterns,” at _IEEE Engineering in Medicine and Biology Society Conference (EMBC),_ Berlin, Germany, July 23-27, 2019, pp. 1217-1223.

  * D. L. Hysell, **P. Sharma**, M. Urco and M. A. Milla, “Aperture-Synthesis Radar Imaging With Compressive Sensing for Ionospheric Research,” in _Radio Science_, vol. 54, pp. 503– 516 , 2019.

  * X. Hui, **P. Sharma** and E. C. Kan, “Microwave Stethoscope for Heart Sound by Near-Field Coherent Sensing,” at _IEEE MTT-S International Microwave Symposium (IMS)_ Boston, MA, June 2 - 7, 2019.

  * **P. Sharma** and E. C. Kan, “Sleep Scoring With a UHF RFID Tag by Near Field Coherent Sensing,” at _IEEE MTT-S International Microwave Symposium (IMS)_, Philadelphia, PA, June 10 - 15, 2018, pp. 1419-1422.

Projects
=====
### [Respiratory Pattern Monitoring with RF Near-Field Coherent Sensing (NCS) Cornell University](https://psharma15.github.io/RF-Vital-Sensing/)
##### Prof. Edwin Kan (August 2016 - Present)
  * Developed a real-time over-clothing cardiopulmonary sensor by a software-defined radio to collect detailed respiratory and heartbeat waveforms.
  * Designed and implemented a testing protocol to perform human study (N = 30) on simulated breathing disorders and apnea.
  * Implemented a nearly tuning-free peak-detection algorithm to identify respiratory disorder with broad frequency range of 2-40 breaths per minute (BPM), which achieved high rate accuracy of 94.8% (RMSE: 2.9 BPM) and respiratory volume accuracy of 77.5% (RMSE: 0.11 L) under simulated deep, fast and central sleep apnea conditions.
  * Designed a semi-supervised support-vector machine (SVM) outlier-classification algorithm to detect motion artifacts with an accuracy of 91%.
  * Designed and implemented a bed-integrated sensor for sleep apnea detection in collaboration with Cornell Weill medical sleep center. The sensor is invisible to the user with improved antenna design and placement to measure separate thorax and abdomen motion.
  * Programmed an attention test protocol on PsyToolkit for a large-scale human study to evaluate stress/attention using both respiratory and heartbeat characteristics from the NCS sensor.
  
### Indoor Imaging from RFID Tag Backscatter for Real-Time People Tracking Cornell University
##### Profs Edwin Kan and David Hysell (January 2016 - Present)
  * Implemented novel sparsity-based OMP and FISTA reconstruction algorithms for high resolution RF imaging, using untagged-object backscattered phase from ambient low-cost passive UHF RFID tags.
  * Developed simulation study in CST Microwave Studio to compare relative tag-receiver placement and algorithm performance.
  * Designed a noise-cancelling calibration algorithm to mitigate backscattered phase offsets from direct tag-to-receiver LOS, background object multipath, and receiver cables and circuits introduced phase for improved size and location estimation.
  * Developed ensemble algorithms to improve the performance and reduce parameter sensitivity for inverse methods with limited bandwidth
and spatial diversity.
  * Implemented convex optimization and level-set approaches to extract object shape and size from the pixel reflectivity of imaging domain.
  * Developed an optimal frequency selection algorithm for a broad bandwidth, multi-frequency setup to generate improved Fourier-reconstructed image based on improved sampling in the K-space.
  * Tested super-resolution imaging based Capon and maximum entropy algorithms, which provided improved performance over matchedfiltering for shape estimation with increased computational and time complexity.
  
### Accuracy and Resources Trade-off in Machine Learning Algorithms Cornell University
##### Course: CS 6780 Advanced Machine Learning (January - May 2019)
  * Developed approximation techniques to tackle constrained-resource issues with large training data and limited CPU, memory and energy
availability, specifically in mobile devices.
  * Studied accuracy vs resource trade-off with different approximation techniques at both training and inference in machine learning algorithms including regression, neural networks and SVM.
  
### Online Trainable Near-Field Communication (NFC) Reader Maxim Integrated
##### Internship: Harry Huang, Micros, Security & Software Business Unit (May - August 2017)
  * Programmed an NFC reader model including analog frontend and digital baseband processing in Python. Implemented new modulation protocols on output of the existing hardware to predict future challenges.
  * Developed intelligent multi-class classification algorithm using a simple neural network architecture to perform digital data demodulation, which achieved low test error of 1% for optimal conditions, and 11% with low coupling efficiency and high noise.
  * Implemented a real-time trainable setup for testing the experimental data from the reader, resulting in low test error of < 2%.
  
### Low-Voltage Arc Detection and Sensor Placement IIT Kharagpur
##### Prof. Aurobinda Routray (May 2014 - April 2015)
  * Developed an algorithm for low-voltage (230 V, 50 Hz) arc characterization and classification from other spikes using k-means clustering of PSD spectral distance measurements, achieving high accuracy > 96%.
  * Developed an algorithm to estimate optimal sensor number and location for arc detection using bipartite graph approach with high accuracy, which achieved cost reduction by 24.75% in smaller electrical networks.
