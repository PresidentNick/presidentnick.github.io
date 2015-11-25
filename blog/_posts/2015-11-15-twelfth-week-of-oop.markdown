---
layout: post
title:  "CS31p Fall 2015: Nicholas Pereira"
date:   2015-11-15 16:00:00
categories: oop week-twelve
---

Ok, so this blog post is not on time, but I've been extremely busy with all the end of the semester projects. I finally had some free time though
to catch up on all my missing blog posts at 35,000 feet on my way to Miami for Thanksgiving break. So this week professor Downing assigned us the last
project of the semester. Wow, how has time passed in this class! It feels like only yesterday that I was working on the collatz project. For this last
project, we are supposed to write a Conway's game of life simulator. The premise is that there's grid full of cells that are either alive or dead. A live
cell will die if it has less than two neighbors because it is lonely. It will also die if there are more than three neighboring cells due to overcrowding and
competition for food. This version of the conway life grid is also going to be able to support Fredkin cells. These cells are similar to conway cells in
their behavior except that they also have a concept of age. Their age can only go up and not down. So the point of this project from what I see is to learn
how to implement abstract classes. There will be a generic Cell class that ConwayCell and FredkinCell will be children of. Thankfully I found a partner to work
with in this project. I partnered up with Barbara Kong, she is also taking software engineering like me and we're in the same software engineering team. So
it is really easy to coordinate times to meet since we both have the group meeting schedules. We started early and confidently. There are some issues we will
have to get through like not knowing how to convert Fredkin cells into Conway cells if the grid is supporting both at the same time, but we will figure it out
by going to office hours.

###Tip of the week:
For several web application frameworks like Django or Flask, you can easily find boilerplate code on github to easily get you project up and running without
worrying too much about setup.