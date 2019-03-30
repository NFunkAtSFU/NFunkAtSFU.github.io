---
layout: post
title: Watchface Progress
date: 2019-03-24 16:34:12 -0700
categories: c, pkjs
permalink: blog/watchface-progress.html
---

I finally finished working through the tutorials at [https://developer.rebble.io/developer.pebble.com/tutorials/watchface-tutorial/part1/index.html]. It was tough to do debugging with these. Sometimes the c files would compile, and sometimes they wouldn't. Mostly this came down to simple typos which caused syntax errors. In some cases, I had to rearrange the order of the functions to make it work. At this point, I have a watchface that shows the day spelled out, the time in 12hr format, the month spelled out and the number of the date, along with a weather reading (temperature and description), and a battery bar underneath. 

For future work, I may try to display some graphics (clouds, sun) for the descriptor and make the temperature number a bit larger. I have found some interesting watchfaces that were inspiring, such as [https://github.com/freakified/TimeStylePebble] and [http://clintkprojects.blogspot.com/2014/11/pebble-watchface.html]. I'm happy with the appearance of my own design, but maybe I'll think about a calendar view or heart rate info in ongoing iterations. 