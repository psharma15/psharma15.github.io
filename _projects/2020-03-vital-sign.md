---
title: "Noninvasive Cardiorespiratory Monitoring using Wearable RF Near-Field Coherent Sensing"
excerpt: "This project implements a novel wearable RF sensor to monitor various respiratory patterns including sleep apnea with high signal to noise ratio."
permalink: /projects/vital_sign
collection: projects
---
#### Cornell University, Graduate Research Assistant
*2016-2020*

This project developed and validated a low-cost wearable radio-frequency (RF) near-field coherent sensing (NCS) system for continuous cardiopulmonary monitoring and respiratory disorder detection.


### Problem

Continuous monitoring of respiratory and cardiac physiology traditionally relies on skin-contact sensors such as ECG leads and chest belts. These systems limit long-term comfort, are prone to motion artifacts, and are not well suited for unobtrusive or home-based monitoring.  

Non-contact RF sensing approaches showed promise but were historically limited by low signal-to-noise ratio, sensitivity to environmental motion, and limited validation in realistic clinical scenarios.

### Approach
<p align="center">
  <img width="600" src="../images/RF_setup.png?raw=true">  
  <figcaption>Subject wearing RF NCS and reference sensors. Bottom-left shows respiration waveforms from RF NCS vs BIOPAC chest belts. Bottom-right shows extracted heartbeat waveform from NCS vs ECG and estimated HR.</figcaption>
</p>
I designed and implemented a wearable near-field RF sensing platform capable of extracting detailed respiratory and heartbeat waveforms through clothing using a software-defined radio architecture.

Key components of the work included:

- Designing and executing an **IRB-approved human subject study (N = 30)** involving simulated breathing disorders, apnea events, and attention/vigilance tasks  
- Developing a real-time, over-clothing **cardiopulmonary sensing system** with high signal fidelity  
- Implementing a nearly tuning-free peak-detection algorithm for respiratory disorder identification across a broad frequency range (2–40 breaths per minute)  
- Achieving high respiratory rate accuracy (94.8%, RMSE 2.9 BPM) and respiratory volume estimation performance (RMSE 0.11 L) across irregular breathing patterns  
- Designing a semi-supervised SVM-based framework for **motion artifact detection** (91% accuracy)  
- Engineering a bed-integrated RF system for **sleep apnea detection** in collaboration with the Weill Cornell Medical Sleep Center, including optimized antenna design to separately capture thoracic and abdominal motion  
- Developing and programming an attention-detection protocol (Mackworth Clock Task) to study relationships between vigilance and cardiopulmonary dynamics  

### Impact

This work represents one of the early demonstrations of near-field RF sensing for simultaneous respiratory and cardiac monitoring with strong signal robustness and clinical validation.  

By extending evaluation beyond laboratory conditions into clinical sleep settings, this project advanced the feasibility of RF-based monitoring as a scalable, low-burden alternative to conventional contact sensors for both hospital and home health applications.

<!-- 
**Project details and code can be found here: [RF Vital Sensing](https://psharma15.github.io/RF-Vital-Sensing/)**

  * Designed and implemented a testing protocol to perform an **IRB approved human study (N = 30)** on simulated breathing disorders including apnea and stress/attention.
  * Developed a real-time **over-clothing cardiopulmonary sensor** using a software-defined radio to collect detailed respiratory and heartbeat waveforms. 
  * Implemented a nearly **tuning-free peak-detection algorithm** to identify respiratory disorder with a broad frequency range of **2-40 breaths per minute (BPM)**, which achieved a high rate accuracy of 94.8% (RMSE: 2.9 BPM) and respiratory volume accuracy of 77.5% (RMSE: 0.11 L) under simulated deep, fast and central sleep apnea conditions.
  * Designed a semi-supervised support-vector machine (SVM) outlier classification algorithm to **detect motion artifacts** with an accuracy of 91%.
  * Designed and implemented a bed-integrated sensor for **sleep apnea detection** in collaboration with **Cornell Weill Medical Sleep Center**. The sensor is invisible to the user with improved antenna design and placement to measure separate thorax and abdomen motion.
  * Programmed an **attention detection** test protocol (Mackworth Clock Task) on PsyToolkit for the 30-subject human study to evaluate attention/vigilance using respiratory and heartbeat characteristics from the RF-NCS sensor.
-->
