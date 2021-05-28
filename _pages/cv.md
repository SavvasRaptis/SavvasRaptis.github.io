---
layout: archive
title: "CV / Resume"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
  - /bio
---

{% include base_path %}

Links (PDF/Download)
======
[Short CV](http://savvasraptis.github.io/files/cv/ShortCV.pdf)

Education
======
* Diploma in Physics (4-year), National and Kapodistrian University of Athens,, 2016
* Master in Astronomy & Astrophysics (2-year), KU Leuven, 2018
* Doctorate in Space & Plasma Physics (4-year), KTH, Royal Institute of Technology, 2022 (expected)

Work experience
======
* 2019 - now : Lecturer & Teaching Assistant
  * KTH, Royal Institute of Technology
  * Courses included: Electric Circuits, LaTeX, Electromagnetism & Space Physics

* 2018 - now : PhD Researcher
  * KTH, Royal Institute of Technology
  * Research on space & plasma physics, including data analysis, simulations and machine learning

Skills
======
* Programming
  * Python
  * Matlab
  * C++

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
