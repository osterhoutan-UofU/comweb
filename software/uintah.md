---
#(don't forget to change file name to software id)
# Modify these:
id: uintah
title: The Uintah Software
author: "Andrew the dev/tester"
date: 2020-01-01
published: true   # toggle between true and false if you want to hide post
tags: [software, uintah, test-tag, bob101]
# Don't modify these:
layout: info-post
permalink: software/:basename #:output_ext
category: software
info_type: software
---

{{ site["pages"] | inspect }}

{{ page.url }}

### Test Title

test content

this allows for limmited multimedia support, and you will need to either know how to use jekyll or link it with absolute URI from an external source to get it to work.
The later is recomended fo rmost people. 

gobldey gook

test image w/ jekyll liquid comments (image is in the `/site-src/images` directory already)

![test-image]({{ "/images/DecidabilityDiagram.png" | absolute_url }})


test image w/ external media:

![Test-Image-2](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSXqq3j05ykEU69GBIwyuuuiFhePdmiIIk3zMJ6gfim7Sv3yaJ0v86GjGf4_W9P-BqgHjA&usqp=CAU)


that is all for now

