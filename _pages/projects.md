---
layout: archive
title: "Showcase"
permalink: /projects/
author_profile: true
---

{% include base_path %}

Here is where I will be posting the latest updates on my projects.

| Drones   | Nano-Satellites | Extracurricular |
|:--------:|:--------------:|:---------------:|
|          |                 |                 |

Links
==========
1. Lorem ipsum dolor sit amet
2. Consectetur adipiscing elit
3. Integer molestie lorem at massa
4. Facilisis in pretium nisl aliquet
5. Nulla volutpat aliquam velit
6. Faucibus porta lacus fringilla vel
7. Aenean sit amet erat nunc
8. Eget porttitor lorem

Interests
=====================
Space exploration and development, software development, aviation, aerospace, defense, space systems, satellites, nanosatellites, CubeSats, global positioning systems (GPS), control systems, system design, telecommunications, 3D modeling and scanning, unmanned aerial vehicles, UAV, UAS, aerial video/photography, precision agriculture, telematics, geomatics, engineering, additive manufacturing and 3D printing,  smart materials, digital image processing, mobile app and web development, and entrepreneurship.

{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}
