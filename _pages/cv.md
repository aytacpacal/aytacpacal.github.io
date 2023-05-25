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
* B.S. in Physics, Boğaziçi University, Turkey, 2010-2015
* M.S. in Computational Science and Engineering, Boğaziçi University, Turkey, 2017-2019 
* Ph.D in Atmospheric Physics, “ML-based analysis of extreme events”, German Aerospace Center(DLR) & University of Bremen, Germany, since 03/2020


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
