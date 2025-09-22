---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<p style="text-align: center; margin-bottom: 2em;">
  <a href="/files/cv.pdf" class="btn btn--primary btn--large">
    <i class="fas fa-download"></i> Download CV (PDF)
  </a>
</p>

Education
======
* Ph.D in Multimodal Human-Machine Interaction, University of Zurich, 2024-present
* M.S. in Electrical and Sound Engineering, [Your Previous University], [Year]
* B.S. in [Your Field], [Your Previous University], [Year]

Work experience
======
* 2024-present: PhD Student
  * University of Zurich
  * Research focus: Multimodal human-machine interaction
  * Combining voice, gesture, text, and facial recognition for natural human-computer communication

* [Previous Position]: [Your Previous Role]
  * [Institution/Company]
  * Duties included: [Your responsibilities]
  * Focus: Speech processing, multimodal signal processing, AI-based solutions
  
Skills
======
* Speech Processing
  * Automatic Speech Recognition (ASR)
  * Speech Enhancement
  * Dysarthric Speech Analysis
* Multimodal Signal Processing
  * Audio-Visual Processing
  * Gesture Recognition
  * Facial Recognition
* Machine Learning & AI
  * Deep Belief Networks
  * Neural Networks
  * Pattern Recognition
* Programming
  * Python
  * [Other languages you use]
* Research Areas
  * Music Signal Processing
  * Human-Computer Interaction
  * Multimodal Data Analysis

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
