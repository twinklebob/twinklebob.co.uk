---
title: In Defense of Legacy Code
description: The scourge of the developer, the Legacy Code. Is it all as bad as they say?
layout: post
type: post
published: true
category: Web-Development
tags:
- PHP
- Programming
- Web_Development
image: https://i.imgflip.com/43zb7i.jpg
author: davidlumm
---

If there’s one thing that Developers love to hate, the biggest enemy of their creativity, the worst drain on their time, it’s "Legacy Code". It’s a strange term really, when you think about it. Usually we think about a legacy as being a positive thing left behind after a particular person is gone. Whether that’s tangible or financial, like a bequest, or the legacy of a famous or influential person who has left an impression on the world - leaving it a different place to how they found it. In software terms, however, the term "legacy" almost always comes with a negative connotation.

A lot of developers, at the mere smell of legacy code will shout to redevelop from scratch, to seek out the latest new shiny and rebuild the product from the ground up. There can be benefits to that, for sure, but it isn’t the only way. I’m mostly a fence sitter on this one, but if pushed I’d probably fall on the _Maintain Legacy_ side of the fence. I don’t think it’s a black and white decision, though.

<!--more-->

When you hear the term "legacy code" it can mean anything from code written by an absent predecessor (aka "somebody else’s code") to code that has been abandoned when the product is still in active use.

Personally I think that the state of abandonment is a really useful marker here - it might be that the code is no longer supported, no one has worked on it for a while or perhaps the developers have moved on or simply no longer care about it. Eli Lopian, CEO of Typemock, famously [defined Legacy](https://dzone.com/articles/defining-legacy-code) as: _Code that developers are afraid to change_.

Of course, as someone bluntly put it on LinkedIn while I solicited content for this article, "_devs gotta dev_". Working on the same old code in a project you don’t care about, or worse a project that is objectively bad, can be awful. The chance to work in a newer technology and to do it "right" from the beginning can be a very tempting option.

One of the strengths of legacy code that we often overlook though, is the fact it _is_ a legacy, like an heirloom passed down to us. All the blood, sweat and tears of the developer(s) who came before us. All the lessons learned and the victories hard won. Sometimes as our head is turned by the latest new shiny we forget about all the other stuff that isn’t the product we see. In other words, if we don’t learn the lessons of the past we’re doomed to recreate them.

Old code can be complex though. As much as we talk about design and planning, no product stays still for long. It eventually grows organically, someone asks for this feature, someone asks for that feature, and users build their own workflows and workarounds, unintended behaviours that then ultimately get baked into the ongoing development so that no one gets upset. The person who caused a specific change leaves and everyone forgets why the change happened. "_It's always been this way_" is the rallying cry. Office politics inevitably play their part. As [Conway's Law](https://en.wikipedia.org/wiki/Conway%27s_law) puts it: "_Any organization that designs a system will produce a design whose structure is a copy of the organization's communication structure._"

Complex code makes even simple changes complex and you can get to the point where stakeholders, users or customers are saying "can’t you just change x? It’s only a small change." But it’s not a small change, is it? It’s a week’s worth of meetings, a week's development and then a week tracking down where that one weird bug came from and ultimately giving up and rolling the whole thing back. That stuff stings and it _costs_!

However the alternative, if you start from scratch, means you can have a time of lag: where features stop being developed on the old system and the new one also isn’t ready yet. It can be a significant drain on resources and a source of frustration for users/customers, especially when the unforeseen happens (and it inevitably does).

The first thing is to have an honest and frank discussion about the legacy codebase. Is it really as bad as everyone says, or is it redeemable? What is the cost of redeeming the code versus redeveloping a brand new solution? Is there an option to develop the new in parallel and to gradually move parts of the system from the old to the new?

Sometimes it can be helpful to get a third party in to do some of this step. They have no vested interest in either the existing code nor the new shiny, they are just being paid to assess.

Understanding the users, and what they are hoping to achieve with the system, is also vitally important. Doing some analysis of what they do (and some surveying of _why_ they do it) will help to build a picture of the system from an alternative point of view (when compared to the developers). In turn this will help establish a set of User Personas and User Stories, which can then help guide better testing. Understanding the _purpose_ of the system and the desires of the users means you are truly able to determine whether it’s fit for purpose and what (if anything) needs to be improved or replaced.

When it comes to adding features, fixing bugs or slowly migrating to a replacement product, iterative improvement is your friend. It makes much more sense to release small changes regularly than to go quiet on the current version for an extended period and suddenly release an all new version which has not been subject to thorough usage - you can guarantee that users will always do something you don’t expect.

When your customers are complaining about a lack of progress and your developers are screaming "Legacy, run away!" at the top of their lungs you just need to take a step back, do some analysis and determine the best course of action. It might be that you need to introduce some new technologies to keep the developers interested, but that doesn’t necessarily mean throwing away the baby with the bath water.

The legacy of your developers old and new should be treasured and respected, but so should the ever evolving needs of your customers and users. It can be tricky waters to navigate, and sometimes you need a trusted third party to help pilot you to safe harbour.

Photo credit: [Imgflip Meme Generator](https://imgflip.com/i/43zb7i)
