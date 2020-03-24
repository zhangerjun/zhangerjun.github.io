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
* Ph.D University of Montreal (poly), Montreal, Canada, 2018-2022
* M.E  Optical Engineering, Beijing University of Technology, China (2018)
* B.E. Photoelectric Information Engineering, Shenzhen University, China (2014)

  
Projects
======
* Neonatal diffusion MR imaging
* Models of smart windows
* Super-resolution imaging algorithms, simulation and system building
  * Master Thesis
  
Work Experience
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

 Conferences
======
  <ul>{% for post in site.talks %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
