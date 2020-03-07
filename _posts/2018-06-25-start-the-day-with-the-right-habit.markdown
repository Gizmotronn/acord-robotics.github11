---
layout: post
title: HTML Dashboards
date: '2020-02-26 15:01:35 +0300'
image: architectui-html-bootstrap-dashboard.jpg
tags: Dashboard Social Network Websites
published: true
---
Dashboards are a very big project to undertake, but they're also something very important to AC0/RD. In this post, I'll talk about what dashboards are and how ours will work.

{% include jointcomments.html %}

# Contents
* [What are HTML Dashboards?](#what-are-html-dashboards)
* [HTML Dashboards vs CMS Dashboards](#html-dashboards-vs-cms-dashboards)


# What are HTML Dashboards
For developers coming from content management systems like Wordpress, Drupal & Joomla, the dashboard may sound like the "backend" of a website, and it commonly is, even with static site generators like Bootstrap. Bootstrap consists of a front-end, which is composed on html, css & javascript, and the individual files for that make up the site (which may be hosted on a service like Github). 

In the case of a CMS, the dashboard allows you to track & manage things like:

* Comments
* Blog posts
* User accounts
* Site performance
* Store sales
* App performance
* Survey results
* & more...

On wordpress, the dashboard is all set up and ready to go as soon as you install wordpress on your server/host. With bootstrap, it's a bit different.

> "A dashboard usually consists of graphical representations of the current status and trends within an organization.

You can use your dashboard to monitor the same things that a CMS dashboard can, but you have to set it up manually. This can mean a lot of work, especially if you aren't fluent with HTML, CSS & Javascript, but it can often work better. This is for a few reasons, which I'll explain in a moment.

Driving a car requires you to see a control panel, that way you find out about your speed, mileage, how much gas you have left. You can consider having a software business the same way: you need to know how every part is behaving and when you need to take action.

# HTML Dashboards vs CMS Dashboards
Let's use wordpress as an example when we're talking about dashboards built with a CMS. 

![](https://ps.w.org/slate-admin-theme/assets/screenshot-2.jpg?rev=988294)

For Wordpress, the dashboard is your hub, where by default everything gets done. Blog posts, surveys, email sign-ups and more are created, edited and deleted from the dashboard. In this case, the dashboard is less of a source of information and more of an administrative tool for your website.

However, when logging into a wordpress site, you (by default) get logged into the back-end - your dashboard (by default, it has the url *yoursiteurl.com*/wp-admin). 

![](https://mlqmtwka8c9g.i.optimole.com/gOh5_w-JlyUwvvr/w:320/h:208/q:85/dpr:2.6/https://www.competethemes.com/wp-content/uploads/2015/09/wordpress-admin-dashboard.png)

As you can see here, this part of the dashboard certainly looks more like an amalgamated set of information, reports, etc. In this example, the following is featured:

* **At A Glance** --> A quick stats widget, showing the posts, pages and comments count for your website
* **Activity** --> This widget shows the most recent blog posts published, and the most recent comments (it also shows comments that have been marked as "likely" spam)
* **Quick draft** --> Draft a blog post here with this widget
* **Wordpress news** --> Recent releases, news, etc 

Certain plugins add more widgets to this screen, and you can add/remove them at your leisure by clicking the "*screen options"* button at the top right of the screen.

HTML Admin dashboards, on the other hand, are static. This is to say that while they do display information, which should update (for example, an RSS feed of your comments), the dashboard itself is static. The dashboard serves as the front-end of your Bootstrap website - with Wordpress, it's the other way around.

Wordpress websites do not look like the dashboards shown above to visitors. They look like this:

![](https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcTljrDxM5Er4BhMsXov_whw1k7CY7QcjVfpSl1fBAtw8IjeDAVw)

This is because wordpress is composed of a **front-end** and a **back-end** of your site. The back-end is the administrative side, where only logged-in users can view it. This is how you create and manage content - we've already established this. For Bootstrap, while the dashboard can be set to log-in only, there is only one side, or part, of the site. The administrative work, and the viewing of the content gets done at the same time, on the same set of pages. You can actually set up a page on your wordpress (or CMS) site to display a dashboard like this:

![](https://s3.envato.com/files/259392478/architect-html.__large_preview.png)

However, the rules regarding front- and back-end still apply for sites built with CMS tools.
