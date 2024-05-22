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
* Ph.D. in Ecology and Evolutionary Biology, University of Toronto (2021)
* B.S. in Biology, University of Costa Rica (2013)

Work experience
======
* 2024: Research fellow - Bacterial diseases in Arctic ungulates
  * Queen's University Belfast
  * Supervisor: Eric Morgan, Ph.D.
    
* 2022: Postdoctoral fellow - Urban disease ecology
  * University of Toronto
  * Supervisor: Peter Molnar, Ph.D.

* 2023: Postdoctoral fellow - Movement and disease transmission
  * University of Tennessee
  * Supervisor: Mark Wilber, Ph.D.
    
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
* Reviewer for The American Naturalist, PLOS Computational Biology, Scientific Reports, Ecography
