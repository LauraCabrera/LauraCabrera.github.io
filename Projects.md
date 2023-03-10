---
layout: page
title: Projects
permalink: /Projects/
---

## Current projects

### In-situ inference and automatic analysis of social interactions

A lot of research is currently done regarding automatic analysis of social behavior and social interactions. To do so,  computing is generally performed offline or using servers with high computing capabilities, leveraging the extensive field of machine learning. Nonetheless, not all applications and problems have the option of accessing such powerful computing resources.

Particularly for in-situ monitoring of people during their day-to-day activities, issues such as accesibility, communication latency and privacy preservation are real concerns for the deployment of initiatives based on machine learning techniques.

This line of research aims to exploit optimization techniques in the ML algorithms to reduce computing costs (i.e. memory and computing time) without impacting significantly the performance, as well as optimization of the software and hardware of the computing devices. These will enable machine learning methods to be deployed for in-situ devices. As the first step of this research line, we are working on a project for in-situ detection of crowdeness using low-resource devices, approved and financed via grant by the [Instituto Tecnológico de Costa Rica (TEC)](https://www.tec.ac.cr/en).

## Previous projects

### ALARM project

<img style="float: right;" src="../img/NICU.jpg" width="250"/>

The ALARM (Alarm-Limiting AlgoRithm-based Monitoring) project consisted of model-based predictive monitoring for neonatal intensive care units, developed by the [e/MTIC](https://www.tue.nl/en/research/research-groups/eindhoven-medtech-innovation-center/) innitiative and in a collaboration between TU Eindhoven, the [Maxima Medical Center](https://www.mmc.nl/) (MMC) and [Philips research](https://www.philips.com/a-w/research/locations/eindhoven.html) (Eindhoven headquarters).

The project aims to develop new monitoring techniques for improved and efficient diagnosis, but also leveragin data mining approaches to reduce the high number of alarms in the intensive care environment (neonatal and adult ICU) in order to increase patient safety and reduce alarm fatigue of the staff.  Neonates infants are a particualrly vulnerable population, and improving monitoring of maturation of neonates is important to predict patient outcome.

The project was lead by Dr. Carola van Pul ([contact](https://www.tue.nl/en/research/researchers/carola-van-pul/)).

### Multimodal detection of gestures in-the-wild

<img style="float: left;" src="../img/gestures.jpg" width="250"/>

Whereas most efforts related to gestures are focus on applications for Human-Computer interaction, not much has been done about detecting gestures as an inherent part of social interactions.

This project addresses the detection of hand gestures during free-standing conversations in crowded mingle scenarios. Unlike the scenarios of the previous works in gesture detection and recognition, crowded mingle scenes have additional challenges such as cross-contamination between subjects, strong occlusions, and nonstationary backgrounds. This makes them more complex to analyze using computer vision techniques alone. 

We propose a multimodal approach using video and wearable acceleration data recorded via smart badges hung around the neck. In the video modality, we propose to treat noisy dense trajectories as bags-of-trajectories. For a given bag, we can have good trajectories corresponding to the subject, and bad trajectories due for instance to cross-contamination. However, we hypothesize that for a given class, it should be possible to learn trajectories that are discriminative while ignoring noisy trajectories. We do this by exploiting multiple instance learning via embedded instance selection as our multiple instance learning approach.

See related paper [here](https://ieeexplore.ieee.org/abstract/document/8734888/).

