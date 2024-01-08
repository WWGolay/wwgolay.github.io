---
title: "Robotic Telescopes"
permalink: /research/robotic-telescopes/
date: 2024-01-08
excerpt: "One of the largest inconveniences about optical astronomy is that you can only observe during the night. To alleviate this issue..."
header:
    teaser: /images/robotic-telescopes.png
    image: /images/robotic-telescopes.png
    image_description: "The _Robert L. Mutel Telescope_ is located at [Winer Observatory](http://www.winer.org/) in Sonoita, Arizona. _image credit: [MACRO Consortium](https://macroconsortium.org/)_"
    caption: "The _Robert L. Mutel Telescope_ is located at [Winer Observatory](http://www.winer.org/) in Sonoita, Arizona. _image credit: [MACRO Consortium](https://macroconsortium.org/)_"
---

One of the largest inconveniences about optical astronomy is that you can only observe during the night. To alleviate this issue, many observatories use automated software to control their hardware and execute a pre-configured schedule so an operator does not have to stay up all night. However, the related hardware, control drivers, and interfaces have historically been custom and one-off for each observatory. This means that robotic operation was only possible for an observatory if someone was able to write the software themselves, which is a significant barrier to achieving a completely automated system for small observatories typically ran by individual universities or amateur astronomers.

In recent years, the [ASCOM Standard](https://ascom-standards.org/) has been developed to provide a common interface for controlling astronomical hardware. The [Macalester-Augustana-Coe Robotic Observatory (MACRO) Consortium](https://macroconsortium.org/) and myself have developed a pure-Python package for robotic control of small telescopes called [pyscope](https://pyscope.readthedocs.io/) which natively supports the ASCOM Standard and provides a simple framework for controlling custom hardware. Most importantly, it includes the [telrun module](https://pyscope.readthedocs.io/en/latest/api/pyscope.telrun.html) which includes tools for scheduling observations and executing them automatically.
