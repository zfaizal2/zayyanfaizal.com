---
title: “Perfect Form” Fitness App 
summary: a mobile application which provides instant, actionable feedback on squat technique with video input.
date: 2019-12-11
tags:
  - post
  - tech
  - software
  - fitness
  - sophomore
---

As a final project for one of my CS classes I took for fun, myself and two others built a form checking app as we learned about how software is built and learning different frameworks. This project was especially interesting as our team initially started with 8 people, though as time went on we ended up with only 3 as people dropped the course. 

Coming in to the project, our team had little to no experience building software so this was definitely a learning experience for all of us. We were ambitious in the beginning with feature ideas of competitive lifting, lifting partner matching, dynamic form checks for multiple excercises, and "gamifying" fitness. We defined the minimum viable product as having just one lift able to be evaluated.

What we finished with by December is a mobile app which takes a picture of a squat at the lowest point, and determined if the squat is low enough. Our team did this using the Tensorflow.js Pose Estimation library which provides joint location information given an image of a human. Though what we produced isn't functional in a practical fitness sense, this was a great proof-of-concept to show that something like this can actually work. The front-end of the application was built using React Native and we had a RESTful API with an Express server. 

This project served as inspiration for perform.

You can watch a video <a href="https://www.youtube.com/watch?v=TezZre2N8bg">here</a> about our project. 