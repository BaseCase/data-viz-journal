---
layout: post
title: Basic Tech
---

# Basic Tech

This week I spent some time getting the basics of the project's tech up and running. The bulk of the work of this project is in learning and data analysis, but my final output is a running website, so I wanted to pick things that would get the job done with a minimum of fuss on my part.

## Architecture
This is a simple web app, using a straightforward setup. We'll have:

- A server, responsible for fetching data from the Madison data API on a regular schedule, processing it, and making it available to the client.
- Client code, written in HTML and JavaScript, which will request data from the server and render it into data visualizations.

## Platform: Heroku
![Heroku Logo]({{site.url}}/img/heroku_logo.png){:class="small-image"}

I'll be running the app on [Heroku](https://www.heroku.com/), an app hosting service that makes it easy to get something up and running fast. Most importantly for me, they have a free tier! The downside is that unless you pay, your app goes to sleep after an hour and will take a while to wake up when someone visits it, but hey, free.

## Server: Luminus
![Clojure Logo]({{site.url}}/img/clojure_logo.png){:class="small-image"}

My web framework is [Luminus](https://luminusweb.com), one of the most popular ones for the [Clojure](https://clojure.org/) programming language. I honestly don't know that much about it, but I've been learning Clojure for fun, and this seems like a good excuse to play around with it. Since the project's backend needs are pretty simple, I'm not worried about too many stumbling blocks with an unfamiliar framework.

## Client: d3.js
![D3 Logo]({{site.url}}/img/d3_logo.webp){:class="small-image"}

My client code will be simple HTML, CSS, and JavaScript, and to actually draw my data visualizations, I'll use industry standard [d3.js](https://d3js.org/). D3 is a bit complicated to learn to use, but its flexibility and power more than make up for this. I anticipate having to bash my head against d3 a fair number of times while getting it to do what I want, but I know the investment will pay off in the long run.

## That's it!
And that's everything! Like I said, I wanted to keep things nice and simple. This site is going to have at most a two-digit number of visitors at any time, so I really don't have to concern myself with anything more complex than this.

The site is [up and running now](https://infinite-shelf-21164.herokuapp.com/), though there isn't anything there yet besides placeholder text. More coming soon!
