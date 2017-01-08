---
layout: archive
title: "Projects"
excerpt: "Showcase of my Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}

This is where I will be keeping up to date progress reports of my projects via photos and documents.

| Unmanned Systems | Space Exploration | Extracurricular |
|:--------:|:--------------:|:---------------:|
|Anything remotely controlled, semi-autonomous, to fully autonomous robots (multirotors, helicopters, planes, planetary rovers, boats and submarines).  |  CubeSat: mechanical and electrical design, antenna design, space-segment-software design/implementation/testing/deployment/maintenance, wireless communication, thermal/vibrational/vacuum testing and reliability. | Software Dev (web/apps, games), VR/AR, cloud geospatial analytics tools​, big data, machine learning, GPS. |

![Areas of Study](/assets/images/space.jpg "Areas of Study")

### Drones

I am active in the DIY-UAS community on [DIYDRONES](http://diydrones.com/profile/menezes) and I'm always willing to provide advice/assistance as well as learn from others. I have practical experience in planning and executing aerial surveys (using UAV technology), acting as a navigator/pilot, writing approved Special Flight Operations Certificates, and developing UAV technology/platform solutions.
{: .text-justify}

![How Drones are Made](/assets/images/parts-to-drone.png "How Drones are Made")
*When I first purchased my drone, I received a large box of small intricate parts and limited instructions. I really have to thank the community for all the progress I made and problems I solved. From left to right, you can see the progression and integration of FPV goggles/camera, 3D printed parts, and my programmed controller.*

![Tethered UAV](/assets/images/tether.jpg "Tethered UAV")

*One of the final tests of my power-over-tether UAV project (Summer 2016)*

### CubeSats

I've also working on various nanosatellite (CubeSat) development projects at the Lassonde School of Engineering. The main one being the [Canadian Satellite Design Challenge Team at York University](https://www.lassat.ca). Our challenge is to design and build a 3U CubeSat from scratch using limited commercial off the shelf components by mostly designing it ourselves. The competition information [can be found here](https://www.csdcms.ca). I also played an important role in the team working towards the [QB-50 project](https://www.qb50.eu).
{: .text-justify}

![CubeSat Electrical Power System Hardware Testing](/assets/images/cubesat.jpg "CubeSat Electrical Power System Hardware Testing")
*From top left row to right: you can see the battery testing and validation process we went through for the QB50/CSDC satellite(s). We conducted vibration tests with clamps that will be used for securing the batteries to the spacecraft, cycle testing to determine the End-of-Life for the batteries, and vacuum testing (because space is a vacuum). The bottom row, shows our testing of the protection circuit using LabVIEW, testing of the solar panel's peak-power, and we also vibration tested a Beagle Bone Black because we were thinking of using it for the OnBoard-Computer.*

![Proto-type Solar Array](/assets/images/ptsolar.jpg "Proto-type Solar Array")
*Here's a glimpse of our proto-type solar array that our advisor helped us solder together.*

![Proto-type Antenna](/assets/images/ant.jpg "Proto-type Antenna")

*Here's a glimpse of our proto-type antenna. Yes its two pieces of measuring tape slapped to a PCB, and yes it transmits radio frequencies. Trust me, I didn't believe it myself.*

**Please follow CSDC@YorkU via the links on my [Contact Page > Organization](http://keithmenezes.ca/contact/) to follow and support us on our journey!**{: .text-justify}

## Featured Links

1. [The Pierre L. Morrissette Institute for Entrepreneurship Silver Prize](http://lassonde.yorku.ca/articles/lassonde-students-clean-young-space-entrepreneurs-competition)

![Here's a picture of our team](/assets/images/sedsteam.jpg)
*Here's a picture of our team: Benjamin Ghatan, myself and Yuriy Davydov*

2. [CSDC@YorkU team featured in school post](http://lassonde.yorku.ca/articles/student-club-featured-ieee-communications-magazine)
3. [Full Article Published in IEEE Communications Magazine](http://lassonde.yorku.ca/sites/default/files/IEEE-Communications-Mag-CSDCYorkU%20(2).pdf)
4. [Volunteer Work for the UAV-g-2015 conference](http://lassonde.yorku.ca/articles/drones-take-over-lassonde-during-international-geomatics-conference)

#### Tech Interests
Space exploration and development, software development, aviation, aerospace, defense, space systems, satellites, nanosatellites, CubeSats, global positioning systems (GPS), control systems, system design, telecommunications, 3D modeling and scanning, unmanned aerial vehicles, UAV, UAS, aerial video/photography, precision agriculture, telematics, geomatics, engineering, additive manufacturing and 3D printing, smart materials, digital image processing, mobile app and web development, and entrepreneurship.

{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}
