---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[Download paper here](http://alfredmoore.github.io/files/CV_MoXu_rob.pdf)

Education
======
* B.S. in Control Engineering, Dalian University of Technology, 2018
* M.S. in EECS, University of Michigan, 2022
<!-- * Ph.D in Version Control Theory, GitHub University, 2018 (expected) -->

Work experience
======
* Summer 2021: Intern
  * ABB 
  * Duties included: 
    * Involved in the electrical high voltage power system design of robots.
    * Control the high voltage power, achieving stable performance.
    * Established a database to record electrical components.
  <!-- * Supervisor: Professor Git -->

<!-- * Fall 2015: Research Assistant
  * Github University
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub -->
  
Skills
======
* Python
  * Numpy
  * Pytorch
  * matlibplot
  * scikit-learn
* C++
  * Eigen
  * Gtsam
  * openCV
  * ORB-SLAM3
* Matlab
  * Simulink
* Systemverilog
  * RISC-V

Research & Project
======

Lidar and Visual ORB Fusion	
------
  * ROB 530 Course Project	–In Progress
  * Utilize ORB-SLAM3 and OpenCV to detect and determine objects, and Lidar SLAM to convert 3d points cloud into a map of distinctive features from the dataset of NCLT.
  * Use ORB-SLAM3 and LiDAR-based SLAM together as a form of error checking by having each feed back into the other, and take the average of ORB and Lidar as the second methods.
  * Compare the performance of two Fusion methods with the ORB-SLAM3 and Lidar-based SLAM systems.

Network Proxy Server Management System
------	
  * Individual Project	
  * Established a management system to provide effective server nodes across the world, supported to create, update, utilize and delete the proxy nodes, based on AWS EC2.
  * Support multiple proxy protocols including Vmess, Trojan and Shadowsocks to achieve various network security requirements.
  * Disguise the proxy connections as normal http to avoid the unexpected supervision.

Research on Bearing Fault Diagnosis Method Based on Granular Model
------ 	
  * Research Assistant	
  * Used wavelet packet threshold to denoise the original signal on MATLAB
  * Applied NumPy information granulation analysis to obtain the main information on Python
  * Established Pytorch stacked convolutional self-encoder(CNNs) to extract the main information features and achieved accuracy higher than 98% and visualization with matplotlib.
  * Utilized Scikit-learn unsupervised learning K-Means to classify the feature.

Gantry Crane System Optimized on Simulated Annealing
------	
  * Course Project        	
  * Utilize Simulink in MATLAB to build the Gantry Crane physical model based on control state equations.
  * Control the system with a double closed-loop control PID method for stability.
  * Optimization on PID control system parameters with Simulated Annealing Algorithm to avoid the local optimal.

Processor Design Based on R10000 Architecture
------
  * EECS470 Course Project
  *	Development on Ubuntu, bash and SystemVerilog, group cooperation through GIT remote repository
  *	Design a R10K architecture processor with RISCV containing modules like ROB, RS, pipeline and so on
  *	Additional functions including 2-width superscalar, branch prediction, victim data cache and software debugger

Mathematical Contest in Modeling Held by COMAP
------
  * Team Leader
  *	Utilized the principal component analysis algorithm and multiple linear regression to analyze the influence of the external environment on fungi on MATLAB
  *	Applied the species competition model to simulate fungi's intraspecific competition, added climate factors and Gaussian white noise to simplify the external disturbances
  *	Completed paper and won the prize of Meritorious Winner

Circuit Design by Verilog Programming of Fpga
------
  * Course Project
  *	Utilized  Quartus II and Verilog to design a multifunctional electronic clock on the DE2 circuit board
  *	The clock was given the functions of time display, hourly chime, time calibration, alarm, etc.


<!-- Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul> -->
  
<!-- Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul> -->
  
<!-- Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul> -->
  
<!-- Service and leadership
======
* Currently signed in to 43 different slack teams -->
