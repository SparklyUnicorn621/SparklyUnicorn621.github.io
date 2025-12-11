---
layout: post
title: Light-up Teddy Bear
subtitle: Final Project Report
thumbnail-img: /assets/img/FinalBear.jpeg
gh-repo: daattali/beautiful-jekyll
gh-badge: []
tags: [homework, arduino, code, sewing]
comments: true
mathjax: true
author: Laela Clark
---


## Motivation

When I was little, my dad gave me a light-up Build-a-Bear, and it quickly became my favorite stuffed animal that I still keep with me today. This teddy would light up when a button in the arm was pressed and have a fading pattern of color-changing lights that it would cycle through before turning back off. Unfortunately, it no longer lights up, so I decided to recreate this nostalgic toy for my final project.

This project is really meaningful to me because it combines everything I've learned this semester with a cherished childhood memory. Many people have special stuffed animals or comfort objects from their childhood that hold sentimental value. By using e-textiles to recreate a version of my beloved teddy bear, I'm able to preserve that memory in a tangible way.

## Project Description

My light-up teddy bear features five independently blinking LEDs with random brightness levels and timing, mimicking the random color-changing pattern of my original Build-a-Bear. 

The bear has two modes of operation:
 
  **Automatic Dark Mode:** A light sensor continuously monitors the ambient lighting. When it detects darkness (like at nighttime), the LEDs automatically turn on and begin their random blinking pattern.

  **Manual Button Mode:** During the day or in bright conditions, you can press a momentary button sewn into the bear's paw. When pressed, the LEDs blink for 15 seconds before automatically turning off.

## Materials List

### Electronic Components
- 1 LilyPad Arduino Protosnap Plus
- 1 LilyPad Light Sensor
- 1 Momentary Button
- 5 LilyPad LEDs (connected to pins A4, A5, A6, A7, A8)
- 1 LiPo Battery (rechargeable)
- insulated copper wire
- Solder

### Fabric & Materials
- Sherpa fabric (about 1.5 small dog blankets)
- Regular sewing thread
- Stuffing (poly-fil)
- Black stuffed animal eyes and nose
- Velcro
- satin ribbon (for the bow)


## Paper Prototypes

### Original Paper Prototype
![Front](/assets/img/FinalBearProto.jpg)

This was my initial design showing how I planned to connect all the components with conductive thread.

### Revised Paper Prototype
![Front](/assets/img/PaperProto2.png)

After testing with alligator clips, I revised my design to use soldered wire connections instead of conductive thread for the internal wiring. This revision better reflects the actual soldered connections, but not the actual wire lengths or placement because I nolonger had to worry about traces/wires crossing and I eyeballed the wire lengths based on my partially-sewn bear at the time rather than measuring precisely.

## Alligator Clip Prototype

### In the Dark
![Front](/assets/img/FBearA1.jpeg)

### With the Button Pressed
![Front](/assets/img/FBearA2.jpeg)


## Final Working Project

### In the Dark
![Front](/assets/img/Bear1.jpeg)
![Front](/assets/img/Bear2.jpeg)

### With Button Pressed
![Front](/assets/img/Bear3.jpeg)

## 3 Tips to My Past Self

### 1. Felt would've been easier, but sherpa is worth it (with one modification)

My life would have been SO much easier if I'd used felt or something similar, but honestly? I'd still choose sherpa again because I absolutely love the way it looks and feels. The one thing I'd change: buy sherpa that only has the fuzz on one side! When I first started to try and trace out the pattern pieces, I quickly realized that it would be insanely difficult with the fuzz there and that I would likely run into more problems going forward. But because I was already committed to this (and I was unable to purchase single-sided sherpa and have it arrive quickly enough to finish the project on time), I ended up having to cut all the fuzz off the wrong side of the fabric, which was tedious and messy. Single-sided sherpa is definitely a must.

### 2. BUY CHALK. Seriously, just buy chalk.

I had taken my fabric chalk to campus with me, so when I started tracing and cutting out the pieces at home over thanksgiving, I used this blue pen/marker instead. Big mistake. My fingers were stained blue for DAYS. Every time I touched the outlines to sew the seams together—even days later—my fingers kept getting stained blue all over again. Fabric chalk is cheap, works really well and doesn't turn you into a Smurf.

### 3. Double check your velcro placement BEFORE sewing it down.

I soldered all my connections (which was really cool to learn and definitely made the project look cleaner since I didn't have to worry about metallic thread traces or insulation), but I cut all the wires assuming the velcro opening would be on the right side. Then I sewed the velcro on the LEFT side instead without realizing I was putting it on the wrong side. By the time I had realized my mistake, I had pretty much finished sewing the enitre bear and sherpa is REALLY hard to seam rip without accidentally ripping up the fabric. I ended up having to finagle everything to fit, which luckily worked because I had left some extra wiggle room in the wire lengths just in case. Double-check your placement before you commit!


## Citations

- Teddy bear pattern: [https://www.howjoyful.com/howjoyful-bear-tutorial-and-pattern/](https://www.howjoyful.com/howjoyful-bear-tutorial-and-pattern/)
- Youtube video reference for sewing the teddy bear patterm: [https://www.youtube.com/watch?v=e_6qTxB1wQA](https://www.youtube.com/watch?v=e_6qTxB1wQA)
- LilyPad hookup guide for paper prototype components: [https://learn.sparkfun.com/tutorials/lilypad-light-sensor-v2-hookup-guide](https://learn.sparkfun.com/tutorials/lilypad-protosnap-plus-hookup-guide/all)
- Course lecture slides and POGIL activities
- Markdown Cheatsheet: [https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
