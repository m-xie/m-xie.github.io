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
* A.B. in Chemistry and Physics, _summa cum laude_, Harvard College, 2020
* A.M. in Statistics, Harvard University, 2020
* M.D./Ph.D. Johns Hopkins University School of Medicine (current)

Research experience
======
* 2017-2020: Undergraduate Research Assistant
  * Department of Chemistry and Chemical Biology, Harvard University
  * Supervisor: Professor Adam E. Cohen


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
 
