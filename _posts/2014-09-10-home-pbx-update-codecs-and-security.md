---
layout: post
title: 'Home PBX Update: Codecs and Security'
date: 2014-09-10 10:00:27.000000000 +01:00
type: post
parent_id: '0'
published: true
password: ''
status: publish
categories:
- Asterisk
tags:
- Asterisk
- FreePBX
- Projects
- SIP
- Telephony
- VoIP
meta:
  _edit_last: '1'
  dsq_thread_id: '3004767610'
permalink: "/home-pbx-update-codecs-and-security/"
---
_This is the next instalment of a series of [blog posts](http://twinklebob.co.uk/tag/asterisk/) following the ongoing installation of a PBX (a Private Branch eXchange, literally a private telephone switchboard) in my house._

The thing about technology is that it's great when it works, but it can be a pain to get it working. So far getting [our home phone exchange]({{ site.baseurl }}{% post_url 2013-08-20-advanced-telephony-for-the-everyman %}) (PBX) working has been just like that, but that's exactly why I want to do it, so that I can go through all of the pain and use my experience to help other people. I doubt the savings we’ll make on phone calls will be so substantial, but the convenience of being able to transfer calls between handsets and pick up calls from VoIP and our land-line on the same devices will be extremely useful.

<!--more-->

Since it’s been a little while since my last update, it might be worth just recapping what I’m doing and why. Making calls over the internet has been around a while and the technology has gotten better and so have our connections. Generally at home you might have a land-line, your mobile phone and some sort of internet telephone (even if that is just something like Skype). Each route has a different handset and different charges etc. What I’m looking to do is connect all these up. That will allow us to make calls on the cheapest route, allow people to call us on multiple numbers (that can include international numbers, if you often get calls from other countries) or call us over the internet, have conference calls and transfer calls between handsets. All that works with the help of a server and a gateway to our land-line, if you wanted this it could cost you as little as £70 in hardware!

The reason it has been a little while since my last update is because I’ve been tackling some other projects plus I had a problem with call quality that I couldn’t quite get to the bottom of. It was causing a lot of echo and made the system basically unusable. A brief bit of research suggested that it might be caused by my Asterisk server being virtualised (see the [previous post]({{ site.baseurl }}{% post_url 2013-09-13-a-home-pbx-surely-thats-expensive %}) for more details) so I decided to park the project until I could get myself another Raspberry Pi to use.

It wasn’t a eureka moment that got me back on the project, however, but a security concern. All this time the server has been happily running in the background whilst I’ve been largely forgetting about it, but it had been drawing attention to itself. There’s been a recent spate of people with nothing better to do than try and find poorly-secured Asterisk installations and to abuse them.

Security on anything connected to the internet is always slightly concerning, but something that could allow attackers to make very costly calls at your expense? That’s definitely something that I did not want.

Thankfully my installation was already reasonably secure and I started to get emails telling me that a particular IP address had been banned because it was continuously trying to get access to the Asterisk server.

That being said, I still did some research and bumped up my security according to the [advice from Digium](http://blogs.digium.com/2009/03/28/sip-security/) (the primary developers of Asterisk) which boosted my confidence.

During some testing of the new security I discovered that my mobile phone based client didn’t have a full set of codecs, in fact the codecs installed were pretty naff. The codec (short for COder-DECoder) describes how the audio is converted into digital signals and back again, a codec you have probably heard of is MP3. I installed a free codec pack and added these to the codecs in use on both test phones and all of a sudden the call quality has improved dramatically!

It’s often the rule in these situations that when the problem looks complicated the solution is far more simple than you even bother to look at. I hadn’t even considered that codecs would improve the situation with respect to echo!

So now I have more confidence in the system again I’m back into the swing of configuration. I need to rearrange some equipment in the house, but at the next available opportunity I’ll be installing the gateway between the Asterisk server and the land-line. From there on in we’ll be answering calls to the home phone on our mobiles and making calls over the cheapest provider. It’s still going to be a bumpy road, no doubt, but I’m excited to see how this system can help us.

I’m looking forward to the first time someone calls the house and we pick it up from somewhere completely different or the first time we have to transfer a call from one handset to another.

Quick takeaway: Security needn’t be a concern, there are ways to secure the system; call quality shouldn’t be a concern either, I’ll be doing more testing and tweaking in that area.

What about you? Would you like to get more from your phone system? I’d be happy to help you work out your requirements and decide whether a home PBX would be right for you. Just [contact me]({% link _pages/contact.md %} "Contact Us") in the usual ways.
