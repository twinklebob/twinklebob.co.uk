---
layout: post
title: Almost paper free (part 2)
date: 2016-06-08 09:25:19.000000000 +01:00
type: post
parent_id: '0'
published: true
password: ''
status: publish
categories:
- Projects
tags:
- Automation
- Business Support
- Programming
- Projects
- Raspberry Pi
meta:
  _edit_last: '1'
permalink: "/almost-paper-free-part-2/"
eye_catch: /assets/4277750232_a80e9b6a02_z.jpg
---
It’s funny the way life is sometimes, isn’t it? You may remember that alongside projects for clients I’m also attempting to [reduce the huge piles of paper]({{ site.baseurl }}{% post_url 2016-04-07-towards-paper-free-part-1 %}) threatening to swallow my office. It’s been a couple of months since I first let you know about my plans, so I thought it was about time I updated you.

<!--more-->

I’ve made some pretty good progress, I found decent libraries for Python (my language of choice for this project, I’ll explain why later) to help me connect with the scanner and also connect with [Evernote](https://evernote.com/upgrade/?tier=premium&amp;origin=ebcc&amp;offer=cc_dlumm)* without using the send by email feature. In fact, I’ve gotten so far as to be able to start the process off and get documents into the test version of Evernote.

“So wait, what’s funny about that?” I might hear you ask. The funny thing is that in the last month our 8-year-old printer finally gave up and we started the long and arduous task of researching a new printer. It needed to be an all-in-one, colour, relatively cheap ink, wireless and have support for Google Cloud Print. The printer I finally settled on was the [Epson XP-830](https://www.epson.co.uk/products/printers/inkjet-printers/consumer/expression-premium-xp-830), which not only has an automatic document feeder (ADF) but it also does duplex scanning; and to top it off, it can also scan to various cloud services including, you guessed it, Evernote.

So not only am I short on time to finish the project at the moment, I’m short on motive - or at least that’s how it would seem at first glance.

Whilst the Epson does a very good job, and I’m now using it to scan any new documents that arrive, it works using the Evernote email address (which is a premium feature) and can only handle one document at a time, with the need for a short wait between each as the scanner processes and delivers the data to Evernote. It isn’t going to be the best tool to handle the huge backlog I have.

Everything is looking good for getting this project to work as I’d like it to. I just need to clean up what I’ve done so far and give myself at least one easy way to kick off a scan job, whether that be a hardware button connected to the raspberry pi or a page/app I need to get up on my phone - ideally I’d like both, and that’s why I picked Python as the best language for this particular task. Python and the Raspberry Pi go hand-in-hand, plus it’s a pretty good language for web development.

So perhaps next time I update you I’ll be able to tell you that I’ve eradicated the paper mountain from my office and I can finally see the sun. Would you be interested in paying someone to help you reduce your paper? Maybe you’ve got another pesky problem that could be solved with a little bit of technology? Write a comment below or [contact us]({% link _pages/contact.md %} "Contact Us") to see if we can help!

_* Any link with an asterisk is a sponsored or affiliate link; if you click on it I will be rewarded and in most cases so will you. However, if you don’t want to click the affiliate link you can always click the non-affiliate version listed below:_

* [Evernote.com](https://evernote.com/)

Photo credit: [ajclarkson](https://www.flickr.com/photos/ajclarkson/4277750232/) via [VisualHunt](https://visualhunt.com/) / [CC BY-ND](http://creativecommons.org/licenses/by-nd/2.0/)