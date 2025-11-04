---
layout: post
title: Ghost Detector
subtitle: Code to Sense When it is "Cold" and "Dark"
thumbnail-img: /assets/img/GhostDetector1.jpeg
gh-repo: daattali/beautiful-jekyll
gh-badge: []
tags: [homework, arduino]
comments: true
mathjax: true
author: Laela Clark
---

In this project, the goal was to create a "Ghost Detector" so that the red lights (I was not entirely sure which two red leds I was supposed to turn on so I did the red pin 6, yellow (which looked pretty orange to me so it was a red proxy) pin A5, and the RGB red pin 12) would turn on when both the temperature sensor read that it was "cold" and the light sensor read that it was "dark".

One tip I would give my past self is to use serial print to see what temperatures the sensor was picking up because I was really struggling to find the right temperature threshold as I have really cold hands (which I have now figured out are far colder than my room so I had to use the palm of my hand) so that the light would not turn on when I touch the sensor but still turn on at room temp.

## This is when it is "Cold" and "Dark" (covering light sensor at room temp):

![Front](/assets/img/GhostDetector1.jpeg)

## This is when it is "Dark" but not "Cold" (covering both light and temp sensors with my hand):

![Front](/assets/img/GhostDetector2.jpeg)
