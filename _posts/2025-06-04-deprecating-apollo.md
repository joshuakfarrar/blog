---
title: "Deprecating Apollo"
layout: post
author: "Joshua K. Farrar"
categories: opinion
---

A few years ago I started working on Apollo, a web framework using Http4s, one that I wanted to open source to demonstrate my coding chops in Scala, and to the broader civic tech community. I think I was leaving my fellowship at Veterans Affairs, and I needed also to prove to myself that I could still write good, useful code. The result was a bit of a fail: I wrote pulled together an extremely barebones framework, I don't think anybody ever saw it, certainly nobody ever used it. Then I found a job, and basically forgot all about it. The truth is that I like to code, but, in my spare time, if the choice is between studying philosophy (I like to summarize philosophy papers) or foreign languages, or even playing video games, code just... takes a back seat. We have a little one now, and that's even more pressure on my reasonably scarce free time. That combined with the rise of companies using open source repositories to train LLMs to replace software engineers, and I just don't have it in me to offer up my code to the world, just so I can lose the career I love once someone does figure out how to get LLMs to reason well enough to manage the complexities of a large software project.

Protip: right now, they cannot.

All this leads to today, where I have archived the old [Apollo](https://github.com/joshuakfarrar/apollo) repository.

But all is not lost! A pheonix rises from the ashes!

Just as an exercise in productivity measurement, I have begun to earmark for myself 1 hour per day to write code. Plus, I have some ideas that I think could greatly contribute to the larger Scala and Http4s, Cats, TypeLevel communities, and make it easier for people who want to start building purely functional web applications do so, even if they haven't internalized all of the functional programming necessary to do so. That is, I am announcing that I have begun work on Apollo 2.0.

One of the very best libraries in the Ruby on Rails communities is Devise: if you are building a web application, chances are that you need, sooner or later, to set up authentication and authorization, and sessions. Devise makes this easy: you add a Gem to your Gemfile, `bundle install`, wire up some routes and you're pretty much good to go. Instead of perhaps weeks to develop these features from scratch, you can get them working in a weekend, and turn your attention back to what you actually probably care about, solving some problem for yourself or your customers.

The Http4s and wider Scala ecosystem doesn't really have anything like it. When I started working on Apollo 2.0, I knew that I didn't really want to just slap ScalaJS onto an otherwise static website and consider myself having accomplished my goal. What I want for Apollo 2 are the basic features that will allow me to write full-stack Scala applications for my customers. I really like the Scala programming language, but the thing that keeps me coming back, time and again, to the Ruby on Rails, Node, and Spring ecosystems is the lack of good, purpose-built tooling for the Scala ecosystem. That isn't to say no tooling exists: Http4s is an absolutely incredible web framework, Doobie works well, etc., but for full-stack application development, there's simply a lot left to be desired simply for convenience sake. Nobody wants to pay software engineers to re-invent the wheel for what is otherwise commoditized code.

Oh, and over my years of writing Java, I've occasionally slipped into writing Scala for fun, and I think I'm a lot better now than I was then. At the very least, I have learned a lot about the right ways to handle computable functions that may fail, and might not return anything. And for the problems I'm paid to solve, that matters a lot.

More soon.

¡Chau!