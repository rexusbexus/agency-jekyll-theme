---
title: Bug hunting
subtitle: ...
layout: default
date: 2018-05-27
pretty-date: May 27, 2018
img: bug-hunting.jpg
thumbnail: bug-hunting.jpg
author: Gustav Dyrssen
author-url: #

post-par1:TUB.. Kiruna do you copy?
post-par2:Kiruna.. Yes TUB we copy you.
post-par3:TUB.. It's beatiful, they.. they should have sent a poet.

post-par4:I can hardly describe my feeling when we at TUBULAR software team managed to get the groundstation to display the simulated data from the Arduino. A huge milestone have been achieved. We spent a long time bug hunting the other day trying to find the bugs that stood in our way. We discovered that the way we displayed the red and green lights that indicated the status of the valves, pumps and heaters would take a couple of seconds to properly update. Meaning if we would have sampling rate higher than say 0.2Hz the groundstation would be busy updating the GUI while new data would come in before it was finished and interrupt occured. Luckly there where easier and faster ways of displaying the pictures. 

post-par5:There where other minor bugs in the groundstation that was fixed. We also found an intresting bug regarding the OSW. We had simulation data that the Arduino transnitted. Everything looked good until it went into Normal mode-Ascent. Then it entered safemode. This was one hard bug to find. First we thought it might be un the heater object, but that was ruled out. It was a function that the heater object called that caused problems. getMode(). The getmode is very simple funcion an no error was appearan't so we where at at loss. 

post-par6:The we realised it used semphores and the error must lay in there. We checked when was the getmode() took and released its semaphore before the error occured. It was then we found it. It was in the sampling logic that took a semaphore and never let it go, just as we would never let go of our hunt for the bug. The fault laid in that that the line of code resonsable for releasing the semaphore had found it's way on the wrong side of a curly boy }. With this bug gone we would finally transmit data from the Arduino to the groundstation during the entire simulation. Not bad for a days work.
---
