---
layout: post
title: Home library management
date: 2014-01-07 16:14:03.000000000 +00:00
type: post
parent_id: '0'
published: true
password: ''
status: publish
categories:
- Mobile Apps
- Projects
tags:
- Lyverva
- Mobile Apps
- PHP
- Projects
- Web Development
meta:
  dsq_thread_id: '2098017250'
  _edit_last: '1'
permalink: "/home-library-management/"
---

I love books, we have quite a lot at home, covering a wide range of subjects, plus a lot of fiction books and children's books. We don't mind lending them out, but eventually it becomes quite hard to keep track of them all: where's this book, is it in the living room, the study, does someone else have it? etc.

<!--more-->

A few years ago, when I still had a desktop PC at home, I used to use a program called [Tellico](http://tellico-project.org/){:target="_blank"} to help me manage my collection of books. The upside, it had cover pictures and could record the locations of the books, it could even export the entire collection to a static webpage so I could share it with friends. But without a barcode scanner I had to type in the ISBN for each book manually.

I don't generally use a desktop or a laptop at home these days, outside of work, I prefer to use my phone and my tablet to do most tasks. We've got books spread over 3 bookcases in 2 rooms, plus a pile of children's books in my child's room. So I decided I'd look at doing this again.

So I went looking for an app to do it. It needed to do a few things for me:

* Allow ISBN scanning with the phone camera
* Automatically look up book details
* Record the location the book is stored
* Synchronise across devices
* Provide a web interface so friends and family can see what we've got and whether it's available or not

I couldn't find anything that perfectly fit the bill although [Libramatic](http://www.libramatic.com/){:target="_blank"} came pretty close. It was missing the all-important location setting, at least at the free level. The website isn't entirely clear on what you get for your €29.99 a month. In addition, a lot of the interaction once a book has been entered is using it's unique reference - something that would make sense in a library with lots of copies of the same book, but not so much at home.

So I decided that the time is right for me to have another crack at mobile development, it's been a more than two years since my last failed attempt. I'm looking to use PhoneGap for the clients so I can write for both Android and iOS, with PHP for the backend and I'm hoping to record some of the journey here.

I'm going to release the source code under the MIT licence, so that others can make use of it, although if it's any good I may also charge for premium features.

The project is called Lyverva, which is Cornish for Library. I have a fascination with the Cornish language, but not a vast knowledge of it, yet.

I could do with your help guiding the project so I'd appreciate if you could fill in this [quick survey](https://docs.google.com/forms/d/1kXr-BvWWRWPkL8TvzMkBnXmAUBFE2CVDz9Dk05zcdGM/viewform "Lyverva Survey"){:target="_blank"} for me.

The projects are on GitHub as [lyverva-server](https://github.com/twinklebob/lyverva-server "Lyverva PHP Backend Server (GitHub)"){:target="_blank"} and [lyverva-client](https://github.com/twinklebob/lyverva-client "Lyverva PhoneGap Client (GitHub)"){:target="_blank"}, although they're pretty bare bones at the moment so they might not make much sense.
