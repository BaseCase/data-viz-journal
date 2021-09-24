---
layout: post
title: Digging into the Data
---

# Digging into the Data

I've started exploring the data sets available on the [City of Madison Open Data website](https://data-cityofmadison.opendata.arcgis.com/). There's a lot of stuff here! In my imagination, I was expecting to poke around on this site and stumble across some incredibly fascinating dataset that just screamed a particular kind of visualization it wanted to have applied to it.

The reality is much more, uh, administrative than that. A city deals with all kinds of data, and most of that data is pretty mundane. For example, there's a list of every street light that the city maintains, along with some data about each light. Here's what that map looks like:

![Madison streetlights map]({{site.url}}/img/madison_streetlights.jpg)
*a map of Madison streetlight locations on the Isthmus*

What can we see from this? Well...there certainly are a lot of streetlights downtown.

## Asking questions to find stories

What I learned from my first foray into the open data website is that there isn't any low-hanging fruit. If I want to find an interesting story to tell and to tell it in a compelling way, I need to be willing to push this data further than surface-level. I notice a couple of things when I look at this screenshot:

* There are some street lights floating out in Lake Mendota. There are, as far as I know, no streets out there. Is that a mistake in the data set or something more interesting?
* The lights are super dense down State Street. There are a lot of maps on this website. Are there other things I can learn about State Street that might correlate in some way with street light density?

Those two questions are examples of the two main things I'm trying to ask as I poke around in this data:

1. Is there anything surprising or interesting about *this* data?
2. Is there a way to correlate the data in this set with *another* set in an interesting way?

## Next week: more exploration, some building

As fun as it is to click around on the Open Data website, I need to start setting down some groundwork for my actual app. The sooner I have some basics up and running, the more time I'll have to put data into the system and work with it.

I've decided to use [D3.js](https://d3js.org/) to help visualize the data. It's a powerful JavaScript library used all over the place for data visualizations both simple and complex. Most importantly: it's popular enough to be something of an industry standard, which means it's easy to find help if I get stuck while using it.

With any luck, I'll find a little time to add some CSS to the log, too :)
