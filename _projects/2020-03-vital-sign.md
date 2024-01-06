---
title: "Respiratory Pattern Monitoring with RF Near-Field Coherent Sensing (NCS)"
excerpt: "This project implements a novel NCS-based RF sensor, tailored to monitor various respiratory patterns including sleep apnea."
permalink: /projects/vital_sign
collection: projects
---
#### Cornell University, Graduate Research Assistant
*2016-2020*

This project demonstrates a research prototype of a potentially low-cost wearable RF sensor for monitoring heartbeat and respiratory patterns and detecting central and obstructive sleep apneas.

<p align="center">
  <img width="600" src="../images/RF_setup.png?raw=true">  
  <figcaption>Subject wearing RF NCS and reference sensors. Bottom-left shows respiration waveforms from RF NCS vs BIOPAC chest belts. Bottom-right shows extracted heartbeat waveform from NCS vs ECG and estimated HR.</figcaption>
</p>

**Project details and code can be found here: [RF Vital Sensing](https://psharma15.github.io/RF-Vital-Sensing/)**

  * Designed and implemented a testing protocol to perform an **IRB approved human study (N = 30)** on simulated breathing disorders including apnea and stress/attention.
  * Developed a real-time **over-clothing cardiopulmonary sensor** using a software-defined radio to collect detailed respiratory and heartbeat waveforms. 
  * Implemented a nearly **tuning-free peak-detection algorithm** to identify respiratory disorder with a broad frequency range of **2-40 breaths per minute (BPM)**, which achieved a high rate accuracy of 94.8% (RMSE: 2.9 BPM) and respiratory volume accuracy of 77.5% (RMSE: 0.11 L) under simulated deep, fast and central sleep apnea conditions.
  * Designed a semi-supervised support-vector machine (SVM) outlier classification algorithm to **detect motion artifacts** with an accuracy of 91%.
  * Designed and implemented a bed-integrated sensor for **sleep apnea detection** in collaboration with **Cornell Weill Medical Sleep Center**. The sensor is invisible to the user with improved antenna design and placement to measure separate thorax and abdomen motion.
  * Programmed an **attention detection** test protocol (Mackworth Clock Task) on PsyToolkit for the 30-subject human study to evaluate attention/vigilance using respiratory and heartbeat characteristics from the RF-NCS sensor.
