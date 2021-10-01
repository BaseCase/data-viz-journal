---
layout: post
title: Gee Eye Ess
---

# Gee Eye Ess

Sometimes something is staring you right in the face, and you just need a little prodding to realize it. I remarked last week on how a ton of the [Madison Open Data](https://data-cityofmadison.opendata.arcgis.com/) seemed to be map-based. Well, uh, it turns out there's a reason for that.

This week, I started writing some code to interact with the data API and work towards getting a rough skeleton together for the site I'll be building. The first thing I did was click on the documentation link, and I was taken to the [ArcGIS developer docs page](https://developers.arcgis.com/documentation/). I've been seeing "ArcGIS" in the URL for the Madison data site all semester, but it didn't occur to me to ask "what is ArcGIS?" until now.

## GIS: Geographic Information System

So I went to [ArcGIS's main site](https://www.arcgis.com/index.html) and found out that it's *all about maps*. Maps are, like, its whole thing. So of course a Madison data site hosted by ArcGIS is going to highly mappy!

After reading over the ArcGIS website, the obvious next question was: what is this "GIS" that they are so eager to help with? As far as I can tell, the definition of GIS does not appear on the ArcGIS website! [Wikipedia has the answer](https://en.wikipedia.org/wiki/Geographic_information_system), though, and once I read this page, everything made sense. GIS stands for Geographic Information System, and it's a whole field of its own, overlapping with but distinct from Data Visualization.

Data Visualization has been concerned with maps and correlating data sets by location for its entire history. One of the earliest examples of data viz that gets trotted out all the time is John Snow's map of an 1854 cholera outbreak in London:

![John Snow's 1855 cholera map]({{site.url}}/img/snow-cholera-map.jpg)
*one of the earliest data visualizations and a forerunner of GIS*

In the 1960s, researchers started building computer systems to enable richer and more flexible geographic correlations and visualizations, and from there the field of GIS was born.

![A modern topographical visualization]({{site.url}}/img/topographical-map.jpg)
*a fancy-looking 3D rendering of topographical information*

## Narrowing the focus

I began this project with the assumption that learning about data visualization in general, and exploring Madison's data specifically, would naturally lead me from a too-broad idea ("learn about data visualization") towards a focused project to implement. I don't have an exact story I want to tell about this data yet, but encountering the notion of GIS has helped me start to focus in a bit. It's clear that whatever I wind up making here, it's going to be map-based.
