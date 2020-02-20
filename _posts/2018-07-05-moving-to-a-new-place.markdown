---
layout: post
title: Constructing Social Networks
date: '2020-02-18 15:01:35 +0300'
image: social-networking-service.jpg
tags: Social-Network Construction Web Design
published: true
---

We're all on social media, and we're always on the lookout for groups around the interwebs that house people with similar interests to us. We comment on forum boards and say our thoughts in the replies of various blog posts, but what's the best way to make your own social network that is engaging and people will use?

{% include jointcomments.html %}

# Contents
* [Things you need](#things-a-social-network-needs)
* [Wordpress](#wordpress)
   * [Buddypress](#buddypress)
    	* [Plugins for Buddypress](#plugins-for-buddypress)
* [Bootstrap](#bootstrap)

Since 2016, I, and AC0/RD have used Wordpress (a content management system that incidentally is the software used for over 25% of the world's websites) for our social media. I never paid much attention to the comments system on Wordpress, because the main stuff happened on the forums, and I considered the comments section to just be for non-members posting comments on the blog posts (at the time, our website was entirely log-in only and that's why comments were not high up on the priority list for us). However, comments systems like Disqus can be used for a type of forum, and that's one of the things I'll be talking about in this post.

# Things a social network needs
Your website is a social network if it has any of the following types of user interaction:
* Games - for example web-based RPGs
* Comments sections - mainly used in blog posts
* Q&A Forums
* Support Forums
* Community Forums
* User profiles
* User gamification
* User groups 
* + more user stuff (check out something like Buddypress to see what you can do with membership sites!)

I'm going to over each of these in-depth over the course of this post. I'd also recommend checking out [my post on HTML dashboards](https://acord-robotics.github.io/acord-robotics.github11//2020/02/23/start-the-day-with-the-right-habit/ "HTML Dashboards") as it's a good way to get all the community traffic in one place.

> "Your dashboard is a great place to keep track of all the activity from your users

Most platforms that are used by developers can do most of the things mentioned above, but it can take a bit of fiddling around if you use a static site platform like Bootstrap, Jekyll or GoHugo. I'd recommend checking out [Codepen](http://codepen.io) for code snippets, which you can then modify yourself to fit your needs. If you're using Wordpress or another CMS, it's easy enough to set-up - just install a plugin like Buddypress or PeepSo. You do want to make sure that you don't have too many plugins installed on Wordpress, though, as it runs the risk of your site loading incredibly slowly (at our "peak", the AC0/RD website was taking upwards of 15 seconds to load)...

Let's take a look at the best platforms for creating a social network:

# Wordpress
![](https://www.wpexplorer.com/wp-content/uploads/wordpress-com-vs-org-infographic.png)
When we talk about Wordpress, we're talking about Wordpress.org, not wordpress.com - also known as the self-hosted version. I'm not going to explain the differences between Wordpress & Wordpress.com, but there's a great blog post that you should check out: https://ithemes.com/tutorials/wordpress-com-vs-wordpress-org/

Wordpress (.org) is extremely extensible, with over 50,000 plugins freely available on the Wordpress repository, and many thousands of companies that develop premium themes and plugins. One of the most popular, and most important, is Buddypress, which is actually developed by the Wordpress community (i.e. it is open-source). 

![](https://socialengineindia.com/blog/wp-content/uploads/2019/01/social-networking-service.jpg)

#### Buddypress
Buddypress is a plugin that adds the following features to your wordpress website:

* User profiles
* Friends (like on Facebook)
* User wall (status updates)
* Groups
* Private messaging between members
* Notifications

This is already quite good, but with the availability of plugins that *extend* buddypress, you'd be crazy to stop there. There's so much more that you can add:

* Integration with your forum --> BBPress
* User photo & video galleries --> RTMedia/Mediapress
* Completely customize & re-skin Buddypress --> Youzer by Kainelabs $$
* Buddypress User Blog --> Buddyboss $$
* Buddyforms Members (alternative to BUB above)
* Buddypress Global Search
* Woocommerce Buddypress Integration --> Woocommerce (E-Commerce)

![](https://blog.hubspot.com/hs-fs/hubfs/Imported_Blog_Media/BuddyPress-Global-Search-2.png?width=1300&height=900&name=BuddyPress-Global-Search-2.png)

###### Plugins for buddypress

Because Buddypress is open-source, anyone can update it and create their own plugins for it. This can be good, because as there are millions of PHP & Wordpress developers around the world, there's a huge chance that the plugin you're looking for to extend Buddypress (or any other part of your website, in fact) already exists. Even if it doesn't, you can always hire a developer to create a specific plugin for you, or learn how to do it yourself.

The downside to this is that a lot of these plugins are expensive, especially if you're starting out 




###### Image credit
* [Wordpress.org Infographic](https://www.wpexplorer.com/wp-content/uploads/wordpress-com-vs-org-infographic.png)
* [Cover art](https://socialengineindia.com/blog/wp-content/uploads/2019/01/social-networking-service.jpg)
* [Buddypress Global Search](https://blog.hubspot.com/hs-fs/hubfs/Imported_Blog_Media/BuddyPress-Global-Search-2.png?width=1300&height=900&name=BuddyPress-Global-Search-2.png)


