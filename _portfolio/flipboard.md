---
title: Flipboard
category: Experience
order: 1
tags: [Engineering, Design, Prototyping]
years: 2011–present
tile-header: tile-header640w@2x.jpg
tile: tile400w@2x.jpg
links:
  - "[Flipboard Website](https://about.flipboard.com/) "
  - "[Flipboard Promo Video](https://www.youtube.com/watch?v=v2vpvEDS00o)"
  - "[Inside Flipboard iPhone: The Power of Flipboard in Your Pocket](http://inside.flipboard.com/2011/12/07/the-power-of-flipboard-in-your-pocket/)"
  - "[Inside Flipboard 2.0: Welcome to the Next Generation of Flipboard](http://inside.flipboard.com/2013/03/27/welcome-to-the-next-generation-of-flipboard/)"
  - "[Inside Flipboard 3.0: The New Flipboard Gets Personal with Over 30,000 Topics to Follow](http://inside.flipboard.com/2014/10/29/the-new-flipboard-gets-personal-with-over-30000-topics-to-follow/)"
  - "[Booklet about my journey to Silicon Valley](booklet-silicon-valley)"
  - "[Talk at One More Thing Conference](one-more-thing-conference)"
---
*Flipboard* is a place to discover, collect and share all the news you care about. The mobile experience combines the beauty and ease of print with the power of social media.

<iframe width="640" height="360" src="//www.youtube-nocookie.com/embed/v2vpvEDS00o?rel=0&showinfo=0" frameborder="0" allowfullscreen></iframe>

Over the past four years I have been building the world’s first social magazine to transform the media landscape as one of the key contributors to the product and its technology.

**I lead the implementation of core functionality such as user-curated magazines, forming millions of collections of deep content.**

*“Flipboard 2.0 allowed anyone to make a magazine and that has driven our growth massively.”* —John Doerr, KPCB

![Magazines](images/flipboard/magazines.jpg)

My initiatives lead to now foundational infrastructure, patented technologies, and [open source projects](flanimatedimage).

**I also designed and prototyped new features and interactions across multiple platforms,** for example to further personalize the content experience:

It is clear that a user’s experience is best when the served content is highly relevant to the individual. The more a system knows about a user, the more personalized it can become. To achieve that, it would be best to gather all the data that can’t be inferred upfront. Earlier versions of *Flipboard* and many other products approach that by asking the user initial questions. The challenge with an elaborate setup process is that the users are not yet familiar with the benefit they’ll get from the product and are likely to drop off.

The solution is to show the user the value of the product as soon as possible – in the case of *Flipboard* great content beautifully presented – and intersperse the product customization and education in an engaged user’s natural flow. The in-feed personalization introduced in *Flipboard 3.0* recommends user curated magazines and algorithmically related topics on an ongoing basis. The layering of signals from people with signals from machines complementarily increases the relevancy of the delivered content.

*Below are samples of the in-feed personalization flow (the [Flipboard Briefing](flipboard-briefing) project describes the process I use):*

![Sketches](images/flipboard/sketches.jpg)

![Designs](images/flipboard/designs.jpg)

<iframe src="//player.vimeo.com/video/116841043?title=0&byline=0&portrait=0&autoplay=0&loop=0&color=ffffff" width="320" height="566" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>

*Flipboard* won countless awards for its innovations and is featured regularly in *Apple* retail stores around the world, the *Apple App Store*, and *Google Play Store*.

![Apple Store and App Store Featurings](images/flipboard/apple-store-and-app-store-featurings.jpg)

With my previous experience and by being at *Flipboard* early on, I’ve had the opportunity to shape the product significantly and have helped the world-class team grow by almost 10X and the user base by over 100X. The many invaluable experiences I gained in technological innovation and product design are unique to this startup environment. The belief that great stories move the world forward is fueling the journey to create a place in which everybody can discover everything about their interests.

![Development Photos](images/flipboard/development-photos.jpg)

—
<ul>
{% for link in page.links %}
  <li>{{ link | markdownify | remove: "<p>" | remove: "</p>" }}</li>
{% endfor %}
</ul>
