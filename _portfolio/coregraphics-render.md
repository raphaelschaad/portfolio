---
title: CoreGraphics Render
category: Projects
order: 7
tags: [Art, Programming, Open Source]
years: 2010
tile: tile400w@2x.jpg
links:
  - "[CoreGraphicsInstagramArtwork on GitHub](https://github.com/raphaelschaad/CoreGraphicsInstagramArtwork/)"
---
I was intrigued by a challenge I came across: *“Single drawRect function for a single 400x400 UIView that does something magical”*. I believe constraints are powerful and added a few more (excerpt from code):

    // Conditions:
    // - no pixel graphic ressources
    // - no external code besides SDK
    …
    // - finish under 4h
    // Let's start: my goal is to approximate the Instagram iTunes Artwork.

700 lines of *CoreGraphics* code (a layer on top of *OpenGL*) later the program drew the Instagram logo. It features an **implementation of multiplicative monochrome normal distributed saturated noise, usage of blending modes, detailed gradients and shading, smoothing radial gradients through clipping, and bezier paths with arcs for reflections.** Isn’t it quite astonishing how a few thousand text instructions to a computer, carefully orchestrated, can create something that is instantly recognized by most people? The program ends with:

    // Conclusions:
    // - I reached the goal within the conditions and like the result, especially rendered on the device.
    // - At some points I tried to use another technique than already used (e.g. transform an existing shape).
    …
    // - I like my quick implementation of multiplicative monochrome normal distributed saturated noise for this (formula from Wikipedia).
    // - Edges of curves are rendered pretty choppy, a trick I found to smooth those is clipping the graphics context along the edge.

![Result Code](images/coregraphics-render/result-code.jpg)

—
<ul>
{% for link in page.links %}
  <li>{{ link | markdownify | remove: "<p>" | remove: "</p>" }}</li>
{% endfor %}
</ul>
