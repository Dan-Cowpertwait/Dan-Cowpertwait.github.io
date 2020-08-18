---
layout: post
title:      "The makings of a software developer, through Sinatra!"
date:       2020-08-18 08:42:16 +0000
permalink:  the_makings_of_a_software_developer_through_sinatra
---


When I was deciding on my Ruby Sinatra project, I decided to go for something fun, before really tackling a real world application. I knew I could build it on the basis of something mundane, like my love for time management.

But, along as a hobbyist in UX/UI and Graphic Design, I really wanted to make a program that was not only visually appealing, but also mentally. That's when I came up with Pointlessly Philosophical Pot Plants.

The idea was to build a program that I could practice my design skills alongside my new found coding knowledge.

Building the application was challenging at first, but due to the awesome course material at Flatiron I found myself breezing through the standard CRUD actions for my controllers and models. Tasks, Quotes and Plants were all working smoothly alongside the User login system which I'd built with careful consideration alongside the course content.

My first trouble began with the logic of the models interaction. I suddenly realised that my idea had been a tad overzealous, I felt completely baffled how I intended to use the Tasks to call Quotes which would then water and grow the plant with matching imagery.

By the time I got it working I must have closed about 100 stack overflow tabs, but sure enough, I had a Pot-plant that quoted, grew and changed according to user interaction. After this I had heaps of fun creating the graphics for the application, making an aesthetically pleasing user interface with some help from W3's CSS resources. I also learnt to animate for the first time, how about that!

My worst problem however, was still to come. I'd continued committing and pushing branches to my repository for some time, though my understanding of GitHub was pretty loose. I then made a fatal error with my database. For some reason Rake refused to drop tables and I not only lost my migrations, but had persisting information that I couldn't get rid of for the life of me! (I'll ask my reviewer about this when I present my project)

I thought, "Hey, if I can rollback to an earlier GitHub commit, I may be able to retrieve my old db's".

Sounded great. Terrible idea. I accidentally reverted to the original Head of my repository, deleting all my previous data and reverting to my second commit.


Luckily, with extensive experience in design, I'd known to make local backups, which were decent enough that I could recover most of my work. Unfortunately this had disheartened me to such an extent I finished building the functionality I needed and moved on, to return to the project at a later date, when I wanted to build a current portfolio for my graduation.

Now, months later, I returned, having been close to the end of the curriculum. I was pretty happy that when I did, I found myself still familiar with Sinatra code! This actually made me really happy. I knew I'd need to be able to switch between frameworks in the real world, so it was nice to realise I had the knack for it.

I touched it up and prepared to submit for review, unfortunately I realised GitHub commits were actually part of the project and I'd screwed that up royally.

One of Flatiron's value's is "be scrappy". So I suppose I was being just that. I learnt a valuable lesson about working with repositories that I'm bound to never, ever, make again. As I'd already begun work on my Ruby on Rails project by the time i'd come back to Pointlessly Philosophical Pot Plants, I'd learnt and implemented my now strongly built knowledge around GitHub and it's repositories, which will be seen in my new application Distanc-r, To be covered in my next blog post.

On to Ruby on Rails!!!
