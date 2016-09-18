---
title: ImagePlay on iPad
category: Education
order: 1
tags: [Research]
years: 2010–2011
tile: tile400w@2x.jpg
links:
  - "[BFH-TI Book](http://ti.bfh.ch/book)"
  - "[Computer Perception and Virtual Reality Lab](http://www.cpvrlab.ti.bfh.ch/)"
---
Computer Vision is a field in Computer Science that allows a computer to “see”. For my bachelors thesis I researched how tools can make these powerful yet complex technologies accessible to a broader audience. Allowing anybody to use such technologies can amplify their ideas and lead to a new generation of applications.

Practical use cases of Computer Vision include detection of tumors in medical images or improving photos taken in space. Fascinated by these applications, I majored in that field and explored new possibilities with projects such as [Durchblick](durchblick) (a virtual reality tag cloud with face recognition) or [LightDetector](lightdetector) (an algorithm that transforms light into sound for the blind). A big part of the work was studying the theory enabling these applications such as Digital Signal Processing (DSP). To aid students in understanding these concepts my advisor developed a Windows tool used in classes called *ImagePlay*.

**The goal of my thesis *ImagePlay on iPad* was to research how to bring it to new platforms where any user could directly manipulate Computer Vision processing blocks with a touch interface to prototype their own applications. An abstracted and extensible plug-in architecture allows students without any prior platform knowledge to develop and share new processes.**

The result was a publication and a new node-based visual programming environment for image processing including:
- Input processes (asset library, device camera)
- Core processes (pixel conversion and arithmetic)
- Extensible architecture to build processes (geometry, morphology, classifiers, etc.)
- Output processes (viewers, file writers)
- Saving, loading, and sharing of process grid files

![ImagePlay on iPad BFH-TI Book 2011](images/imageplay-on-ipad/imageplay-on-ipad-bfh-ti-book-2011.jpg)

Raphael Schaad, Bern University of Applied Sciences Engineering and Information Technology (BFH-TI)
Advisor: Prof. Roger Cattin, Computer Perception and Virtual Reality Lab, BFH-TI
Industry Expert: Peter Matti, Pronik AG

Presentation & Exhibition: Feb. 11-12 2011 at BFH in Bern, Switzerland
Publication: Raphael Schaad, ImagePlay on iPad, BFH-TI Book, 2011

—
<ul>
{% for link in page.links %}
  <li>{{ link | markdownify | remove: "<p>" | remove: "</p>" }}</li>
{% endfor %}
</ul>
