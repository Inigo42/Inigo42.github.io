---
layout: post
title: What blog solution should I use?
published: true
---

## What better thing to write about than what I have had on my mind from the last 24 hours?

Okay, so you want to write a blog. But your intellectual ego prevents you from going with something cookie-cutter or __too convenient__. What are you to do?

The journey is similar to finding the porridge that is just right. But, hopefully my experience can help illuminate a path.

### Coding your own blog software
#### (porridge is too cold)

If you're like me, your first idea will probably be just to write the actual code, from the bottom up, which I did... Having no web development experience at all... As you may guess the backend was a bit of a mess. And the frontend wasn't too modern either.

But, I learned quite a bit, having never done a project longer than 50 lines of code in Go until then. I did a couple of "interesting" things out of my lack of experience in the domain. For instance, instead of just using a regular sql database, I chose levelDB, which is a key-value database that exists on the drive. However, I still needed structured if not relational data, so I encoded an Article struct in json, and sent that to the database. It worked surprisingly well, and frankly I have no idea if that was clever, stupid, or regular practice with such a database. At any rate I learned a lot, but ended up with a blog software that would be a pain in the ass to use consistently.

If what you want is to write articles in a convenient, flexible, and nice blogging suite, this solution is probably not for you. No worries, it wasn't for me either, but the experience is definitely worthwhile if the end goal isn't to actually use the result.

### Using blogger
#### (porridge is too hot)

Again, if you're like me, using blogger will feel both crusty and overly controlling. While it's a great service and has a lot to offer, blogger felt too cookie-cutter. And though I could integrate some custom functionality and neat feature for private use through their API, it still didn't feel right for a tech-centric private blog.

I can very easily imagine myself setting up a blogger account in numerous scenarios, but this was not one of them. However, don't discount blogger as a potential option as it really is convenient and may serve your needs best.

### Using Medium
#### (porridge that I sadly did not try, but probably will in the future)

I think Medium is absolutely amazing. It has built a fantastic community, offers a great service, and excites me. However, I didn't feel that Medium was the best fit for a private blog, at least for me. I'm sure countless people use it as such, but I know Medium as the place where all of the cool write-ups and tutorials from experienced people live and that didn't quite fit my conception of a personal blog.

### Using github/jekyll
#### (porridge is just right, well, I hope it is, I mean that's what my research and experience suggest, but I probably don't know about other equally amazing solutions, you know it's fine, this article is not comprehensive or entirely conclusive, just read on and live your life)

I like github. I like scripting languages. I like markup. Seems like a match for me. Plus, since jekyll is written in Ruby, it should be very hackable (in the good sense). If you want to get started asap you can use [jekyll-now](https://github.com/barryclark/jekyll-now) (not sponsored). My experience with it has been great so far!





