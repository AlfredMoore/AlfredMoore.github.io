---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[Download CV_Robotics here](http://alfredmoore.github.io/files/CV_MoXu_rob.pdf)

[Download CV_DataScience here](http://alfredmoore.github.io/files/CV_MoXu_ds.pdf)

Education
======
* B.S. in Control Engineering, Dalian University of Technology, 2018
* M.S. in EECS, University of Michigan, 2024(expected)
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
  * Gym
  * Stable-baselines 3
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

Reinforcement Learning Control of Amphibious Quadruped Robot
-----
  * Intern, I4FSI Lab, Westlake University April 2023 – Aug 2023
  * Designed and 3D-printed the swimming modules of an amphibious quadruped robot with 12 degrees of freedom, 4 flippers and a buoyancy module.
  * Established raspberry Pi 4B python environment with socket connection with PC, servos control interface on the GPIO and IMU interface on the I2C.
  * Utilized the deep reinforcement learning model, Proximal Policy Optimization(PPO) with extra tricks, to improve performance.
  * Established a customized RL environment based on Gym.Env with socket connection to the Robot.

Lidar and Visual SLAM Loosely-Coupled Fusion
-----
  * Mobile Robotics Course Project Jan 2023 - April 2023
  * Utilized ORB-SLAM3 to detect, extract and compare ORB features from images and calculated rotation and translation information with the optimization of loop closure detection.
  * Convert the 3D points cloud into rotation and translation matrix by LITAMIN2 LiDAR SLAM.
  * Loosely coupled visual and LiDAR SLAM by checking bad data and replacing it with good data.


Predicting Music Popularity Based on Extracted Instrumental Features
-----
  * Machine Learning Course Project Jan 2023 - April 2023
  * Classified Spotify songs’ popularity from pre-extracted features by machine learning algorithms, such as logistic regression, SVM, XGboosting, random forest and fully connected neural network.
  * Searched and downloaded 45000+ songs on the Google Cloud by multithreaded Python scripts and extracted Mel-spectrograms by librosa to manually extract features and establish the dataset.
  * Utilized the Transformer on Tensorflow with 500000+ parameters and ResNet CNN to classify the popularity with the extracted Mel-spectrograms but found the low correlation with spectrograms.

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
  *	Design a R10K architecture processor (simplified Intel Pentium 4 Processor) with RISCV.
  * The prosessor contains modules like ROB, RS, pipeline and so on
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
