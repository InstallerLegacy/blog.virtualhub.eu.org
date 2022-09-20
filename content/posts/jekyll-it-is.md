---
title: "Jekyll it is!"
date: 2022-08-12T17:55:00+05:30
draft: false
tags: ["old"]
categories: ["VirtualHub Blog"]
---

So, after testing [Wordpress](https://wordpress.org/), [CloudCannon](https://cloudcannon.com/) and [Publli](https://getpublii.com/), I have started using [Jekyll](https://jekyllrb.com/). As I have told you in the previous post, this blog is created using it.

## A bit about this Blog

This blog is a testing ground for me to check how well Jekyll performs according to my needs. Till now it has performed exceptionally well. So, how did I create this blog?

The first thing I would like to tell you is that I am using [Ubuntu](https://ubuntu.com/) (Default GNOME edition) now. So, I tried to search for how to install Jekyll on Ubuntu. Jekyll is built using [Ruby](https://www.ruby-lang.org/), so I needed to install Ruby first. Ruby came in form of a [snap](https://snapcraft.io/ruby), so I installed it. Why did I install the snap and not the [regular DEB version](https://packages.ubuntu.com/jammy/ruby-full)? I was not sure if Jekyll would be interesting enough for me. [Snaps](https://snapcraft.io/) are much easier to remove and purge from the system than DEB packages. So, I installed Ruby using snap.

But, the snap package did not work for me. It spilled an error when I tried to install Jekyll. I did not try to troubleshoot it. I did not want to invest too much time into Jekyll. So I then installed the DEB package. The installation went smoothly. I followed the [instructions](https://jekyllrb.com/docs/) from the official Jekyll website and all went well. I installed Jekyll successfully.

Then came the next phase - searching for an appropriate theme. I searched on various websites and tested several themes but none of the themes pleased me. If I found a theme that I liked, I found that it was abandoned and did not work now. At last, I came to this theme: [https://lanyon.getpoole.com/](https://lanyon.getpoole.com/)

This theme was not at all perfect for VirtualHub, but it gave me a new idea - the idea of this blog. So, I created this blog and after some time decided that Jekyll was useful enough to try to port VirtualHub into.

## Neo.VirtualHub

Once again I started to search for a theme suitable for the VirtualHub website. I tested a lot more themes. I then decided on [https://chirpy.cotes.page/](https://chirpy.cotes.page/). This theme has most of the features I needed including search, Dark Mode/Light Mode preference for viewers, Categories, and Tags Support. It just lacked one thing: the layout I wanted:

<br>

{{< image src="/images/2022/August/12/jekyll-it-is-1.webp" alt="VirtualHub Publii layout" >}}

But, I decided to live with that. I decided to use [giscus](https://giscus.app/) for the commenting system. I played with [staticman](https://staticman.net/) but decided not to use it.

That's all for today!
In the next post, I will tell you why I did not choose *insert_your_favourite_theme_here*.

Stay tuned!
