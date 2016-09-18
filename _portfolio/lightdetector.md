---
title: LightDetector
category: Projects
order: 2
tags: [Programming, Research]
years: 2010
tile-header: tile-header640w@2x.jpg
tile: tile400w@2x.jpg
links:
  - "[LightDetector Video](http://vimeo.com/raphaelschaad/lightdetector)"
  - "[Access for All Website – Non-profit organization improving the internet for people with disabilities](http://www.access-for-all.ch/en.html)"
  - "[Computer Perception and Virtual Reality Lab](http://www.cpvrlab.ti.bfh.ch/)"
---
It is impressive how blind people compensate for their visual impairment with other senses and independently navigate modern life. Technology can further assist this sensory substitution. *LightDetector* is an iPhone App that allows blind people to “see” light. It uses the mobile phone’s camera and image processing to transform light sources into sound. The video shows two of my blind friends experiencing “vision” with *LightDetector* as they have never before.

<iframe src="//player.vimeo.com/video/116454634?title=0&byline=0&portrait=0&autoplay=0" width="640" height="480" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>

I have previously audited the accessibility of Switzerland’s biggest e-banking site E-Finance to meet new federal requirements for people with disabilities. The assistive technology back then was exclusive to desktop computers. During an encounter with two blind men at a café, I was excited to learn that the iPhone is very accessible for them through a speech interface and special touch gestures. Our friendship and my passion for building technology that augments people’s abilities gave birth to this independent research.

**I used MATLAB and [ImagePlay](imageplay-on-ipad) to design the algorithm that detects the brightness and recognizes light sources.** When implementing it for the early generation iPhone hardware, the calculations had to be optimized. Another interesting challenge was to process the live camera feed. Due to the lack of an official API, the app launched the standard camera capture interface and then continuously copied the screen’s content with a private function – a technique I found during the [Durchblick](Durchblick) project.

![LightDetector Development](images/lightdetector/lightdetector-development.jpg)

I speak about this project in [my talk at One More Thing Conference](one-more-thing-conference) to highlight the importance of using technology not only to address business gaps but to solve society’s needs.

—
<ul>
{% for link in page.links %}
  <li>{{ link | markdownify | remove: "<p>" | remove: "</p>" }}</li>
{% endfor %}
</ul>
