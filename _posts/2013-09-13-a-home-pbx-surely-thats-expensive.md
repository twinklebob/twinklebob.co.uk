---
layout: post
title: A home PBX? Surely that's expensive?
date: 2013-09-13 13:11:37.000000000 +01:00
type: post
parent_id: '0'
published: true
password: ''
status: publish
categories:
- Asterisk
- Projects
tags:
- Asterisk
- FreePBX
- Projects
- Raspberry Pi
- SIP
- Telephony
- VoIP
meta:
  _edit_last: '1'
  dsq_thread_id: '1755807414'
permalink: "/a-home-pbx-surely-thats-expensive/"
---

_This is the next installment of a series of [blog posts]({{ site.baseurl }}{% post_url 2013-08-20-advanced-telephony-for-the-everyman %} "Advanced telephony for the everyman") following the ongoing installation of a PBX (a Private Branch eXchange, literally a private telephone switchboard) in my house._

In lieu of any real progress on this front, due to some other commitments, I thought it would be good to discuss the hardware involved in the project to show how accessible this technology is.

<!--more-->

At the bare minimum you need a computer of some description (this will be the server) and some sort of device to actually make calls on (the client). If you want to interact with your landline you'll need an FXO gateway and if you want to use your existing phones, you'll need an FXS adapter, aka an Analogue Telephone Adapter (ATA).

All of that is sounding sort of expensive, isn't it? Well it doesn't need to be. All of this can be replicated on a small scale pretty easily.
In terms of server I'm running a PBX-specific system ([FreePBX](http://www.freepbx.org/)) on a virtualised platform as part of a server I already have running all day. In layman's terms that means I'm using the spare capabilities of the server to create a make-believe server that will act as my PBX. However, if you didn't have this capability, I have heard good things about running FreePBX on a Raspberry Pi (around £30 for a Model B, less if you shop around).

I'll be interacting with our landline with the help of a Linksys SPA-3000, which you can pick up on ebay around £20. I think I got mine for £16 about a year ago when I first started considering this project. The SPA-3000 also includes a line to connect a real phone to, so I'll be making use of that.

We'll have our mobiles (both running Android) as clients, too, but if we need to add any more real phones I've got an old Linksys PAP2 lying around, that will give us a further 2 lines. They can be picked up for around £20 too.

So hardware wise, we're looking at around £40 for my set up, a similar set up could be had at your home/office for around £70.

Just to remind you of the benefits of such a set up, we'll have multiple lines, the ability to do conference calls (should we ever wish), cheesy on-hold music, intelligent routing (e.g. the [TwinkleBob line]({% link _pages/contact.md %} "Contact Us") will only call my device(s) and only during office hours) and, most importantly cheaper calls.

At home, our most expensive calls are to mobiles (11.3 pence per minute during the daytime plus a 13.87p connection charge) because despite having free minutes on our phones we don't have great signal at home; this is closely followed up by daytime calls to standard 01 and 02 numbers (8.41ppm). With [VoipCheap](http://www.voipcheap.co.uk "VoipCheap UK") those calls will be 2ppm and free with no connection fee, as long as we top up £10 every 90 days.

Plus, while we're calling out, someone else can still call in and even have their call answered by the one of us who isn't already on the phone or by a central voicemail system.

Perhaps it's overkill for us at home, but hopefully it'll prove the point that it's possible to get a better phone system without paying out of the nose for it! Let me know if you're interested in joining me on this journey of discovery!
