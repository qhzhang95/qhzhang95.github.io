---
layout: archive
title: "Qihang Zhang's resume"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
------
* **2018 - 2023** &ensp; _Ph.D. in EECS_, Massachusetts Institute of Technology
  * Advisor: George Barbastathis
  
* **2014 - 2018** &ensp; _B.S. in Physics_, Tshinghua University
  * Advisor: Yulin Chen & Lexian Yang

Work experience
------
* **2025 - present** &ensp; Research Assistant Professor, The Chinese University of Hong Kong
* **2023 - 2025** &ensp; Postdoctoral Fellow, Tsinghua University

Main research interests
------
* The statistical mechanism of optical scattering phenomena, including their wavelength, polarization, spatial frequency distribution and quantum properties;
* AI + Physics algorithm for optical sensing and imaging inverse problems;
* Advanced optical systems for biomedical imaging, nano-metrology and manufacturing inspection.


Publications
------
  <ol>{% for post in site.publications reversed %}
    {% if post.category == 'manuscripts' %}
    {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %}</ol>

Patents
------
  <ol>{% for post in site.publications reversed %}
    {% if post.category == 'patents' %}
    {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %}</ol>

Talks
------
  <ol>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ol>
  
Teaching
------
  <ol>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ol>

Service and leadership
------
* Journal reviewer of Physical Review Letters, Photonics Research, Physical Review E, Optics Express, Physical Review Applied, Journal of the Optical Society of America A, and Advanced Materials.

Honors and awards
------
* Young Scientists Fund, National Natural Science Foundation of China (2024)
* Shuimu Tsinghua Scholar, Tsinghua University (2024)
* Chi-Sun Yeh Prize, Tsinghua University (2018)
  (Top undergraduate honor in physics department)
* Outstanding Graduates of Tsinghua University (2018)
* National Scholarship (2017)
* Future Scholar Project (2017)
* Golden Prize (Nationwide rank 8) in Chinese Physics Olympiad (CPhO) 全国中学生物理竞赛 (2013)
* Best Theory Prize in Chinese Physics Olympiad (CPhO) 全国中学生物理竞赛 (2013)

