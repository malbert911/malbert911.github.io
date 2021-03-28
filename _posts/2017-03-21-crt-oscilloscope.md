---
# Required front matter
layout: post # Posts should use the post layout
title: CRT to Oscilloscope # Post title
date: 2017-03-21 # Publish date in YYYY-MM-DD format

# Recommended front matter
tags: micro-electronics # A list of tags
splash_img_source: /assets/img/2017-03-21-crt-oscilloscope/crt-cover.jpg # Splash image source, high resolution images with an aspect ratio close to 4:3 recommended
splash_img_caption: DIY Oscilloscope # Splash image caption
---
For the most part, cathode ray tube displays are obsolete. Why not convert one to an oscilloscope?

I enjoyed looking at music visualizers and the partners they made. As such I wanted to try making my own.
The process itself was simple, open the TV and flip some wires. Only problem is that some of these wires can kill you.

The guide I followed was [this one.](https://www.instructables.com/How-To-Make-A-CRT-TV-Into-an-Oscilloscope/)

In summary:
* Vertical source (TV) goes to horizontal coil
* Horizontal source (TV) is unused
* External source (music) goes to vertical coil

Due to the TV being color, some minor modifications had to be made to get a better oscilloscope. At first it was only a single point moving. Since there was no picture being transmitted to the input, there was nothing coming out of the TV vertical source to feed the horizontal coils to make full lines. After plugging in a VHS player and turning it on, I started getting full lines. That is also why the lines are blue, it was the color of the VHS player pause screen.

This is by no means an accurate measuring device. It was a fun project to see the music I enjoy take a physical form.

![Animated sequence](/assets/img/2017-03-21-crt-oscilloscope/crt-gif.gif)
![Result with dimmed lights](/assets/img/2017-03-21-crt-oscilloscope/crt-darker.jpg)
