---
title: How I integrated 11ty with Notes.
description: This is a post on My Blog about integration of 11ty with notes.
date: 2021-11-02
tags:
  - another-tag
layout: layouts/post.njk
---
I took the base blog starter of 11ty where the blog section is already created. I followed the following steps:
	- I forked the Eleventy-base-blog
	- I deployed it on Netlify
	- For integration of notes, I created a notes.njk whose navigation order, I created at order 4
	- I deleted a section of markdown preview at bottom of .eleventy.js file so taht wiki links can work
	- I added custom code to .eleventy.js file for notes and backlinks to work
	- I added a few dependencies in package.json file
	- I added a template for notes section inside layouts folder called notesTempl.md
	- I added a notes folder which contains all my notes and changed layout in js file in that folder to notesTempl
	- Voila, it started working
	
## Learning Process

It actually depends on the fun, the interaction and acceptance of the fact that I don't know shit. Only when I accepted it that I seriously don't know anything, I was not afraid of losing or to fail because I am anyways starting at 0. What can I lose actually? I can only stand to gain from the process and I did learn and I am still learning by following the process of accepting that I don't know; let's start from scratch and explore and document so that I don't come back and cycle in loops. Interesting process isn't it?

![My blog](/img/5.jpg)
