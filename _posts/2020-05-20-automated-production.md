---
title: Automating Production
description: Or how we took a factory from a complex mixture of software and human processes into a the nirvana of full automation.
layout: post
type: post
published: true
category: case-study
tags:
- Case_Study
- Automation
- Streamline
- PHP
- C#
image: /assets/pxfuel-qsowr-1024x768.jpg
author: davidlumm
---

It’s possible in a few companies to get by with very little technology, but for the rest there are decisions to be made, equipment to be bought and processes to be laid down. If you’re an expert in anything other than technology, you might not be able to solve those problems easily.

As an example of a problem we helped to solve, there was a small factory that had a couple of ecommerce websites, selling directly to consumers and making on demand. They had a production management system and a team taking telephone orders.

Each process had a separate evolution, created by different teams to solve different problems, except over time they had been brought together in a perfect example of the spaghetti approach.

<!--more-->

The orders came in through the website and delivered by email to a single inbox, monitored by one of the order processing team. Those emails were printed once a day and distributed through the team who would re-enter the order details into the production system to push the order through the factory. As you can imagine, mistakes were sometimes made.

Douglas Adams, author of the Hitchhikers Guide to the Galaxy series, once wrote “_We are stuck with technology when what we really want is just stuff that works._” Science fiction has promised us that by now we’ll be comfortably idle, sitting back whilst technology takes care of us, yet here we are bogged down in more technology and working just as hard as ever.

This is a problem for big businesses and for small businesses, however the difference is that the large companies have larger budgets and people whose job it is to think about these things, smaller companies rarely have such luxury.

I doubt that this company are alone in these sorts of processes that have evolved out of ideas that were supposed to help. When they started doing it that way online sales were just a small fraction of the total load, but it had grown to a massive problem. We developed a bespoke system that would connect the ecommerce website and production systems together, automatically cutting out huge delays, opportunities for error and the requirement for additional workforce that had to be hired in at peak times.

Now, for those that are interested in the technical aspects of the problem and solution, the eCommerce web-estate was all custom PHP, the factory production system was mostly powered by a legacy system combining classic Asp and Asp.net. In between the two we placed a windows service which was constantly running, processing orders, and an internal website given visibility to the queue waiting to be processed (this allowed orders to be cancelled if the customer contacted within 24 hours before they were automatically processed).

Photo credit: [pxfuel](https://www.pxfuel.com/en/free-photo-qsowr)
