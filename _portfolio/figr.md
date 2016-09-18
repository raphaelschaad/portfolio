---
title: Figr
category: Advising & Speaking
order: 1
tags: [Advising, Prototyping]
years: 2012–2014
tile: tile400w@2x.jpg
links:
  - "[Collectively Assembled](http://www.collectivelyassembled.com/)"
  - "[Figr](http://figr.com/)"
---
*“There are not more than five musical notes, yet the combinations of these five give rise to more melodies than can ever be heard.”*
—Sun Tzu

![Interactions Paper Sketches](images/figr/interactions-paper-sketches.jpg)

Fascinated by the endless possibilities a clever combination mechanism can give to a limited set (think music, flavor, color), I explored applying this concept to images. **I prototyped interactions that allow remixing photographs with swipe gestures on a touch screen.** Double-tapping an area toggles it to the device’s live camera feed to capture new scenes and incorporate them into the library. Shaking the device animates to a random constellation.

My fluency in iOS technologies (Objective-C, Cocoa Touch) allowed for rapid prototyping of native gestures and image manipulations. For the capturing capabilities, initially the standard camera capturing interface was used, which is presented modally and resulted in a poor experience. Using lower-level frameworks (AVFoundation, CoreAnimation) allowed for a performant in-line displaying and capturing of the camera’s live-feed.

**Based on the concepts of my prototypes the product Figr was built** – a beautiful way to consume and create fashion on a mobile device.

**I advised Collectively Assembled** – the newly formed team behind Figr –, supported their engineering, and helped with the launch of the product. Figr was featured prominently by Apple in the App Store.

![Remix Overview](images/figr/remix-overview.jpg)

![Figr Devices](images/figr/figr-devices.jpg)

![App Store Featuring](images/figr/app-store-featuring.jpg)

—
<ul>
{% for link in page.links %}
  <li>{{ link | markdownify | remove: "<p>" | remove: "</p>" }}</li>
{% endfor %}
</ul>
