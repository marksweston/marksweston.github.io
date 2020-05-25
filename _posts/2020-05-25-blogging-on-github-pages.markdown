---
layout: post
title:  "Blogging on Github Pages"
date:   2020-05-25 19:10:00 +0100
categories: blogging meta
---
I've been blocked on this for months.  It's absurd.

Yes, Github Pages is fundamentally simple.  Upload a static site into the right repository, with the right settings, and let Github do the rest.

But I want a blog, while not wanting to build it from scratch.  I want a nice theme that I enjoy looking at.  It therefore seems obvious that I need to use Jekyll and build on Github's automation of the Jekyll workflow.  But that means I need to choose a theme...

There are lots, of course.  First I find a theme that I like the look of, but it's for Jekyll 4.0.  It turns out that the github-pages gem that I added to my Jekyll project has a hard dependency on Jekyll 3.8.  And there's no sign of an early upgrade, because Github has compatibility worries about existing sites.

It turns out there are plenty more that expect a custom install process rather than using ruby gems, or that haven't been tested with Github Pages.  It seems to be a rule of the universe that all the themes I like have one or more of these problems.

So, three months later, I don't have a working blog because I couldn't choose a theme.

The next time I get all worked up about delivering fast, then iterating.  Or "make it work **then** make it right"; someone just slap me.


