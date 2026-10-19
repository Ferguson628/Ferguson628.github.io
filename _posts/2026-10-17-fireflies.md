---
layout: post
title: Simultaneous Fireflies, all together!
subtitle: 
tags: 
comments: false
mathjax: false
author: M Ferguson
---
For this project, we were instructed to combine (and revise, if needed) previous code we have written to light up different LEDS in patterns that mimic various fireflies. This round included LEDs in the style of the Big Dipper, Flash Bulb, and Blue Ghost fireflies, as well as the Synchronous firefly (for extra credit). 

Here is a photo of the LEDs around second 12:
![Lilypad with LEDs on](https://ferguson628.github.io/assets/img/fireflies.jpeg) 

What I found most helpful over the course of the project was taking advantage of serial printing to see if my variables were updating correctly and checking whether or not various if statements had run, et cetera. For example, as I was modifying my Big Dipper code to make the pattern non-linear, I realized that the reason it wasn't turning off was because I had an extra timing conditional in my if-loop that meant the reset to 0 was never triggered. Serial print was absolutely my most useful tool in fixing my code.
