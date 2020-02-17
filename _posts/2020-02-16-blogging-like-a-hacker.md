---
layout: 	post
title: 		Blogging like a hacker
date: 		2020-02-16 01:06 +0530
categories:	introspect
tags:		[blogging, exploration]
last_modified_at : 2020-02-17 17:44 +0530
---

Let me just start off by saying that this post is (heavily) inspired by (or, creatively plagiarized from) Tom Preston-Werner's [original](https://tom.preston-werner.com/2008/11/17/blogging-like-a-hacker.html) from 2008.

So, with the disclaimer out of the way, let's begin.

I've been toying with the idea of setting up a blog for over 5 years now, almost since the time I began my engineering studies. Right from my first exposure to coding and creating something of my own, I wanted to document my experiences, more so for myself than for anyone else, which is how my feelings towards a blog remain to this day. I agree I write in a conversational manner like I am addressing a reader, but that just makes it easy for me. And also, I do love writing. I enjoy putting my thoughts to paper, or the digital word here. It sometimes feels almost like a release, like there are so many thoughts running amok in my mind that it's easier to just spew them all out in one single place rather that try and control the flow in any way, shape, or form. And that's why I make so many typos when I'm composing a blog post, requiring me to use aggressive spell checks and even proof-reads to actually obtain something not resembling absolute garbage.

But as much as I enjoy this writing gig, I seem to be stuck in an endless loop of quitting and starting all over again. I do fancy myself to be somewhat of an aesthete, and having knowledge of programming and web development, I'm well equipped to tinker with the innards of technical solutions for blogging. Which is how it starts, I'd see a nice blog, good layout, interesting design, and off I'd go down the rabbit hole, exploring Wordpress, or Blogger, or Jekyll, or Hugo, or Ghost, or whatever else it was that managed to tickle my fancy. I'd keep at it for a few days but ultimately give up, convinced I didn't have the necessary time to waste or some equally lame excuse. But this time, I kept at it with a firm resolve to introspect and really find what exactly led me into this destructive pattern.

What I found was this - complication and/or over-simplification. Let me explain.

I have a feature set in mind when I set out to create a blog; attractive modern design, good typography, customization options - both in design and functionality, category and tag support, built-in SEO and overall ease of use. But it isn't easy for me to find all of these things in any one stack or solution. My first blog adventure started with Blogger, but I quickly lost interest owing to the limited customization options and just general old-world feel. Next came Wordpress, which took way too long to setup the way I liked it and even then wasn't a good solution at the best of times. Slow loading webpages, lack of content ownership, complex structure and technical stack; and all for a simple blog.

I finally settled on a static site using a generator such as Jekyll, or Hugo, or Ghost. However, this came with its own challenges, namely smaller developer communities and the possibility of running into issues that would be beyond me. Even choosing the most popular of the three, Jekyll, I had to contend with themes that did not fit my specific requirements even after some amount of effort on my part.

Starting with Rohan Chandra's [Type Theme](https://github.com/rohanchandra/type-theme), I added tag and category support and made various visual changes to the blog format, ultimately giving it up in favour of John Otander's [Pixyll](https://github.com/johno/pixyll). This is where I am at the moment.

However, even after all this exploration - wading through the murky waters of PHP, Apache, SQL, Ruby, Textile, Liquid, and god-knows-what else, I still am not 100% satisfied. Before I go any further, one clarification I have to make is that I am not trying to throw shade on the work of either Rohan or John's projects, both of which helped me improve my skills in using Jekyll. Something is still holding me back and I find myself digging through the code much more often than actually writing out posts. Which made me realize that (I am a bit of a freak), I am a perfectionist, and I'll not be pleased until something suits me perfectly (and the only till my definition of perfection changes!). So here I am, looking for a change again, exploring Michael Rose's [So Simple Jekyll Theme](https://mmistakes.github.io/so-simple-theme/) at 1 AM.

This moment of astounding clarity led me to type out this post, which I think is my longest till now (and by some margin). Just to record how totally and completely ass-backwards one can get sometimes!

<figure class="align-center">
  <img src="{{ '/assets/img/here-we-go.jpg' | relative_url }}">
  <figcaption>Cheers to sleepless nights and endless explorations!</figcaption>
</figure>

***Update*** : Just to clarify the title - blogging like a "hacker" :man_technologist: - The title is just a reference to the fact the through the journey of setting up my blog, I realised that whatever else I may be, a coder I definitely am! I wasn't satisfied with the built solutions offered by Wordpress or Blogger, and just had to create something I could understand inside and out. And also, seamless updates with Ruby Gem-based themes rock :metal:!
