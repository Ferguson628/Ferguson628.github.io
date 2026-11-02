---
layout: post
title: Analog Arrays
subtitle: 
tags: 
comments: false
mathjax: false
author: M Ferguson
---

For this assignment we wrote code which every 1 second selects a random PWM LED and, if it was off, turns it on at a random brightness, and if it was on, turns it off, using arrays to store pins and pin states.

Here is a photo of my set-up:
![PWMs set-up](https://ferguson628.github.io/assets/img/arrays.jpeg) 

My biggest tip to my past self would be that pin 10 not working correctly as a PWM is isn't because of something you're doing! In fact, it's an error in how the board was coded, and to get around it you have to setup pin 10 as normal, but write to pin 3 instead.
