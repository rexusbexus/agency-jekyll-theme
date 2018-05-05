---
title: Unit Testing
subtitle:  Finding your logic errors ASAP
layout: default
date: 2018-05-05
pretty-date: Mei 5, 2018
img: lets-be-specialist.png
thumbnail: uunit-test.png
author: Muhammad Ansyar Rafi Putra
author-url: #

post-par1: Hello everyone! Ansyar is here~. From the last post, I promise to share my unit testing experience. The first time i heard about unit test was 3 weeks ago. Our PM told us, software team, to use unit test to catch any logic mistake early. Then, I began studying unit test. It took a couple of days to understand the basic. After that, i learned that it's not possible to apply unit test by using Arduino official IDE, this is the reason why we are using PlatformIO now.
post-par2: Important thing before unit test, your code has to be unit test-able. That means the code cannot have only one main function, instead split it into several test-able functions. After splitting the functions, i tried to build the test cases, then i realized another obstacle. In PlatformIO, there are two types of unit tests, first one is unit test for the whole code (note that any arduino code is hardware dependent), second one is non-hardaware dependent unit test for C/C++ using unity library. The hardware dependent function has to be uploaded to the board before testing it, but the normal one doesn't. 
post-par3: For now, we have two unit tests for non-hardware dependent functions. In my opinion, unit test is an awesome tool. I used it to test the command reception function, testing if the software can receive the telecommand properly. Then, I found that my function had one logic mistake that cause the whole code to crumble and the code was compile-errors free. Then I realized, no compile errors doesn't mean your code is working. Yes, that's it for today. Have a nice weekend peeps!!

---
