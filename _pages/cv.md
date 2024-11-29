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
* M.S. in Data Science, Chinese University of Hong Kong, Shenzhen, 2023
* B.A. in Finance, Hunan University, 2021
  
Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Skills
======
* Language
  * Mandarin (Native); English (Fluent) 
* Computer skills
  * Python, SAS, Stata, Linux, Latex, R
* Databases
  * WRDS, Refinitiv Workspace, Bloomberg, CSMAR, Wind
