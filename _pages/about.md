---
permalink: /
title: "About Me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% include base_path %}

I obtained the PhD degree from Huazhong University of Science and Technology (HUST) in 2019, Majors in Computer Architecture, advised by Prof. Dan Feng. My research interests include Cloud Storage Systems and Big Data Processing Systems. I have published papers on performance optimization of such systems in major conferences and journals, including ICDCS, ICPP, JPDC, TCC, etc.

<!-- My CV is available in PDF format here (last updated on April 2017). -->

Education
======
* B.S. in School of Computer Science and Technology, Huazhong University of Science and Technology, 2012
* Ph.D. in Wuhan National Laboratory for Optoelectronics, Huazhong University of Science and Technology, 2019
  
Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

<!-- Projects
======
  <ul>{% for post in site.projects reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul> -->
  
<!-- Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul> -->
  
<!-- Service and leadership
======
* Currently signed in to 43 different slack teams -->
