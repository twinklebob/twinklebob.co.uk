---
layout: post
title: What about Home Automation?
date: 2014-09-03 10:00:56.000000000 +01:00
type: post
parent_id: '0'
published: true
password: ''
status: publish
categories:
- Home-Automation
tags:
- Home_Automation
- IFTTT.com
- Internet_of_Things
- NinjaBlocks
- SmartThings
meta:
  _edit_last: '1'
  dsq_thread_id: '2984194198'
permalink: "/what-about-home-automation/"
---
Unless you’ve been hiding under a rock for the last, I don’t know, maybe 60 years, you’ve probably heard or seen the phrase “Home automation”. Most people see it one of two ways, either that slightly 1950’s vision of robots and other things that are probably less convenient than what we have today, or the alternative is the vision of a whole house filled with expensive equipment controlled by an expensive controller which all had to be built into the house. Neither is entirely true or entirely false, but one thing is true, it needn’t be (too) expensive nor complicated.

<!--more-->

During the 70s, 80s and more so in the 90s we started to see whole house systems such as X10 that allowed a lot of control over a lot of your house, but this largely meant being trapped into a single manufacturer for all future technology. It was a risk few were willing to take, that’s why 40 years after X10 was introduced our houses still aren’t all filled with it.

With the rise of wireless communications in the form of WiFi and Bluetooth and the growth of the API we’re starting to see the much lauded “internet of everything” start to appear. What this means is that we’re starting to see a lot of single purpose tools, for instance the Belkin WeMo range of remote controlled sockets or the Philips Hue remote control light-bulbs. Whilst these are really impressive tools, they each come with their own app to control them, quickly filling up your phone and tablet with apps. Plus it means that to turn that socket on over there you have to reach for the phone, load up the right app and press the right button - if you’re turning on the socket from down the road it’s quite impressive, but what if you’re in the same room? It’s probably easier to reach over and do it yourself.

Anyway, why pay for expensive sockets that come with apps, when you can get those cheapy remote control sockets for a fraction of the price? Unless you can really see yourself turning something on/off when you’re away from the house it might not be worth it.

The problem with all these disparate systems is slowly being conquered by other companies who are developing tools to integrate them together and also to add extra capabilities. The three main players in this area, that I’ve come across, are [IFTTT](https://ifttt.com/) (pronounced like “gift” without the “g”, I’ve [written about them before](http://www.geek-speak.co.uk/2013/03/ifttt-automation-for-the-web/)), [SmartThings](http://www.smartthings.com/) and [NinjaBlocks](https://ninjablocks.com/).

**IFTTT** is a pretty amazing tool, which I make great use of, but they only integrate currently with a limited set of real world devices and their scenarios are pretty basic. If _this_ happens then do _that_ (by the way, that’s the meaning of the name: “if this then that”) can only achieve so much.

**SmartThings** was one of the first integrating controllers that I became aware of when it was launched on Kickstarter. As well as host of their own-brand devices they also support any of the internet connected devices (such as the Hue and WeMo devices) as well as Z-Wave and ZigBee devices (these are popular standards for a wide range of devices). SmartThings also integrate with IFTTT for extra awesomeness.
Unfortunately, at the moment, the SmartThings products aren’t officially available in the UK but they can be bought from Amazon starting around £367, which is about double the official price.

**NinjaBlocks**, particularly their new **NinjaSphere** product, have similar capabilities (although their support for Z-Wave devices is currently a little behind SmartThings) but they also support devices that use 433MHz wireless control, such as those cheapy remote control sockets. In fact there’s quite a few 433MHz devices that are considerably cheaper than their internet-connected equivalents; of course the NinjaBlock/NinjaSphere then makes these devices internet connected!

Currently there’s no connection to IFTTT, should you desire one, but the “Ninja Cloud” allows you to do much that IFTTT can do. The NinjaBlocks are a little bit more involved than the SmartThings hub, or at least they can be, but once either system has been set up there won’t be much difference. The NinjaBlocks devices also use open-source software, this means that the users of the software are able to view, modify and improve that same software. What this means is that over time the software will improve and capabilities will continue to be added.

Personally, for me, I’d probably be spending my money on the NinjaSphere, but as I say both have similar capabilities and that’s where we’re going to focus our attention now.

What can be gained having all these sensors and remote controlled devices? Let’s look at a few scenarios to see what it could do for you:

## **1. Intruder Alarm**

So let’s start it simple, detect motion in your house when nobody is supposed to be home, take some pictures (and send them to your phone), phone the police to leave a pre-recorded message and set off a siren and flashing lights. Whilst there are some home security systems that could do this for you, they probably cost a fortune and they almost certainly won’t be capable of serving dual purposes.

With a home-automation system, those motion sensors could also be used to activate lights, the siren could also be used as part of a smoke/fire detection system and as well as a strobe, you could also flash all of the normal house lights. That should put anyone off!

## **2. Turn on an exterior/interior light when you arrive home, only if it’s dark**

You’ve just arrived home and it’s dark. Instead of having to leave an exterior light on all night or rely on motion sensors, you could have the system detect that you are home using the location of your phone and turn on the outside lights and the first light inside the house.

Whilst you’re at it you could also have the system also unlock your front door. Oh yes, it can do that too.

## **3. Follow-me lights**

One of the published examples used in the NinjaSphere marketing videos (for instance on Kickstarter) shows lighting following you around the house. Are you fed up of walking into a room, turning on the lights, finding the thing you’d gone there and then turning them off again only to then turn on a light in the next room. There are usually two solutions to this problem, leave loads of lights on and use lots of electricity or fumble around in the dark unless you intend staying in a room for more than five seconds. Instead how about have the system track your phone (or a smart tag, if you normally don’t carry your phone) and turn lights on ahead of you and off behind you. Sound good?

<iframe src="//www.youtube.com/embed/X604TGDgTVA" width="560" height="315" frameborder="0" allowfullscreen="allowfullscreen"></iframe>

That’s just a few examples, I’ll be sharing some more possibilities in future blog posts. If you’re interesting in adding this technology to your life please [contact me]({% link _pages/contact.md %} "Contact Us")!
