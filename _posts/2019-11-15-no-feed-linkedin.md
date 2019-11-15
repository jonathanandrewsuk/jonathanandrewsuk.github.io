---
featured_image: /images/big-tile.png
date: '2019-11-15 09:59 -0500'
published: true
title: No Feed LinkedIn
description: Removing the LinkedIn newsfeed with a chrome extension
---
## A simple chrome extension to boost productivity 

I challenged myself to make something small and useful, I put a strict timebox around the work of 3 Hours.

Producing something new in a tight timeframe was an exercise in scoping. My original thoughts for the chrome extension were more feature rich, with multi-site and a settings panel built in react. 

In the end it's just a few lines of CSS that load when you visit Linkedin. 

![no-feed-screenshot]({{site.baseurl}}/images/ne-feedas.png)

It works but is reliant on the div classes that contain the feed elements, so when LinkedIn have a re-design it's going to stop working. I plan to upgrade the extension with some logic to guess which div contains the feed element.

