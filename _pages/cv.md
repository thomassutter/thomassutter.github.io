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
* B.Sc. in Information Technology and Electrical Engineering, ETH Zurich, 2012
* M.Sc. in Information Technology and Electrical Engineering, ETH Zurich, 2012
* Ph.D in Machine Learning, ETH Zurich, 2023


Work experience
======
* 2023 - : PostDoc
  * ETH Zurich: I lead research projects in Prof. Dr. Julia Vogt's lab at ETH Zurich (topics: multimodal learning, generative models) 
  * UC Irvine: I visited Prof. Dr. Stephan Mandt and his group in the fall of 2023 for a research stay.
* 2014-2015: R&D Software Engineer
  * upicto GmbH
  * The project was a contract by MeteoSchweiz to further improve the algorithm developed during my master thesis and productize the findings. I worked on improving the algorithm to estimate the visibility based on images, developing a rendering pipeline using openGL, programming a GUI and designing an image preprocessing pipeline to decide if an image is suitable for visibility estimation.

* 2015-2018: R&D Software Engineer
  * Logitech
  * Consumer Video Unit: I have been mainly working for Logitech’s consumer video unit on developing and improving computer vision algorithms. The work includes various subtasks in a video analytics pipeline which involves motion estimation, as well as appearance based classification and detection methods and testing the developed methods.
  

Publications
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
  

