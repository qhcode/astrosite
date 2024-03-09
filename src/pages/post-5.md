---
title: 'My Fifth Blog Post'
pubDate: 2024-03-
description: 'This is the fifth post of my new Astro blog.'
author: 'Chris Adams'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'The full Astro logo.'
tags: ["astro", "blogging", "learning in public"]
---
# My First Blog Post

Published on: 2024-03-08

## What I've accomplished

1. Due to a certain passive paranoia, I've developed the habit of signing my commits as `Christopher Adams <fake@notreal.com>`.

Turns out that GitHub doesn't track contributions by the key used to push the commit - instead, it goes by email.

`fake@notreal.com` actually refers to a mysterious bot user named 'testingly' - which I didn't care to take credit for my hard-earned blog posts.

So I changed my defaults to my GitHib-provided email, `52187894+qhcode@users.noreply.github.com`.

StackOverflow-ing the answer yielded a rather.. lengthy git commit for this task:

`git rebase -i HEAD~N -x "git commit --amend --author 'Author Name <author.name@mail.example>' --no-edit"`

But wait! The root commit actually has this information too. That was something I added myself. Well - with another StackOverflow answer. But knowledge is power!

For personal projects, I can yak-shave *as much as I please*.

## What's next

I will finish the Astro tutorial, and then keep adding more posts. Watch this space for more to come.
