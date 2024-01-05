---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

A complete list of publications can be found on [ADS](https://ui.adsabs.harvard.edu/public-libraries/cbvuiG8RSn2nVfQr9l3Osg).

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
