---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.S. in Computer Science, Western Governors University, 2025 (expected)
* A.S. in Computer Science, Southwestern College, 2023

Work Experience
======
* **Research Assistant** @ *University of Southern California*  (June 2024 - August 2024)
  * Proposed and executed a research project investigating methods to train a Multimodal Large Language Model (LLM) to better recognize the emotions of people in images as part of USC’s GLAMOR Lab.
  * Fine-tuned the Multimodal LLM using PyTorch with an Nvidia GPU cluster, and achieved results surpassing the current State Of The Art for the EMOTIC dataset in the mean Average Precision (mAP) metric by 2%.

* **Flight Software Engineer Intern** @ *Scout Space* (June 2023 - Feb 2024)
  * Developed flight software for a satellite camera module performing Space Domain Awareness (SDA) and Rendezvous, Proximity Operations and Docking (RPOD) missions in Low Earth Orbit.
  * Improved computer vision pipeline on embedded Linux ARM processor using OpenCV to pass images to machine learning inferencer using multiprocessing, decreasing transfer time by 15x.
  * Fine-tuned a CNN Machine Learning model to detect a target satellite, as well as its rotation and translation.
  * Set up an AWS server to test the ML model’s performance with simulated imagery generated using the Blender API and internal orbital mechanics software.
  * Implemented a software patching procedure in Bash to upgrade flight software after deployment and launch.
  * Integrated camera module on-site with client satellite, and wrote technical documentation for procedures.


* **Simulation Software Engineer Intern** @ *Turion Space* (June 2022 - August 2022)
  * Developed code in Python and C++ to model the parameters of a 6U CubeSat’s Attitude, Determination, and Control System (ADCS) components in a Basilisk orbital simulator to calculate mission fuel and energy costs.
  * Programmed modules using NumPy and MatPlotLib to create graphs with the output of the CubeSat’s thruster, reaction wheels, sun sensors, and battery after running the Basilisk simulator in a Docker container.

* **Software Engineer Intern** @ *Knuckledragger Design* (Aug 2018 - Feb 2021)
  * Developed a full-stack web app to control an edge device’s motorized antenna using JavaScript for the front-end (ReactJS) and back-end (NodeJS), and Python for I2C communication with a microcontroller.
  * Served the web app from a Raspberry Pi using Nginx and PM2 to connect with the user’s internal network.
  * Programmed the microcontroller using C++ to control motors, read sensors, and communicate via SPI/I2C.
  * Provided pin schematics to the electrical team for designing the antenna’s Printed Circuit Board (PCB).
  * Wrote quality testing procedures and guided technicians during product testing for over 200 units.

Projects
======
* **Co-founder/Software Lead** @ *Caltech Rover Autonomy, Technology, and Exploration Research*  (January 2023 - Present)
  * Co-founded a student team with Caltech's American Institute of Aeronautics and Astronautics (AIAA) chapter to design and build a rover which navigates a moon-like environment for the International Rover Challenge. 
  * Developed the rover’s perception system using Robot Operating System 2 (ROS2) in Python and C++.
  * Set up a WebRTC server to transmit a camera feed from the rover to a control station for remote control.

* **Software Team Member** @ *Mechatronics Club*  (January 2015 - August 2017)
  * Programmed an Autonomous Underwater Vehicle (AUV) for the International RoboSub competition in which the AUV completed maneuvering and dexterity tasks in an underwater obstacle course, winning 1st place.
  * Integrated Computer Vision using OpenCV for the AUV to navigate the underwater obstacle course.
  * Designed ground software and GUI for controlling the AUV and debugging its Arduinos using Python.


Skills
======
* Languages
  * Python
  * C++
  * JavaScript (ReactJS, NodeJS)
* Software Engineering
  * Linux
  * Git
  * Docker
  * Jira
* AI/Machine Learning
  * PyTorch
  * Nvidia Jetson Edge Computers
* Robotics
  * Embedded Systems Software
  * ROS 2 (Robot Operating System)
  * Gazebo
* Simulation
  * Basilisk
  * Blender
  * Unity

<!-- 
Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul> 
  -->

<!--   
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
   -->
<!--    
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
   -->

Awards
======
* Amazon SURE Fellowship - June 2024
* Society of Hispanic Professional Engineers Scholar(ScholarSHPE) - July 2023
* Zed Factor Fellowship - May 2023
* NASA Community College Aerospace Scholar - January 2023
