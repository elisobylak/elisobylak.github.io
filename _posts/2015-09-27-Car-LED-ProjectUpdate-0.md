---
layout: post
title: First real post-Car LED update 0
---

So this is my first real post on my blog here, and I'm excited to start sharing various things I'm doing.
The first project I've decided to highlight is a cool project I am working on for another individual's car. And what it is, is a little LED matrix controlled via Arduino to flash a "Thanks" or "Sorry" signal in traffic to car behind it. I've collected most if not all of the pieces I'll need to complete this project. All I have to do now is put it all together. Below is a picture of the materials I've decided to go with for this project.
<img class="roundrect" src="/images/20150927_152936.jpg" height="400" width="550" >
<br>
Starting at the bottom, and going clockwise, you'll see my Arduino UNO on a prototyping board hooked up to a 4-segment LED display.

Next is the Power barrel charger and USB to Car charger I plan to use to power the Arduino and lights once in the car. It's just a 5V adapter with a 1 and 2.1A rating.

The next item is a knock-off UNO I bought off of Ebay for three dollars. The reasons I like this approach of prototyping on a genuine Arduino then switching to a knock off for production is two-fold. One, I like supporting good technologies and companies (buy an Arduino if you're interested. Two, I don't want to put a $20 component in a little side project, so once I know the set-up works on a real board, I can just swap the board for a more economical model. This project could even suffice with an Arduino mini, but I am most familiar with the UNO, so I decided to work with it.

The final two items in this picture are the two buttons that the driver will use to flash the pre-programmed signals. I've yet to figure out how these will be mounted for the driver to give them access when they need it. That will be in a later update.


The one remaining task I have to do is re-purchase the LED matrix. I ordered a 4-segment Max Matrix 7219 LED matrix and the segments came pre-attached. The only problem with this is, with the orientation of the matrices and the way the Max Matrix 7219 software library works, the text would only display 90 degrees to the orientation I'd like it to be. It can be seen in the picture below. 
<img class="roundrect" src="/images/10_2015-09-27.jpg" height="400" width="550" >
<br>
You can see in the third segment down, clearly that the letters are being displayed horizontally, where I'd like the to be scrolling down the matrix. To resolve this, I am planning to purchase 4 separate segments, use the 7219 Max Matrix library and just orient the LED matrices my self. 

I plan to give another update as soon as I make progress with this project, which will hopefully be very soon. School just started this week, so I'll try and find a nice balance between writing for this blog and doing my school work.