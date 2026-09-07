---
layout: post
title: An Introduction 
subtitle: 
tags: 
comments: false
mathjax: false
author: M Ferguson
---

### Quick facts: 
I am a senior math major (class of 2027) with a minor in Spanish. I'm from Lawrence Township, NJ, spend the summers working as a camp counselor and living with my grandparents in San Diego, and I studied abroad Spring 2026 in Buenos Aires, Argentina.  

### My (sewing/programming/Arduino) experience
I have some limited sewing experience, mostly embroidery and mending by hand (see figures 1-3 below) though I got ambitious last winter break and broke out the sewing machine to make a pencil case for my best friend's birthday (see fig. 4). I brought the sewing machine with me to school this year in anticipation for both this course and various project ideas I have (mostly sewing patches/things onto my clothes).  

![LEGO killer moth tote bag](https://ferguson628.github.io/assets/img/IMG_9463.jpeg) 
Figure 1. LEGO killer moth tote bag

![Mended corduroy pants](https://ferguson628.github.io/assets/img/IMG_8472.jpeg) 
Fig. 2. Mended corduroy pants

![Mended quarter-zip sweater](https://ferguson628.github.io/assets/img/IMG_9754.jpeg) 
Fig. 3. Mended quarter-zip sweater

![Pencil Case](https://ferguson628.github.io/assets/img/IMG_7770.jpeg) 
Fig. 4. Pencil case, made with sewing machine

 
your programming experience, your circuitry/Arduino experience, what you hope to learn in this class, and one boring fact about you.








**Here is some bold text**

## Here is a secondary heading

[This is a link to a different site](https://deanattali.com/) and [this is a link to a section inside this page](#local-urls).

Here's a table:

| Number | Next number | Previous number |
| :------ |:--- | :--- |
| Five | Six | Four |
| Ten | Eleven | Nine |
| Seven | Eight | Six |
| Two | Three | One |

You can use [MathJax](https://www.mathjax.org/) to write LaTeX expressions. For example:
When \\(a \ne 0\\), there are two solutions to \\(ax^2 + bx + c = 0\\) and they are $$x = {-b \pm \sqrt{b^2-4ac} \over 2a}.$$

How about a yummy crepe?

![Crepe](https://beautifuljekyll.com/assets/img/crepe.jpg)

It can also be centered!

![Crepe](https://beautifuljekyll.com/assets/img/crepe.jpg){: .mx-auto.d-block :}

Here's a code chunk:

~~~
var foo = function(x) {
  return(x + 5);
}
foo(3)
~~~

And here is the same code with syntax highlighting:

```javascript
var foo = function(x) {
  return(x + 5);
}
foo(3)
```

And here is the same code yet again but with line numbers:

{% highlight javascript linenos %}
var foo = function(x) {
  return(x + 5);
}
foo(3)
{% endhighlight %}

## Boxes
You can add notification, warning and error boxes like this:

### Notification

{: .box-note}
**Note:** This is a notification box.

### Warning

{: .box-warning}
**Warning:** This is a warning box.

### Error

{: .box-error}
**Error:** This is an error box.

## Local URLs in project sites {#local-urls}

When hosting a *project site* on GitHub Pages (for example, `https://USERNAME.github.io/MyProject`), URLs that begin with `/` and refer to local files may not work correctly due to how the root URL (`/`) is interpreted by GitHub Pages. You can read more about it [in the FAQ](https://beautifuljekyll.com/faq/#links-in-project-page). To demonstrate the issue, the following local image will be broken **if your site is a project site:**

![Crepe](/assets/img/crepe.jpg)

If the above image is broken, then you'll need to follow the instructions [in the FAQ](https://beautifuljekyll.com/faq/#links-in-project-page). Here is proof that it can be fixed:

![Crepe]({{ '/assets/img/crepe.jpg' | relative_url }})

<details markdown="1">
<summary>Click here!</summary>
Here you can see an **expandable** section
</details>
