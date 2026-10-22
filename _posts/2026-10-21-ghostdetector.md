---
layout: post
title: ~Ghost Detector~
subtitle: 
tags: 
comments: false
mathjax: false
author: M Ferguson
---
For this assignment, we designed a ghost detector which reads in temperature and light values, then turns on the red LEDS when it is sufficiently cold and dark enough for a ghost to be around (and back off again when it is not). 

Here is a photo my setup when the ghost was detected:
![GHOST!](https://ferguson628.github.io/assets/img/ghostdetector.jpeg) 

My biggest tip to myself would be to test the light sensor with my phone flashlight rather than my desk lamp. I'm still not sure why, but the sensor would very inconsistently read the desk lamp correctly, even when it was held very close to the sensor. My light values would jump every couple seconds from values between 0 and 2 to values in the 900s. However, when I used my phone flashlight the sensor was able to read it perfectly. Still not sure why that was the case. But using the flashlight from the start would've saved me some time trying to figure out if there was something wrong with my code/sensor.  
