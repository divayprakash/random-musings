---
layout: 	post
title: 		Small updates
date: 		2020-03-09 17:31 +0530
categories: [blogging]
tags: 		[enhancement]
---

How does it happen that simple things always manage to take up so much time? I don't have the first clue, but I know it's true. It's happened to me too much for me to not believe in it.

Anyhow, I've been working on a few things for the blog. Started working yesterday evening around 6PM and making some small changes -

* Darkened the background color - it's now [#111111](https://www.colorhexa.com/111111) instead of [#15171d](https://www.colorhexa.com/15171d).
* Made an effort to speed up the deployment process by having the script create a shallow clone of the `random-musings-deploy` repo. Doesn't really seem to be making much of a difference for now, but I'll look into this later.
* Removed masthead from all pages except the index page - This one has really been bugging me for a long time. I just could not for the life of me figure out why it made sense to have the masthead on all the pages. So I removed it! This also allowed me to simplify the `masthead.md` `_includes` file a bunch.
* Customized masthead - I didn't like that the blog title was smaller than the post titles below it. Fixed that and also used a custom font.
* Colourize output of deploy script - Just did this for fun.

<figure class="align-center">
    <img src="{{ '/assets/img/cool.gif' | relative_url }}">
    <figcaption>Cool, right?</figcaption>
</figure>
