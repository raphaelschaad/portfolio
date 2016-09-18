---
title: Magazine Mosaic
category: Projects
order: 3
tags: [Art, Programming]
years: 2013
tile: tile400w@2x.jpg
links:
  - "[Inside Flipboard: Welcome to the Next Generation of Flipboard](http://inside.flipboard.com/2013/03/27/welcome-to-the-next-generation-of-flipboard/)"
---
![Poster](images/magazine-mosaic/poster.jpg)

I spent most of 2012 prototyping, engineering, and tweaking all the features that resulted in [Flipboard 2.0](flipboard). To celebrate this epic release with the team, I created an art piece arranging the top 1,000 magazines created by our community after the launch night into the Flipboard logo (using Objective-C and the Python Imaging Library).

A detail of what it looks like up close: only hours after launch, people with passions around fashion, science, horses, travel, or architecture, curating more magazines than one can ever read – creating the next interesting challenge.

![Poster Detail](images/magazine-mosaic/poster-detail.jpg)

![Poster Photo](images/magazine-mosaic/poster-photo.jpg)

—
<ul>
{% for link in page.links %}
  <li>{{ link | markdownify | remove: "<p>" | remove: "</p>" }}</li>
{% endfor %}
</ul>
