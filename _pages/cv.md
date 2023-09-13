---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Work

|Position|Company Name|Year|
|-----------|-----------|----------- |
| PhD Student Researcher |German Aerospace Center(DLR), Institute of Atmospheric Physics,  Earth System Model Evaluation and Analysis | since March 2020


## Education

| Qualification | Department, University, Country | Year |
| ----------- | ----------- | ----------- |
| PhD Student | Environmental Physics, University of Bremen, Germany | since March 2020 |
| MS | Computational Science and Engineering, Boğaziçi University, Turkey | January 2017 - November 2019 |
| BS | Physics, Boğaziçi University, Turkey | September 2010 - August 2015 |


## Publications
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
## Talks
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
