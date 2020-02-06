---
layout: post
title: Repository of knowledge
date: '2020-02-03 15:01:35 +0300'
image: Screen-Shot-2018-02-28-at-2.50.11-PM.jpg
tags: repository
published: true
---
Every company needs to have a good knowledge base, especially software start-ups. In a traditional office job, a new employee may be given a tour of the venue they will be spending their days in, as well as given information via word-of-mouth about what work they will be doing. Work shadowing may be done for the first few weeks as well.

In a lot of software start-ups, things are very different. A lot of companies that deal with software engineering have most of their employees working from home, rather than working in an office. There are also a lot of jobs that need to be done. If you worked in an office, your job may be to pull in data from external sources, categorize it and write a report on it (this is a bit of what my dad does, actually). When you're a software developer, you'll be working with systems like git and applications like visual studio. 

Traditional office-based jobs are very static. What I mean by this is that you may be using an application for your work, however your day-to-day work will be very much the same. Project management tools and version control systems are not usually needed.

This is why, when a tech company starts up, they need to have a dedicated knowledge base so that everyone knows how the system works. For example, at ACORD, we have a number of websites, all of which are used and maintained by our developers. We use applications like visual studio code, discord, slack, outline, notion, and online applications like GSuite, Office, Github, & Zenhub. The current way that all this works together is very complicated, and while we are working on trimming it down and cutting the fat out of it, even perfect systems need some sort of knowledge base for new members/employees.

There are a number of online tools like Gitbook, Notion, and even plugins for CMSs like Wordpress & Drupal. However, you don't want to have too many plugins on a CMS site in the interests of good loading time (especially if you live in Australia, our internet is horrible). Having multiple websites can be a bad thing if you have to log into multiple sites (like you **currently** have to on ACORD), however if you make your knowledge base public it's not as bad (especially if you use iframe elements to embed all your sites together, like we do). Another solution is Wordpress Multisite, where you have multiple sites on one installation. This means that all the users sync across (avoiding the multiple login problem), however each site can have different plugins. 

In the interests of open-source-ness, and simplicity, I'll be using a git-based solution for our knowledge base, however it is easy to transfer the content between different systems if we choose to do so in the future. 

# The best solutions
## Gitbook
Gitbook's tagline is "Document Everything", and with the sleek and intuitive user interface that you're presented with, it's hard not to. Gitbook makes writing documentation (which is something that I find fun, but a lot of other programmers don't) fun and easy, and it integrates well with existing github repositories. 

You can choose to either push or pull commits/files from or to Github with Gitbook - what this means is that you can choose to connect your gitbook base to a github repository of your choosing, and you can either edit the files in your knowledge base (which are in markdown format) in github or on the gitbook dashboard.

## Custom Bootstrap Themes
Github pages is a great way to host static sites made from generators like Jekyll & GoHugo, but by far one of the best and most extensive is Bootstrap, which uses a combination of HTML, CSS & Javascript to help you create stunning websites and webpages. Millions of people around the world use Bootstrap (including us at ACoRD), and therefore you'd be expecting that there's many themes to choose from. And there are! Sites like themeforest, which are well known for their website development tools and assets, have thousands of bootstrap themes developed by professional developers around the world. Sites like bootstrapmade.com & Material Design Bootstrap both have tutorials on creating your own themes and if you are just wanting to try Bootstrap out without paying anything, don't worry - more than half the themes currently in circulation on the interwebs are free! 

Since Bootstrap is 
