---
layout: post
title:  "Welcome to Graeme's Notebook!"
date:   2020-06-07 13:04:17 +0100
categories: nonfiction update
---

So, I'm making another attempt to start a blog.

I've had a few blogs in the past, and as much as I enjoy writing, they always end up dying off, either because of time constraints or whatever I was writing about finishing. And I fully expect this to happen here as well. That isn't the problem I'm setting out to solve.

The problem I'm setting out to solve is the storage and retrieval of the content after the fact. I've used a number of different platforms in the past - wordpress, drupal, blogger, and (sort of) mediawiki. They all work well enough, but when I finally get bored of the whole thing, and decide to tear it down, it's frustrating trying to retrieve the actual writing, independent of the website structure. The platforms in question all make a token effort at solving the problem, of course, using various exporter tools, but the end result is usually a complicated nested folder structure full of xml files scarcely any more accessible than just dumping out the CMS database.

This is where [Jekyll](https://jekyllrb.com/) comes in. Basically, Jekyll is a static site builder that takes in posts written in Markdown (a very friendly, readable markup language) and outputs a blog-style website that can be hosted statically (IE no backend processing or databases needed). I was originally planning to write my own static site builder - my old fractals website uses one I wrote in python sometime in 2014, and since then I've learned a lot, and the web has changed a lot. But one of the important lessons I've learned is not to reinvent the wheel without a good reason, and Jekyll seems like it meets my needs nicely. Most of the content I'm expecting to put here is prose, rather than images - the fractals website was initially an adhoc solution to the collection of fractal images I was hosting growing beyond what could be sensibly displayed using imagemagick's montage output. If I find I have an abundance of images to deal with, I might have to return to the custom approach, but it wouldn't surprise me if there's a way to make a gallery with Jekyll, and if not, I suppose I could probably write one. Ruby isn't a programming language I use routinely, but it's not a million miles from things like Python, which I know well, so I'm confident I could pick it up if I needed.

The bulk of what I put up here I expect to either be related to one of my various hobbies, or notes from one of my projects, but ultimately we'll see what we end up with...