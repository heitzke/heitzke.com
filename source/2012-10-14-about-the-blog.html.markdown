---
title: About the Blog
date: 2012-10-14
tags: rails, compass, middleman, haml, scss, heroku
---
Well, seems that I've finally decided to add a little blog to the site. Noting that the current time is indeed 1:48 a.m. on a Saturday night (nerd alert, anyone?) the 'example article' that ships with the Middleman-blog setup isn't really cutting it. 

That being said I figured i'd write about the tech used to build & launch the little site. The framework is Middleman 3.0 with the associated middleman-blog extension. It's simply wonderful. It ships with compass & haml already rocking on it which makes me immensely happy. If you haven't working with either before, do yourself a huge favor and just do it. I primarily work in rails environments these days, so if you don't, you're screwed or something (maybe?).

Anyways, Middleman is wonderful for generating static sites while still allowing you to use the dev tools that you're used to utilizing. It's super flexible and allows you to pretty much do whatever you want. 

The site is currently on a free heroku server (Thanks Heroku, I love you and I promise I'll pay soon). Heroku is another fantastic tool to try out and use. Basically, jump on heroku.com, make a login and once you're in your local project folder, enter your credentials - 'heroku login', create a unique heroku project 'heroku create', and then BAM 'git push heroku master' and your code is now 'live'. I use the term live loosely, as it'll be deployed to 'blazing-dragon-flower-face-9872' or something similar. 

As you can see at the bottom of the blog post, I dropped in Disqus for comments (also insanely easy to integrate). 
