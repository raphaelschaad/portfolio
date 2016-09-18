---
title: Aircoin
category: Projects
order: 1
tags: [Engineering, Research]
years: 2014
tile-header: tile-header640w@2x.jpg
tile: tile400w@2x.jpg
links:
  - "[Aircoin Promo Video](http://vimeo.com/raphaelschaad/aircoin)"
  - "[Aircoin Interaction Demo Video](http://vimeo.com/raphaelschaad/aircoin-demo)"
  - "[Coinbase “BitHack” Hackathon](http://bithackathon.com)"
  - "[BitHack Winners Announcement](http://blog.coinbase.com/post/80997000003/announcing-the-coinbase-bithack-winners)"
  - "[@aircoinapp on Twitter](https://twitter.com/aircoinapp)"
---
An exploration of how *co-presence* enables the quickest way to send money to a nearby person.

![Aircoin](images/aircoin/aircoin.gif)

**Fascinated by proximal and infrastructure-free networks, I explored the new iBeacon technology** (Apple’s name for Bluetooth low energy). It enables small power-efficient hardware and proximity sensing. Around 2013 most smartphones started implementing this new standard. The two 16bit numbers a beacon can advertise wasn’t enough for what I had in mind. With the latest *MultipeerConnectivity* framework on iOS **I prototyped a p2p networking mechanism for discovery of nearby devices through Wi-Fi and Bluetooth.** A key innovation was putting the required communication in the discovery-phase payload and avoid waiting for a network connection.

**Also fascinated by Bitcoins, I explored the Coinbase online wallet API** (using OAuth) and was able to build an app that allowed people to send real money (using HTTP Representational state transfer). The idea was to start with the use case of *Nearby*, through that have trusted *Friends*, and then expand to *International*. The bar set for *Aircoin* was to transfer money more quickly than sharing photos – and using Bitcoins, transactions near or far remain free!

To build a complete working prototype, I teamed up with a friend and submitted it to Coinbase’s “BitHack” competition. Coinbase judged over a hundred app entries for creative use of their API, usability, and execution. **Aircoin was awarded $5,000 (9.82511 BTC) in the BitHack competition.** (I sent my teammate’s share of BTC4.912555 within seconds using Aircoin.)

**Things I want to explore further:**
- How can proximal networks become truly infrastructure-free and have the peers own all their data (in the case of finances, how can the distributed systems prevent double-spending)?
- What use cases other than finances are powerful when built on top of such networks (social behavior, epidemiology, environment)?
- How can a product avoid all currency exchange and inter-bank fees, yet have a wide adoption and remain easy to use?

![Diagram Transfer International Paper Sketch](images/aircoin/diagram-transfer-international-paper-sketch.jpg)

<iframe src="//player.vimeo.com/video/90285603?title=0&byline=0&portrait=0&autoplay=0" width="640" height="360" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>

—
<ul>
{% for link in page.links %}
  <li>{{ link | markdownify | remove: "<p>" | remove: "</p>" }}</li>
{% endfor %}
</ul>
