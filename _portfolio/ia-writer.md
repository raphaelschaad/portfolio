---
title: iA Writer
category: Experience
order: 4
tags: [Engineering, Prototyping]
years: 2009–2010
tile-header: tile-header640w@2x.jpg
tile: tile400w@2x.jpg
links:
  - "[iA Writer Website](https://ia.net/writer)"
  - "[Writer for iPad (Sept 2010)](https://ia.net/writer/updates/writer-for-ipad)"
  - "[A. Burroughs on iA Writer (Oct 2010)](https://ia.net/writer/updates/the-pleasure-of-the-text)"
  - "[Stephen Fry on Writer (Oct 2010)](https://ia.net/writer/updates/stephen-fry-on-writer)"
---
*“Everything goes away except for the writing experience”*
—Stephen Fry, about iA Writer

<!-- This video "iA Writer Feature Walkthrough Video" (https://vimeo.com/18777877) isn't hosted on Vimeo anymore. -->
<!-- 428 is 50% of the native video height of 856, and seems reasonable. -->
<!-- Specify poster frame to show something other than just black in case we don't specify autoplay (or for mobile devices, where autoplay is off by default) -->
<video width="640" height="428" poster="videos/ia-writer/poster.jpg" controls autoplay>
  <source src="videos/ia-writer/ia-writer-for-ipad.mp4" type="video/mp4">
  Your browser does not support playing this video.
</video>

A conversation on Twitter in 2009 with the founder of Information Architects (iA) sparked a collaboration on a “Writing Machine.” I prototyped and reinvented interfaces for text entry on desktop computers, tablets, and smart phones. In 2010 we released *iA Writer*, a word processor designed to single-mindedly focus on writing. The video shows the features and interactions.

Custom interfaces and interactions were challenging to achieve on embedded devices due to hard- and software limitations, but resulted in many of the innovative features such as the text entry in *Focus Mode*, *Reading Time* indication, or the custom *Keyboard Extension*. Another big engineering effort went into the *Cloud* syncing engine that powers the writing workflow across multiple devices.

![Sync Devices](images/ia-writer/sync-devices.jpg)

*iA Writer* appeared regularly in Apple’s “Editor Choices” and “Best App of the Year” category. With over 1,000,000 copies sold, it has helped students, journalists, and bestselling authors to find more pleasure in working with text. Beyond my direct contributions, in 2011 Writer was introduced on the Mac and in 2014, Writer Pro gave birth to many of the original prototypes such as smart syntax control.

![App Store Featuring](images/ia-writer/app-store-featuring.jpg)

*iA Writer* was the first large-scale consumer product I’ve built and it added an important perspective to my previous experience in enterprise software and research projects. Furthermore, it is satisfying to use one’s own tools, creating an important feedback loop for improvements. My first writing project using *iA Writer* was [a booklet about working in Tokyo](booklet-tokyo) for my friends and family.

![Development Photos](images/ia-writer/development-photos.jpg)

—
<ul>
{% for link in page.links %}
  <li>{{ link | markdownify | remove: "<p>" | remove: "</p>" }}</li>
{% endfor %}
</ul>
