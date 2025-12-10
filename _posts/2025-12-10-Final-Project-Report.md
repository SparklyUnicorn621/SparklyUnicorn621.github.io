---
layout: post
title: Light-up Teddy Bear
subtitle: Final Project Report
thumbnail-img: /assets/img/FinalBearProto.jpg
gh-repo: daattali/beautiful-jekyll
gh-badge: []
tags: [homework, arduino, code, sewing]
comments: true
mathjax: true
author: Laela Clark
---


## Motivation

When I was really little, my dad gave me a light-up Build-a-Bear, and it quickly became my favorite stuffed animal that I still keep with me today. This teddy would light up when a button in the arm was pressed and have a fading pattern of color-changing lights that it would cycle through before turning back off. Unfortunately, it no longer lights up, so I decided to recreate this nostalgic experience for my e-textiles project.

This project is meaningful to me because it combines technology with a cherished childhood memory. Many people have special stuffed animals or comfort objects from their childhood that hold sentimental value. By using e-textiles to restore this beloved bear's lights, I'm able to preserve that memory in a tangible way while also demonstrating how we can repair and recreate meaningful items instead of simply replacing them.

## Project Description

My light-up teddy bear features five independently blinking LEDs that create a firefly-like twinkling effect, mimicking the random color-changing pattern of my original Build-a-Bear. The bear has two modes of operation:

  Automatic Dark Mode: A light sensor continuously monitors the ambient lighting. When it detects darkness (like at nighttime), the LEDs automatically turn on and begin their random blinking pattern, making the bear glow softly in the dark just like it did when I was little.

  Manual Button Mode: During the day or in bright conditions, you can press a momentary button sewn into the bear's paw. When pressed, the LEDs blink for 15 seconds before automatically turning off. This gives you control over when you want the lights to shine, without them staying on indefinitely.

Each of the five LEDs blinks independently with random brightness levels and timing, creating an organic, magical effect rather than a synchronized mechanical pattern. This randomness makes it feel alive and special, just like the original.

## Materials List

### Electronic Components
- 1 LilyPad Arduino USB Plus
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


## Paper Prototypes

### Original Paper Prototype
![Front](/assets/img/FinalBearProto.jpg)

This was my initial design showing how I planned to connect all the components with conductive thread.

### Revised Paper Prototype
![Front](/assets/img/PaperProto2.png)

After testing with alligator clips, I revised my design to use soldered wire connections instead of conductive thread for the internal wiring. This revision better reflects the actual circuit implementation and connections, though I eyeballed the wire lengths based on my partially-sewn bear at the time rather than measuring precisely.

## Alligator Clip Prototype

### In the Dark
![Front](/assets/img/FinalBearProto.jpg)

### With the Button Pressed
![Front](/assets/img/FinalBearProto.jpg)


## Final Working Project

### In the Dark
![Front](/assets/img/FinalBearProto.jpg)
![Front](/assets/img/FinalBearProto.jpg)

### With Button Pressed
![Front](/assets/img/FinalBearProto.jpg)

## 3 Tips to My Past Self

### 1. Felt would've been easier, but sherpa is worth it (with one modification)

My life would have been SO much easier if I'd used felt or something similar, but honestly? I'd still choose sherpa again because I absolutely love the way it feels. The one thing I'd change: buy sherpa that only has the fuzz on one side! I ended up having to cut all the fuzz off the wrong side of the fabric, which was tedious and messy. Single-sided sherpa exists and would've saved me hours.

### 2. BUY CHALK. Seriously, just buy chalk.

I had taken my fabric chalk home with me, so when I started tracing and cutting out the pieces, I used this blue pen/marker instead. Big mistake. My fingers were stained blue for DAYS. Every time I touched the outlines to sew the seams together—even days later—my fingers kept getting stained blue all over again. Fabric chalk washes off easily and doesn't turn you into a Smurf. Learn from my mistakes.

### 3. Measure your velcro placement BEFORE soldering everything

I soldered all my connections (which was really cool to learn and definitely made the project look cleaner since I didn't have to worry about metallic thread traces or insulation), but I cut all the wires assuming the velcro opening would be on the right side. Then I accidentally sewed the velcro on the LEFT side instead. Cue me trying to finagle everything to fit, which was extra fun because sherpa is REALLY hard to seam rip without accidentally ripping up the fabric or pulling out fuzz everywhere. Double-check your placement before you commit!


## Citations

- Teddy bear pattern: [https://www.howjoyful.com/howjoyful-bear-tutorial-and-pattern/](https://www.howjoyful.com/howjoyful-bear-tutorial-and-pattern/)
- Youtube video reference for sewing the teddy bear patterm: [https://www.youtube.com/watch?v=e_6qTxB1wQA](https://www.youtube.com/watch?v=e_6qTxB1wQA)
- LilyPad hookup guide for paper prototype components: [https://learn.sparkfun.com/tutorials/lilypad-light-sensor-v2-hookup-guide](https://learn.sparkfun.com/tutorials/lilypad-protosnap-plus-hookup-guide/all)
- Course lecture slides and POGIL activities (CSCI 103, Prof. Iris Howley)
