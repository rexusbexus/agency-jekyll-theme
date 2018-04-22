---
title: Peaking Inside
subtitle: The electrical innards
layout: default
date: 2018-22-10
pretty-date: April 22, 2018
img: peaking-inside.jpg
thumbnail: peaking-inside.jpg
author: Natalie Lawton
author-url: #

post-par1: Hej hej, good afternoon from the electronics team. Today lets tell you a little bit about the guts of the giant that is TUBULAR. With a current grand total of 17 sensors, 12 valves, two heaters, one pump and an Arduino Due this is one power hungry experiment. To make sure that we have enough power to last for the whole experiment and to also ensure we don't try and grab too much current all at once we came up with a couple of potential solutions.

post-par2: Solution 1 -> Mooooooooooooorrrrrrrrrrrrrrrrrre batteries. Solution 2 -> Find valves that take less power. Solution 3 -> Scrap the pump and send someone up on the gondola with a foot pump instead. Solution 4 -> Use SMPS to simultaneously step down the voltage and step up the current. Solution 5 -> Use sequencing of electrical components so that not everything is on at once.

post-par3: After swiftly disregarding solution 3 and not wanting the added complexity of solution 1 we decided to use a combination of solutions 2, 4 and 5. After pulling our hair out over valves for weeks we finally managed to track down a valve that doesn't have quite such a crazy power consumption and current draw. Then by having a maximum of two valves open at any one time and ensuring the pump and heaters are never on at the same time our calculations suggest that we will even have power to spare :D

post-par4: But what will we do with the left over power you ask? Well.. that’s classified ;)
---
