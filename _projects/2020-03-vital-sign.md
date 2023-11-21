---
title: "Respiratory Pattern Monitoring with RF Near-Field Coherent Sensing (NCS)"
excerpt: "This project implements novel high resolution Radio-Frequency (RF) imaging in indoor environment to monitor untagged people or objects."
permalink: /projects/vital_sign
collection: projects
---
#### Cornell University, Graduate Research Assistant
*2016-2020*

This project implemented a low-cost wearable RF sensor for monitoring heartbeat and respiratory patterns and detect central and obstructive sleep apneas.

**Project details and code can be found here: [RF Vital Sensing](https://psharma15.github.io/RF-Vital-Sensing/)**

  * Developed a real-time over-clothing cardiopulmonary sensor using a software-defined radio to collect detailed respiratory and heartbeat waveforms. 
  * Designed and implemented a testing protocol to perform a human study (N = 30) on simulated breathing disorders and apnea.
  * Implemented a nearly tuning-free peak-detection algorithm to identify respiratory disorder with a broad frequency range of 2-40 breaths per minute (BPM), which achieved a high rate accuracy of 94.8% (RMSE: 2.9 BPM) and respiratory volume accuracy of 77.5% (RMSE: 0.11 L) under simulated deep, fast and central sleep apnea conditions.
  * Designed a semi-supervised support-vector machine (SVM) outlier classification algorithm to detect motion artifacts with an accuracy of 91%.
  * Designed and implemented a bed-integrated sensor for sleep apnea detection in collaboration with **Cornell Weill Medical Sleep Center**. The sensor is invisible to the user with improved antenna design and placement to measure separate thorax and abdomen motion.
  * Programmed an attention test protocol on PsyToolkit for a large-scale human study to evaluate stress/attention using both respiratory and heartbeat characteristics from the NCS sensor.
