---
layout: post
title: Bloctime
date: 2016-01-06
thumbnail-path: "img/balza_bloctime.png"
short-description: A Pomodoro-style time management app.

---

{:.center}
![]({{ site.baseurl }}/img/balza_bloctime.png)

## Introduction

The third in the projects I worked on during my Bloc frontend web developer apprenticeship, Bloctime is a time management app inspired by the Pomodoro technique. Work sessions are 25 minutes long, and are followed by a five-minute break. After completing four work sessions, users are prompted to take a longer, 30-minute break. Users can either input tasks and tick them off as they complete them or simply use the timer on its own.

As the previous projects that I worked on used Twitter Bootstrap, I decided to avoid Bootstrap in the creation of this app - mainly in order to further improve my CSS knowledge.

## Problems and solutions

In [Introducting Bloctime](https://brookebalza.wordpress.com/2015/11/23/introducting-bloctime/), I discuss the project's requirements and detail the user stories that I'll be working toward.

In [Bloctime: start and reset a work session](https://brookebalza.wordpress.com/2015/11/30/bloctime-start-and-reset-a-work-session/), I talk about creating a directive to handle the functions of the app's timer. I discuss how I got seconds to display as minutes:seconds, and how I control the starting and stopping of the timer.

[Bloctime: taking breaks](https://brookebalza.wordpress.com/2015/12/07/bloctime-taking-breaks/), looks at how I implemented the functionality that not only allowed the user to take breaks, but that also tracks how many work sessions a user has completed in order to prompt them to take a longer break after completing four work sessions.

## Conclusion

This was probably the most challenging project for me thus far, and I greatly enjoyed working on it. It introduced me to the concept of Angular constants, which I can see being hugely of benefit down the line. 

There's still a bit of functionality that I'd like to add eventually, including authenticated sign-in among others.