---
title: Aare
category: Projects
order: 4
tags: [Engineering, Design]
years: 2010–present
tile: tile400w@2x.jpg
links:
  - "[BBC - Close-Up: Swimming in Berne’s fast-flowing city river](http://www.bbc.co.uk/news/world-europe-10893835)"
  - "[Federal Office for the Environment](http://www.hydrodaten.admin.ch/en/index.html#temperatur_fliessgewaesser)"
  - "[Aare on the App Store](http://itunes.apple.com/ch/app/aare/id375825664)"
  - "[Aare Facebook page](https://www.facebook.com/aareapp)"
  - "[@aareapp on Twitter](https://twitter.com/aareapp)"
---
During hot summers, people in Switzerland flock to the river Aare to cool off. Its glacial-melt water races from the Alps, where I grew up, through Swiss cities and eventually joins bigger rivers in Germany. As I was floating down the river one day, I wondered what the water temperature and streamflow might be and decided to do something about it. **I designed and built an iPhone app that answered that question for me and over the past few years it answered that same question for other people well over a million times.**

![Aare Screens](images/aare/aare-screens.jpg)

*Aare* is a native iOS app built in Objective-C making heavy use of gestures and networking. In the first version, the deployed clients scraped and parsed the hydrologic data themselves from the web. The changing web endpoint and memory constraints of early smartphone hardware lead to complex parsing code and a slow user experience. With a new web service built in Grails, the client logic and payload could be greatly reduced, resulting in faster loading times.

The user interface features original illustrations of sites along the river where the data is measured and is designed for quick usage bursts of only a few seconds to provide its utility.

![Diagram Session Length Distribution](images/aare/diagram-session-length-distribution.jpg)

Since I added usage instrumentation in 2012, one can clearly see even from afar when it was hot in Switzerland based on peaking session counts.

![Diagram Sessions](images/aare/diagram-sessions.jpg)

*Aare* received print media coverage, praises from the mayor of Swiss capital Bern, Alexander Tschäppät, and continues to be featured by Apple in the App Store since 2010.

![Press Coverage](images/aare/press-coverage.jpg)

—
<ul>
{% for link in page.links %}
  <li>{{ link | markdownify | remove: "<p>" | remove: "</p>" }}</li>
{% endfor %}
</ul>
