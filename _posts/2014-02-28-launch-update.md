---
layout: post
title: LAUNCH Update
categories: [blog]
tags: [hackathon]
---

It has been a few days since the [LAUNCH Awards Ceremony](http://launch.co/story/launch-awards-ceremony-icehousecorp-dreamapp-winner-flyr-hackathon-winners-35k), so I thought I would take a moment to reflect on the experience, provide an update to my [previous post]({{page.previous.url}}), and clarify some inaccurate details. It has been a mercurial experience that I'm glad to have been a part of. Nearly forty eight straight hours from concept to working proof.

Lack of sleep, unfamiliarity with the contest format, or just enthusiasm of our accomplishments may have all contributed to the details of my previous post including slight inaccuracies. It turns out, the first round of condensed team judging included fourteen, not twelve teams. Similarly, the next round was out of seven, not five. We were consistently placed number one when listed with other teams, but at this time I am not certain that had anything to do our rank among the teams. We did, however win an award from [Rackspace](http://www.rackspace.com/) which includes credit toward a year worth of hosting there.

Our concept going in was an automated performance testing suite that we decided to call [PerformaceCI](performanceci.com). We initially dug in to [Drone](https://github.com/drone/drone) in an attempt to build on top of that. After about four hours and not a lot of progress, we decided to scrap our work and start from scratch. We built on a [Rails](http://rubyonrails.org/) and [resque](http://resquework.org/) stack relying on [Docker](https://www.docker.io/) to take care of encapsulating the applications being tested. I won't go into technical details here, but I plan to elaborate more on that in a later post and documentation. All of our work is open source and available on [GitHub](https://github.com/performanceci/performanceci-core) now.

We're not ready to quit our day jobs just yet. However, the product is already useful to us today and we're confident that we can build a business on offering hosted and enterprise solutions based on this core open source product.  For now, we plan to polish the core in our spare time while we figure out how to effectively build a sustainable business around it.

No one on my team had ever done a "hackathon" like this before. We have all have stayed up far too late into the night working on this or that. I have even participated in employer sponsored "hack days" before. But none of us had ever done an event such as this. If you're even the slightest bit interested, I encourage you to do some. It can be exhilarating. Just go in with the intention to get exposed to some new piece of technology or concept and have fun with it.
