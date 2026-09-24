---
layout: post
title: Half Inputs 
subtitle: 
tags: 
comments: false
mathjax: false
author: M Ferguson
---

### Description

This assignment asked us to write code which turns on various lights on the Lilypad depending on whether a "button" or "switch" are on (that is, whether two boolean variables representing a button and switch are true/false). I assigned colors to the combinations of on's and off's as follows:
  - If the button and switch are both on, then the yellow light turns on.
  - If the button is on and switch is off, then the red light turns on.
  - If the button is off and switch is on, then the green light turns on.
  - Finally, if both the button and switch are off, then the blue light turns on.


### Nested conditionals or logical operators?

To be honest, the reason I chose logical operators was because I first completed the assignment nested conditionals, but realized it would be much nicer with logical operators, so I took 5 minutes to change it over. I initially chose nested conditionals since I felt more comfortable with logical operators and figured I could use the practice with nested conditionals (and thought "then I also don't have to mess with all the and's and or's and not's"). 

However, after I finished it and saw that I ended up with six conditionals, nested and fairly complicated-looking, rather than the four I knew the logical operators would take, I decided to switch. I really love how elegant the conditions are this way, since only the first one needs the "&&", and the rest can take advantage of the fact that a boolean only has two possible values (one of which is remaining).

I left in, at the bottom and commented out, the first version I made. Let me know if in the future I should take something like that out, since I'm not sure if that's the kind of thing I would lose points for (that is, not removing excess code I didn't end up using). 


### Tip for next time
Next time I would remind myself to slow down, and fully think through (maybe even quickly sketch/draft) what both options might look like when there are multiple approaches I could take to code something




