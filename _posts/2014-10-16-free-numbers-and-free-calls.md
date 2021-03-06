---
layout: post
title: Free numbers and free calls
date: 2014-10-16 10:11:24.000000000 +01:00
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
- SIP
- Telephony
- VoIP
meta:
  _edit_last: '1'
  dsq_thread_id: '3122304343'
permalink: "/free-numbers-and-free-calls/"
image: /assets/can-communication-conversation-362-1024x682.jpg
---
_This is the next instalment of a series of [blog posts](http://twinklebob.co.uk/tag/asterisk/) following the ongoing installation of a PBX (a Private Branch eXchange, literally a private telephone switchboard) in my house._

I've pretty much got a working system now so I wanted to update you all, all that remains at this stage is connecting up to the existing landline to allow calls in/out over that. Given our needs I’ll try and keep that step as simple as possible.

<!--more-->

So now we have 5 inbound numbers (6 including the landline): a US number from [IPKall](http://www.ipkall.com/), two UK internet telephone numbers (these start 056) which came with my service from [VoipCheap.co.uk](https://www.voipcheap.co.uk/) and [Voipfone](http://www.voipfone.co.uk/) (two VoIP providers I use for incoming/outgoing calls), and two local numbers (one based near us and another based in Bristol) which came courtesy of [TelNG’s UKDDI service](https://www.telng.com/ukddi.html).

I can’t see us needing any more than that. I've already made use of the US number to be contacted by a company based out there, I probably won’t make much use of the inbound number issued by VoipCheap, now that I have a local number.

This raft of inbound numbers has allowed me to do clever inbound routing. For instance [IFTTT.com](https://ifttt.com/) (<a href="http://twinklebob.co.uk/tag/ifttt-com/">I’ve written about IFTTT before</a>) only support US telephone numbers (a big reason for me getting a US number in the first place), so I can have a rule in the phone system that means any calls from IFTTT's number are always forwarded to my handset(s).

It would also be possible to have a central number that rings all devices and a unique inbound number for each device, like you might have in a workplace. For our needs, though, the numbers generally map to all available handsets.

As well as the numbers connecting us to the plain old telephone system (POTS), the two VoIP providers also give me two incoming connections from other SIP compatible devices. These can be routed in the same sort of ways.

So that’s incoming calls, what about outgoing? The majority of our calls will be going out over VoipCheap's service. If you top up every 90 days you get what they call [FreeDays](http://www.voipcheap.co.uk/calling_rates/), which allows you to make up to 300 minutes of calls per week to several destinations, including UK standard landlines (01, 02 and 03 numbers) and US landlines and mobiles. UK mobiles aren't free, but at 2.3p/min (at time of printing) this is cheaper than our current landline provider.

The majority of calls will be going out over this service, but IPKall offer a service to [connect US “toll-free” numbers free of charge](http://www.ipkall.com/tollfree.htm), so I've also made use of that. It’s fascinating to ring a US free phone number and for it to read my US number back to me as if I was actually in the country!

One thing that could be easily overlooked is emergency calls, i.e. 999, but these will need to go out over our land-line as much as possible. If that’s not possible Voipfone offer emergency registration, which means that if we ring using that line our address will be discovered from the telephone number.

Once I've got the land-line connected and our existing home phone, I’ll write an update listing all of the settings I've used. I wouldn't have got this far if others hadn't done the same, so I feel it’s only fair. Obviously I won’t be giving away any login credentials…

So that’s it for now. Hopefully in the coming weeks I’ll have a complete system. I'm still looking forward to the first time we transfer a call to our land-line between us, even though at least one of us isn't at home. I'm also looking forward to seeing my phone bill reduce!
