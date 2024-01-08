---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

This is a list of my first-author publications. A complete list can be found on [ADS](https://ui.adsabs.harvard.edu/public-libraries/cbvuiG8RSn2nVfQr9l3Osg).

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
