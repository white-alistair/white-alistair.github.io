---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Education
* **PhD**, *Technical University of Munich*, in progress
* **MSci Physics**, *University of Cambridge*, 2015
* **BA Natural Sciences**, *University of Cambridge*, 2014

## Work Experience
* 2021-present: **Research Assistant**, *Technical University of Munich*
* 2021-present: **Guest Scientist**, *Potsdam Institute for Climate Impact Research*
* 2020-2021: **Data Scientist**, *Planetly GmbH, Berlin, Germany (acquired by OneTrust LLC)*
* 2015-2018: **Quantitative Trader**, *UBS Investment Bank, London, UK*

## Publications
<ol>{% for post in site.publications reversed %}
<li><p>{{ post.citation | markdownify | remove: '<p>' | remove: '</p>' }}<b><a href="{{ base_path }}{{ post.url }}" rel="permalink"> Read more</a></b></p></li>
{% endfor %}</ol>

## Teaching
- [Modeling and Machine Learning of Dynamical Systems in Julia](https://github.com/TUM-PIK-ESM/TUM-Dynamics-Lecture), Co-creator and Lecturer, *Technical University of Munich*, 2021-present
  
<!-- Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul> -->
  
<!-- Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul> -->
<!--   
Service and leadership
======
* Currently signed in to 43 different slack teams -->
