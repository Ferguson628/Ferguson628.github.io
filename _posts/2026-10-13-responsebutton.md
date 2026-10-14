---
layout: post
title: Response Button 
subtitle: 
tags: 
comments: false
mathjax: false
author: M Ferguson
---

### Assignment Description
This assignment asked us to write code which turns on a random LED on the Lilypad when a button is pressed, then off when it is released. Every time the button is pressed again, a different LED than the previous will light up.

### What I realized while doing this assignment
- A similar thing happened for a previous assignment, where I had wanted to practice nested conditionals (which we had just learned) and spent some time structuring my code that way before realizing how much simpler logical operators would be. This time my starting structure was a while loop (while (button == LOW)) before realizing I really just needed a couple if's, and the while loop was only necessary for guaranteeing a new random pin. So just remembering next time not to make my life more complicated and checking if there is a previous, simpler way we learned that might make my job easier.  
- I struggled a bit with figuring out at what point to set oldbutton to button and when to read in the new value to button (and similarly for old pin and pin). It all made more sense once I ditched the initial while loop. Ultimately, I updated the old button and read in the new button every time through the full loop, while updating the pins every time the button turned off.
- I kept forgetting and needing to check if the button was HIGH or LOW when it was pressed – and I confused myself more by using just alligator clips instead of our Lilypad button, which I think caused most of my confusion (I did remember from class that the button being pressed counterintuitively means LOW). I think my confusion came from not knowing whether button pressed (LOW) would be the same as alligator clips connected or disconnected. I should have just wrote it down to have for reference, because I confused myself several times with that. 
