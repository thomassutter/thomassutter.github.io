---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

### [CV as PDF](/files/cv.pdf)

# Education

- Ph.D in Computer Science, Institute of Machine Learning, ETH Zurich, 2023
- M.Sc. in Information Technology and Electrical Engineering, ETH Zurich, 2014
- B.Sc. in Information Technology and Electrical Engineering, ETH Zurich, 2011

# Work experience

- 2023 - : PostDoctoral Researcher, Institute of Machine Learning, ETH Zurich
  - Development of solutions for multiomics and multimodal healthcare applications (Python, PyTorch)
  - Evaluation, Design, and Training of multimodal foundation models for the Swiss AI initiative
  - Leading projects and guiding junior PhD students
  - ETH Zurich: I lead research projects in Prof. Dr. Julia Vogt's lab at ETH Zurich (topics: multimodal learning, generative models)
- 2023: Postdoctoral Researche, UC Irvine
  - I visited Prof. Dr. Stephan Mandt and his group in the fall of 2023 for a research stay.
  - We worked on developing novel multimodal generative models
- 2018-2023 Graduate Researcher, Institute of Machine Learning, ETH Zurich
  - (Co-)Authored 20 scientific publications at top-tier ML conferences (NeurIPS, ICML, ICLR) and in medical journals
  - Design of multimodal generative models and representation learning methods
  - Development of pipelines for machine learning applications in the healthcare domain
- 2015–2018 R&D Software Engineer, Logitech
  - Developed and improved computer vision algorithms in the Consumer Video Unit
  - Developed machine learning methods from scratch, collected the data and tested the developed methods on real-world data
  - Brought various machine learning projects from the prototype to production (Python, Tensorflow, C++)
- 2014–2015 Project Collaborator, upicto
  - Worked on computer vision algorithm for estimating the visibility distance using the camera network of MeteoSwiss
  - Transformed the algorithm and the pipeline from a research project to a production algorithm (Python, R, OpenGL)
  - Logitech acquired upicto in February 2015

# Publications

  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

# Talks

  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

# Teaching

  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
