---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

A PDF of my CV is available [here](/files/CV_01-05-2024.pdf) (updated 01/05/2024).

## Education

* B.S. in Astronomy & Physics, University of Iowa, Iowa City, IA, USA
* M.S. in Astronomy & Astrophysics, Harvard University, Cambridge, MA, USA (in progress)
* Ph.D in Astronomy & Astrophysics, Harvard University, Cambridge, MA, USA (in progress)

## Publications

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

## Talks

<ul>{% for post in site.talks %}
  {% include archive-single-talk-cv.html %}
{% endfor %}</ul>

## Teaching

<ul>{% for post in site.teaching %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

<!-- ## Outreach

<ul>{% for post in site.outreach %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
-->
