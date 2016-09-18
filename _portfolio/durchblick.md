---
title: Durchblick
category: Education
order: 2
tags: [Research]
years: 2010
tile: tile400w@2x.jpg
links:
  - "[Computer Perception and Virtual Reality Lab](http://www.cpvrlab.ti.bfh.ch/)"
---
*Durchblick* is a virtual reality tag cloud with face recognition. The idea is to augment reality in real time by showing personalized information around a person’s head such as name, interests, or links to social media profiles. The vision is *“human’s face as a digital business card.”* The German project name translates to “to be in the know” – *Durch* means through and *Blick* means gaze.

![Durchblick Poster](images/durchblick/durchblick-poster.jpg)

Raphael Schaad, Bern University of Applied Sciences Engineering and Information Technology (BFH-TI)
Advisor: Prof. Urs Künzler, Computer Perception and Virtual Reality Lab, BFH-TI
Presentation & Exhibition: June 18 2010 at BFH in Biel, Switzerland

—
<ul>
{% for link in page.links %}
  <li>{{ link | markdownify | remove: "<p>" | remove: "</p>" }}</li>
{% endfor %}
</ul>
