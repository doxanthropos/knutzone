---
title: "New Site With Hugo"
date: 2020-10-03T21:58:26+02:00
draft: false
---

As I tend to do, when I have not written into one of my own little places on the internet, I had the drive to start new from scratch and luckily I had this domain lying around, waiting for me to do something with it (and being paid regularly so I keep it).

## Hugo and Anubis

The descision for the static site generator [Hugo][hugo] was based mainly on flexibility and availibility for all platforms. While I was still considering writing all the html and css myself, I found the beautiful theme [Anubis][anubis], which looked just like I would want this site to look.

One main point I like about Hugo in comparison to Jekyll is that it doesn't need me to bring the whole language stack with me. It is possible to just download the executable and use it, while with Jekyll (or Octopress, based on it), one needs not only Ruby, but also gems, bundler and other stuff that has to be managed and can get you into situations with conflicting version and depricated libraries. In this regard, Hugo seems much cleaner and simpler.

Anubis, I chose, because it provides a nice dark theme with a simple responsive layout and because it is a really lightwheight theme with no JavaScript. What I do not want is have a website that suffers from [website obesity][bloat].

## RSS

One important change from the Hugo and Anubis default was the [RSS][rss-matters]. I want it to contain all the posts, but not the pages. Of course I was not the first to have such an interest and I found a [nice article][rss] about how to customize the RSS with some general explanations and nearly exact the template line that I needed.

But I also wanted the RSS to be easily available to the interested visitor, so I added it to the navigation area in the header.html layout.

[hugo]:https://gohugo.io/
[anubis]:https://github.com/mitrichius/hugo-theme-anubis
[rss]:https://benjamincongdon.me/blog/2020/01/14/Tips-for-Customizing-Hugo-RSS-Feeds/
[action]:https://www.manning.com/books/hugo-in-action
[bloat]:https://idlewords.com/talks/website_obesity.htm
[rss-matters]:/posts/rss-matters/
