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
* PhD in Statistics, Imperial College London, 2021
* MSc in Statistics, Imperial College London, 2017 
* BSc in Mathematics, University of Santiago de Compostela, 2016

Work experience
======
* Chapman Fellow, Imperial College London, 2022-2024
* Postdoctoral researcher, ICMAT-CSIC, 2021-2022 

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
  
