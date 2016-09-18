---
title: Ensō
category: Projects
order: 6
tags: [Art, Programming]
years: 2014
tile: tile400w@2x.jpg
links:
  - "[Ensō on Wikipedia](http://en.wikipedia.org/wiki/Ens%C5%8D)"
  - "[Averageness on Wikipedia](http://en.wikipedia.org/wiki/Averageness)"
---
![Ensō Quilt](images/enso/enso-quilt.jpg)

An *ensō* is a circle drawn in one fluid stroke to express a moment when the mind is free to let the body create. Because my normal mode of creation is keeping 100 things in my mind at the same time – from user intentions all the way down to debugger breakpoints –, I was fascinated by this idea. **I decided to draw 100 circles over 100 days starting in early 2014.**

I wrote a program that reformatted the images stored in the Paper.app on my iPad and laid them all out to examine them. Some were bigger, some smaller, and some were nicer than others. Next I was curious what would happen when I blended them into a single image. Could the computer create *the perfect ensō?* There is a lack of character when singular issues are averaged away – but also a certain beauty.

![Ensō Mean](images/enso/enso-mean.jpg)

![Playground](images/enso/playground.jpg)

(I also really wanted to explore Apple’s Swift language in the new Playground environment.)

—
<ul>
{% for link in page.links %}
  <li>{{ link | markdownify | remove: "<p>" | remove: "</p>" }}</li>
{% endfor %}
</ul>
