---
layout: post
title:  "Adventures in CSS"
date:   2016-11-06 17:41:37 +0000
---


CSS and HTML work together like PB and J. One really doesn't make sense without the other. CSS offers an elegant solution to the challenge of getting the aesthetics of the HTML code right. In other words, HTML is the markup language and CSS is the style sheet language. While you can have an internal stylesheet, in my opinion, the power of CSS is truly harnessed when, using an external stylesheet, you can change the style of an entire website by modifying just one file.
 
 I've used CSS to set colours, margins, padding, font sizes, alignment, weight and backgrounds among other styles, using element, id, class and attribute to select the HTML element. 
 
 As a humourous aside, my first attempts at selecting HTML elements in CSS was a bit like the Gary Larson cartoon below... inelegant to say the least! I'm sure many first time CSS users can relate.
![](http://66.media.tumblr.com/tumblr_lyiqu5VFK71qz6f4bo2_500.jpg)

In contrast to my first attempts, CSS best practice is to create meaningful markup that is scalable, descriptive and semantic. So while I can litter my code with a morrass of ids and classes, it quickly becomes unweildly and unreadable as the website grows. 

Other tips I picked up along the way:

* Use comments to improve readibility. For example, in the codealongs we were encouraged to include a comment on what a </div> tag was closing
* Separate words in ID and class names by a hyphen
* Don't use units for a 0 value. E.g. 0px is bad code. It should just say 0

Sources & References: https://google.github.io/styleguide/htmlcssguide.xml
http://www.htmldog.com/
https://developer.mozilla.org/en-US/

