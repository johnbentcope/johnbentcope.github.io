---
layout: post
title:  "Getting Started"
date:   2024-06-15 13:07:12 -0400
categories: 
---

# Getting Started

I'm going to try this blogging thing.

## Learning Jekyll

This post was pretty manual to create. I figured out this is the date formatting string Jekyll wants:

`$ date +"%Y-%m-%d %H:%M:%S %z"`

## Learning p5.js

I figured out `canvas.parent('some_div_id')` and now my p5.js canvas doesn't just float in the middle of nowhere.

<div id="started"></div>
<script src="/media/started.js"></script>

## Automating Bad Commit Messages

I installed a global alias for git to automate writing poor quality commit messages.

`git config --global alias.yolo '!git add -A && git commit -m "$(curl --silent --fail https://whatthecommit.com/index.txt)" && git push'`