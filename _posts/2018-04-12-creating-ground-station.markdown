---
title: Designing Ground Station
subtitle: how to connect to your experiment
layout: default
date: 2018-04-12
pretty-date: April 12, 2018
img: creating-ground-station.png
thumbnail: creating-ground-station.png
author: Muhammad Ansyar Rafi Putra
author-url: #

post-par1: Hej peeps, I am Ansyar from the software department. Today, I would like to share my experience creating ground station for tubular experiment. The first thing that should be considered is in what platform the ground station will be. We chose matlab-GUI, because it is simple and easy to implement. The second thing is what the experiment needs. For instance, in tubular, we need telecommand control panel, telemetry data panel, status panel, and connection control panel. Next step, placing the panel. I suggest that the panel for data viewer is on the upper left side of the interface, because we usually read things from upper left of the screen. Then the status panel on the right side, and any input panel on the bottom side of the interface. This would make the interface easier to read and user friendly. Ah, one more thing, if possible, put tool-tips for each elements on the interface. The tool-tips should contain brief explanation about the function of the elements.

post-par2: The most important thing is make your design user friendly and interesting. Put some colors and interactive function. For instance, in tubular ground station, we will have a graph that shows the real time altitude of the experiments which will give us reassurance about the experiment conditions.
---
