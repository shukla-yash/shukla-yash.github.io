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
* Master of Science in Robotics, WPI, 2020 (expected)
* Bachelor of Engineering in Mechanical Engineering, BITS Pilani, India (2018)


Skills
======
* Programming: Python, C/C++, MATLAB
* Tools:
    * Deep Learning frameworks: PyTorch, Tensorflow, Keras
    * Simulation softwares: Gazebo, OpenRave, OpenAI gym, Ansys
    * Libraries: OpenCV, Point Cloud Library, scikit-learn
    * Robotic Framework: Robot Operating System
* Courses: Deep Learning for Advanced Robot Perceptioin, Artificial Intelligence, Robot Dynamics, Robot Control


Experience
======
* Peer Learning Assistant, Physics Department, WPI (Aug '19 - Present)
  * Conduct lab sessions for PH 1110 (General Physics : Mechanics) and PH 1120 (Electricity and Magnetism)
  * Tutor Active Learning Physics Course (PH 1110). 
  * Teaching Python to Physics majors.

* MathWorks, Natick, MA (May '19 - Aug '19)
  * Formulated an innovative CV algorithm to improve accuracy of camera calibration parameters for Fisheye Cameras.
  * The Checkerboard Detection algorithm designed for Fisheye Cameras had better true positive detection even for imagesfrom     Pinhole and Stereo Cameras.
  * Achieved better checkerboard detection precision (98 %) as compared to the existing technique (83 %).
  
* Centre for Artificial Intelligence and Robotics, Bangalore, India (Jan '18 - June '18)
  * Developed a novel image processing algorithm for efficient road segmentation in unstructured environment.
  * Generated costmap in ROS using pointcloud information from Velodyne LIDAR, Stereo Camera and Ultrasonic sensor.
  * Achieved better segmentation accuracy (91 %) as compared to existing Pyramid Scene Parsing Network (79 %)
  

Projects
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
