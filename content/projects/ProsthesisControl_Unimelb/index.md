---
title: "Data-driven Upper-limb Prosthesis Control and Validation"
date: 2024-08-10
description: "Research Project"
summary: "Developed machine learning and control algorithms for human intention detection and prosthesis control with validation using VR and robotic prototypes."
tags: ["EMG", "Motion", "VR (Unity)","SAMD21", "Intention Detection","Machine Learning"]
showDate: false
math: true
---
{{< katex >}}

## Uncertainty-aware Prosthesis Control based on Bayesian Learning
**Minimised undesired prosthesis movements caused by environmental uncertainties. Achieved a 30% reduction in task completion time compared with conventional methods (statistically significant).**

* Developed the decision-making system involving biosignal processing (**EMG** and **joint kinematics**), motion control, and machine learning.

* Built a dedicated experimental platform using **Unity (C#)** for VR simulation and data logging at up to **2 kHz**, **ESP32** for embedded sensor data acquisition and transmission firmware, and **Python** for online decision-making.

* Published in IEEE Transactions on Neural Systems and Rehabilitation Engineering (IEEE TNSRE). [[Paper](https://ieeexplore.ieee.org/document/10654345)] [[VR Code](https://github.com/UniMelbHumanRoboticsLab/VRProEP)] [[Dataset](https://doi.org/10.26188/25592115)]


{{< youtubeLite id="YGia46q7cTQ" label="UA-DPC demo" >}}

****
## Real-time Optimisation & Personalisation using Extremum Seeking Control
**Enables real-time adjustment of controller parameters for optimal performance. Reduced compensatory movements of trunk and shoulder (statistically significant).**


* Implemented Extremum Seeking Control and motion data acquisition firmware on **SAMD21** and **ESP32** microcontrollers using the **Bosch BNO055** sensor on FreeRTOS and bare-metal platforms with **DMA**, **I2C**, **SPI**, **ADC**, and **BLE** communication interfaces.
* Designed and manufactured the mechatronic prototype using 3D printing and laser cutting.

* Collaborated with colleagues at [Human Robotics Lab](https://blogs.unimelb.edu.au/human-robotics/). Published in IEEE Robotics and Automation Letter (IEEE RA-L). [[Paper](https://www.researchgate.net/publication/339675253_Exploiting_Inherent_Human_Motor_Behaviour_in_the_Online_Personalisation_of_Human-Prosthetic_Interfaces)] [[Dataset](https://github.com/Rigaro/CompensationInSynergisticProsthesisData2020)]

{{< youtubeLite id="otWtK7Y6WT4" label="personalisation demo" >}}


****
## Process-mining-based Framework for Human Intention Detection
**Developed a reasoning framework for human intention detection leveraging process-mining techniques and Petri nets.**


* Example: A Petri net is extracted from EMG and motion data of a human subject reaching a single target, with actions \(e_i\) connected through state nodes (circles). The grey actions represent a specific type of movement event starting from the filled circle.


![Extracted Petri net from EMG and motion data](pertinet.png)

* Collaborated with colleagues at [Process Science and Technology Research Group](https://cis.unimelb.edu.au/research/information-systems/process-science-and-technology) and [Human Robotics Lab](https://blogs.unimelb.edu.au/human-robotics/). Published in Information Systems and ICPM. [[Paper](https://doi.org/10.1016/j.is.2025.102540)] [[Code](https://doi.org/10.26188/25487290)]

