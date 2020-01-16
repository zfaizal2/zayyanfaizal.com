---
title: CS 125 Office Hours Queuing App
summary: a queueing system matching students seeking assistance during office hours with next available CA/TA to solve problem of understaffed office hours. 
date: 2019-05-01
tags:
  - post
  - tech
  - freshman
---

For the final project of my CS 125 class, my friend and I decided to solve the problem of overcrowded office hours, especially during MP due dates. Students are often frustrated by spending lots of time during office hours waiting for their hand to be recognized by the few TAs and CAs in the room. Our solution was a mobile application which puts students in a queue for the next available TA on a first-come, first-serve basis. 

For a student, simply open the app and put your name in. A message will appear showing that your name is in the queue and will be matched with the next TA. TAs and CAs login to the app to verify non-student status and will automatically start being matched with students. The TA/CA will announce the name of the student and the student will identify themselves. Once a TA/CA needs to leave, they can log out to stop the matching. 

Our team used Java and Android Studio for the app development and a Firebase database to keep track of the queue. You can watch a video <a href="https://www.youtube.com/watch?v=wywXk4gEV3A&t=6s">here</a> for a more detailed explanation. 