---
title: "circumvention of site blocks"
layout: default
date: 2022-03-20 22:00:00
---

one of the major goals of riza is effective and easy to use circumvention of
site blocks. one of the most basic ways of how blocks work is by denying access
to certain domains and ip addresses. there are, of course, a lot of methods of
circumventing that, such as vpns or tor, but they require installing additional
software, which is a big barrier in adoption amongst general population. thus,
one way in which riza strives to solve this problem is by giving ability to see
blocked site content with nothing more than a modern browser and finally
empowering regular users to exchange links to blocked sites.

<cut/>

the basic idea is, of course, to use p2p data transmission instead of loading it
from server. but how would browser get the code needed to initialize the
transmission? if there is a convenient site that loads the code and then the
data from the blocked site, this convenient site can be conveniently blocked by
the same censorship entity. "if there is a public link leading to censored
information, that link will be blocked". despite that statement looking like it
alone can prove impossibility of our plans, there is a couple of "but"s we can
offer.

first of all, links do not need to be public. as long as people exchange links
to one domain among people they trust, that domain can stay safe. since all the
hosting is done on p2p network and clearnet server needs to only host a small
file, the cost of creating new domains and generating new links can be very
cheap.

but that of course doesn't really solve the problem. we want links that will
continue to work, that will continue to provide new information. what if there
was a way to create a link that wouldn't depend on any particular domain? what
if there was a protocol supported by every modern browser that couldn't be
blocked? luckily such a protocol does exist. it is not without its quirks, but
it works right now.

i've setup a test page that display the method with an example of freshly
blocked russian media "doxa". you can see it
[here](https://riza-committee.github.io/demos/doxa.html)
