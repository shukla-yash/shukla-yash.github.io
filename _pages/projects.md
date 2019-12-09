---
layout: archive
title: "Curriculum Vitae"
permalink: /projects/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Ship Detection and Segmentation from Satellite Imagery
=====
This study aims at segmenting instances of ships from an aerial image. Till date, no metric exists which aims at segmenting ships from aerial imagery. My approach to the problem involves cascading U-Nets for image segmentation, which is based on the idea of iterative refinement. A typical U-Net architecture consists of a convolutional neural network which acts like a decoder followed by an up-sampling deconvolutional network acting like an encoder to segment our object in question, ships.

Sample results from the study are displayed below

<p align="center">
  <img src="https://shukla-yash.github.io/images/DL_project.png?raw=true" alt="Photo" style="width: 450px;"/> 
</p>
