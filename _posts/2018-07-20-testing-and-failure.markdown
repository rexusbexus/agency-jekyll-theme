---
title: Testing and Failure
subtitle: But that's what testing's for.
layout: default
date: 2018-07-20
pretty-date: July 20, 2018
img: testing-and-failure-back.jpg
thumbnail: testing-and-failure-front.jpg
author: Natalie Lawton
author-url: #

post-par1: So this week we finally got to test the pump in the vacuum chamber with the airflow sensor to try and find out exactly how the flow rate is changing at different altitudes. All we had to do was connect the airflow sensor to the arduino attach the pump to the airflow sensor and stick them in the vacuum chamber, easy right?
post-par2: Wrong. 
post-par3: From silly human errors like connecting the airflow sensor backwards and forgetting to uncover the pump inlet to software problems in getting the data back Wednesday's test ended in failure. While we were able to fix the human errors easily enough the software was a tougher cookie to crack. Luckily our software team is awesome and managed to produce a fix by Friday morning so we got to go again.
post-par4: Today we repeated the same tests as Wednesday with much better results. The only problem now is it appears that we have to few data points recorded. So, we can't call today a complete success either... This may sound bad but really its a good thing. This is why we test. To find out what our problems are and to fix them so they don't happen in flight. Our next plan is implementing a timer into the data logger and running the airflow sensor and pump for an extended time on the bench and see if we run into similar problems. But for now is time to stop writing blogposts and to get back to work ^-^
---
