---
layout: post
title:      "Distanc-r, an app to help with difficult times."
date:       2020-08-18 08:41:21 +0000
permalink:  distanc-r_an_app_to_help_with_difficult_times
---


I mentioned in my last post, I was working towards a more complicated project in Ruby On Rails, and I'm happy to say, It's my favourite work so far!!

Having moved straight on from Sinatra, I was concerned that RoR would be a tough learning curve. In some ways I was right, but all in all, the language was super fun to learn, and, although there were some tough points, I found myself thoroughly stoked with the idea of becoming a Ruby On Rails developer.

I decided to create an app that could help with our current situation in lockdown here in Australia.

I came up with Distanc-r when I went out for my first coffee in Melbourne, not long after the restrictions had eased. On a quick takeaway order, I had to provide my Name, Phone, Address along with my friends information who may be joining me. I thought to myself, there has to be a better way to do this right? And so the idea came to light.

Distanc-r would be designed to help make the process easier, while providing back-end stability for user data so they wouldn't have to provide their information up front to businesses.

I knew the app itself would become my final project at Flat-Iron, so I decided to build a strong back-end in ruby on rails, that I could then build on top of when it came to learning React and JS.

My first problems came with my user design. I wanted to have a user be able to add both a business account and an individual account on the same platform, without jumping between different accounts.

I played around a lot with various gems and eventually settled on Devise. I spent around a week just playing with different application scaffolds to give myself a concrete understanding of how i'd implement this within my program. Before long I felt excited and ready to start programming.

My solution to this was to add both Owner and Individual accounts to my application, that could be created and adjusted on a single User account for easy manipulation of businesses and checkins.

I was extremely happy that my previous learning in Sinatra, of model associations, was solid enough, that within next to no time I had my program built.

That was before I broke it... around 10 times.

It happens. I was using gems and ideas i'd never worked with before, so after a while I decided to stick with the basic structure and come back to more complicated things, like Omniauth, Active Storage and Bootstrap. When I felt comfortable the app was at a good level of functionality before I moved on.

And so I did, unfortunately it took me a loooooooonnngggg time to figure these out. Sure enough though, my project came together. And now Distancr is at a level that I'm happy enough with that I can move on to more Front-End frameworks.

Eventually in addition to this build, I'll also add Action-Mailer to inform people of possible Covid-19 infections and additional attributes/model relationships so the application itself can sing more to an enterprise market. But for now, I hope you like it as much as I do!

https://github.com/Dan-Cowpertwait/DistancrRoR

