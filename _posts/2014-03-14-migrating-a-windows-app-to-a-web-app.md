---
layout: post
title: Migrating a windows app to a web app part one
---


I have recently been given a project by a client to update a legacy system that I developed a good six to seven years ago. The App is a WinForms(VB.net/MS-SQL) project that was developed as an in-house CRM system specifically for the client. I’m quite nostalgic about the project, to say the least, as it was one of the first projects I worked on as a developer.

This is part one of a series of posts that I’m going to write that will log my journey to completely migrating this application to rails.

##Why?

Why am I doing this? The last upgrade the client asked for in December 2012 was to update the application to work with the latest version of Sage Accounts (2013 it was using 2008 before). At this point I didn’t even consider a Rails version (the idea was floating around in my head but it wasn’t fully formed yet). So these are the reasons for my Migration of the App:

- **Bloat** - The app has got to a stage where any change is a chore and its become very difficult to maintain. The app was initially developed to work with Windows XP. Things were different back then :)

- VB - I have moved from VB a cpl years after this app went live to C# and then to rails. I am going to migrate the app to rails so the framework is more modular. Currently its a single project.
- Me - I have gained considerable experience in more aspects of development such as UX and Front end (HTML,css,js,CoffeeScript) development along with enhancing my back end (C#, Ruby/Rails) skills I am far more confident in calling my self a Full Stack Web Developer
- Money - I want to develop this app to a point where I can offer the software to other clients as a SaaS application to generate additional revenue.
- Rails - Coming from a .net background when I first started working with rails it was and remains a breath of fresh air. Not only did I learn Ruby and the Rails framework it made me a better .net developer.

##The Process

This is an existing project and will be executed over a number of roll outs in an agile manner rather then as one big release (waterfall). I will be concentrating on migrating functions one by one from the winforms app to rails app as and when a change is requested by the client.

##Next Steps

I have recieved the first set of changes and will be posting them in a different post.

Stay tuned!

{% instagram %}
###{{ item.caption.text }} {{ item.date.text}}
![{{ item.caption.text }}]({{ item.images.standard_resolution.url }} "{{ item.caption.text }}") 
{% endinstagram %}