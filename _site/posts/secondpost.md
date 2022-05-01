---
title: This is my second post.
description: This is a post on My Blog about leveraging agile frameworks.
date: 2021-08-02
tags:
  - number 2
layout: layouts/post.njk
---

# Introduction

Hey everyone! We're going to continue looking at Web Components, from the perspective of a Front End Developer. Today, we're examining a project where we study how we can find someone's geolocation from their IP Address. 


# GeoIP API
First, let's take a look at the GeoIP API. Check out [this link](https://freegeoip.app/json/) to see an example of this at work.

![GeoIP API](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/ccqztzq84p2gngvporwo.png)

Here we see that our constructor for our API is linking back to the GeoIP API, which enables our APIs to work together.

# IP Fast API
We now move to the IP Fast API.

![IP Fast API](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/4py3j4yjnno3smtfu4uu.png)

The `async updateUserIP()` automatically updates the IP, with the `fetch()` function grabbing an IP through the GeoIP API, and once the response is confirmed to be okay, the data comes back to us in the form of safe JSON data.

Then, we can pull out the necessary information from the JSON data, the IP, and then the corresponding city and country. Finally, a composite attribute, called location, is created.

# Utilizing Both APIs

![Both APIs being used together](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/15qljdcb13b6chqqerre.png)

Finally, we can proceed to utilizing both APIs together, as seen in this image. What this code accomplishes is that it pulls the location from the GeoIP API, and then gathers data from the IP Fast API, and then outputs it in the render function.


![Render Method](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/vhm9uzaq65v5442gh0ux.png)

Finally, the render method takes the information and searches it and pulls up the necessary wikipedia queries.


