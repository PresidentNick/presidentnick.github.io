---
layout: post
title:  "CS373 Fall 2015: Nicholas Pereira"
date:   2015-11-15 16:00:00
categories: swe week-twelve
---

Ok, so this blog post is not on time, but I've been extremely busy with all the end of the semester projects. I finally had some free time though
to catch up on all my missing blog posts at 35,000 feet on my way to Miami for Thanksgiving break. So this week professor Downing assigned us the last
project of the semester. Wow, how has time passed in this class! It feels like only yesterday that I was working on the collatz project. For the last phase
of the internet database project, the biggest task we have to complete is making our website searchable. I already have a general idea of how I'm going to
get that started since I took an intro course to elasticsearch when I attended Djangocon back in September. My teammates and I are discussing whether we
should use Elasticsearch or swift type to index our website. In our case though, Elasticsearch is better since swift type would take and extremely long time
to index all of our models and would also exhaust our api rate limit. So I took charge of implementing the search feature. I started up an instance of
Elasticsearch on our web serve and pointed all clients toward that instance to allow local development without having to install Elasticsearch on all of the
machines. The way we're indexing our models is pretty interesting too. Since we're not prepopulating our database and only dynamically loading it, we're
re-indexing our Elasticsearch cluster whenever a new model is loaded into the database. I think we did really well on time management this week.

###Tip of the week:
For several web application frameworks like Django or Flask, you can easily find boilerplate code on github to easily get you project up and running without
worrying too much about setup.