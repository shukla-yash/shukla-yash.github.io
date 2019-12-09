---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Ship Detection and Segmentation from Satellite Imagery
------
This study aims at segmenting instances of ships from an aerial image. Till date, no metric exists which aims at segmenting ships from aerial imagery. My approach to the problem involves cascading U-Nets for image segmentation, which is based on the idea of iterative refinement. A typical U-Net architecture consists of a convolutional neural network which acts like a decoder followed by an up-sampling deconvolutional network acting like an encoder to segment our object in question, ships.

Project team members: Yash Shukla, Bryan Inacio Rathos

Sample results from the study are displayed below.

<p align="center">
  <img src="https://shukla-yash.github.io/images/DL_project.png?raw=true" alt="Photo" style="width: 450px;"/> 
</p>

TurtleBot Trajectory Generation and Tracking
------
We present the implementation of one dimensional and two dimensional adaptive cruise control which follows a given desired trajectory using control lyapunov functions while satisfying constraints specified by a control barrier function to avoid running into obstacles. The Lyapunov function is treated as a soft constraint while the barrier function defines hard constraints for the robot, both of which are satisfied simultaneously using quadratic programming. The controller has been implemented on a turtlebot using Vicon system for feedback.

Project team members: Yash Shukla, Shubham Jain

The system architecture is displayed below.

<p align="center">
  <img src="https://shukla-yash.github.io/images/Controls_project.png?raw=true" alt="Photo" style="width: 650px;"/> 
</p>

A real-time implementation of the algorithm in 1D is shown below.

{% include youtube.html id="2nAtnv_QI_E" %}
___
A real-time implementation of the algorithm in 2D is shown below.

{% include youtube2.html id="vJgotA4i88Q" %}
