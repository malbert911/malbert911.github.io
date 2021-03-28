---
# Required front matter
layout: post # Posts should use the post layout
title: Thomas Daft Punk Helmet  # Post title
date: 2019-10-30 # Publish date in YYYY-MM-DD format

# Recommended front matter
tags: 3D-Printing micro-electronics programming # A list of tags
splash_img_source: /assets/img/2019-10-30-daft-punk-helmet/daft-punk-parking.jpg # Splash image source, high resolution images with an aspect ratio close to 4:3 recommended
splash_img_caption: Halloween 2019 # Splash image caption
---

It had been two years since my last major 3D printing project, and I had much bigger ambitions this time. I decided on recreating Thomas Bangalter’s helmet from Daft Punk.

# Printing
I opted to use an already proven model, but design my own electronics. The model I ended up using was [this one.](https://www.thingiverse.com/thing:338831) 
The model itself was very accurate. However, it was divided into several small pieces intended for smaller printers. More time in the assembly was required.

# Assembly
Each section of the helmet is held against each other with zip-ties and 2-part epoxy glue. This part was tedious and messy, but the result was strong and solid.

![Helmet Assembly](/assets/img/2019-10-30-daft-punk-helmet/daft-punk-printing.jpg)

# Electronics
While looking at other renditions of this helmet, many people either build their own LED matrix diode by diode or used LED strips. I wanted to be somewhere in-between and used 8x8 MAX7219 LED matrices. I ordered 8 and planned to use all 8. Due to my weaker soldering skills at the time, I killed 4 of those 8 modules. The front matrix was going to be 8x32 pixels as a result. The ear cups on the side are strips of WS2812 individually addressable LEDs. 

<embed src="/assets/img/2019-10-30-daft-punk-helmet/scrolling-text.mp4" autostart="false" height="200" width="200"/>


The ear LEDs go through a pre-defined loop of effects that I programmed. The matrix is controllable from a phone using a HC05 Bluetooth module that then relays the text via serial to the Arduino.
The library used for the text animations/transitions is [MD_MAX72XX](https://majicdesigns.github.io/MD_MAX72XX/)

![Helmet Electronics](/assets/img/2019-10-30-daft-punk-helmet/daft-punk-electronics.jpg)

# Finishing
To smooth out the printing lines, I experimented using Bondo Filler. Usually used in automotive, it allowed me to fill the gaps and then sand the excess Bondo off. While it was miles better than just sanding the plastic directly, it was quite difficult to work with. I only got the hang of the proper mixture amount and spreading techniques when I was done. I would still use it again if needed for some other project.

![Helmet Finishing](/assets/img/2019-10-30-daft-punk-helmet/daft-punk-bondo.jpg)

# Final Result

![Helmet Final](/assets/img/2019-10-30-daft-punk-helmet/daft-punk-hallway.jpg)
![Helmet Final](/assets/img/2019-10-30-daft-punk-helmet/daft-punk-parking.jpg)