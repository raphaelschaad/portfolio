---
title: FLAnimatedImage
category: Experience
order: 3
tags: [Engineering, Open Source]
years: 2013–present
tile: tile400w@2x.jpg
links:
  - "[Article “How Flipboard Plays Animated GIFs on iOS” by Raphael Schaad](http://engineering.flipboard.com/2014/05/animated-gif/)"
  - "[FLAnimatedImage on GitHub by Raphael Schaad](https://github.com/Flipboard/FLAnimatedImage)"
  - "[Engadget: Flipboard iOS app update introduces animated GIF support](http://www.engadget.com/2013/08/14/flipboard-ios-app-update-gif-support/)"
  - "[TechCrunch: Flipboard Updates iOS App With GIF Support](http://techcrunch.com/2013/08/14/flipboard-updates-ios-app-with-gif-support/)"
  - "[The Verge: Flipboard update adds animated GIF support, surfaces better stories](http://www.theverge.com/2013/8/14/4621506/flipboard-update-animated-gif-support-leading-news-stories)"
---
***FLAnimatedImage* is a performant iOS animated GIF engine that I built for [Flipboard](flipboard)).** It became the most popular [open source iOS animated GIF engine on GitHub](https://github.com/Flipboard/FLAnimatedImage), used by many of the top downloaded apps in the *Apple App Store*.

Accompanying the release of the open source project and to describe the many requirements, surprising challenges, and final solution, **I wrote [an article on “How Flipboard Plays Animated GIFs on iOS”](http://engineering.flipboard.com/2014/05/animated-gif/).**

Excerpt:

*Flipboard has always sought to “cook the raw web” and transform it into something that has the design elegance of a magazine. We consider many details – from the typography of articles, to the layout of photographs – to remain as faithful to the nature of content as possible.

When it came to animated GIFs, we knew we wanted them to play automatically in our app. Auto-play is one of the chief appeals of animated GIFs. However, many applications on iOS render animated GIFs as stills – an unfortunate result of the complexity of playing multiple GIFs simultaneously, and in real time, on a mobile device.

One would think that such an ancient image format would be supported out of the box for developers on modern iOS devices. But not even all of Apple’s own apps play them. When viewed with the mobile browser, the system often slows to a crawl. It’s challenging to keep the memory footprint and CPU usage low while maintaining fidelity to the playback timings …*

[Full technical article with illustrations](http://engineering.flipboard.com/2014/05/animated-gif/)

![FLAnimatedImage Flipboard](images/flanimatedimage/flanimatedimage-flipboard.gif)

—
<ul>
{% for link in page.links %}
  <li>{{ link | markdownify | remove: "<p>" | remove: "</p>" }}</li>
{% endfor %}
</ul>
