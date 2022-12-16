---
title: "Hello world."
collection: posts
permalink: /posts/hello-world
summary: 'Hello world! means more than hello.'
date: 2022-12-16
link:   /articles/hello-world.pdf
---

I recall "Hello world!" as the birth announcement for the Mac. It actually predates the Mac - it's [attributed](https://www.thesoftwareguild.com/blog/the-history-of-hello-world/) to Brian Kernighan . 
What's it for? If your program can render "Hello world", it works end to end. 
Per the Kernighan post, it's also that what's being rendered is also complex enough to excercise important functions. 
My first C program was probably a "hello world", over forty years ago. [K&R's "The C Programming Language"](/articles/hello-world.pdf) was the first technical book I really read. But I think of the Mac first.

I'm using this post as a tool for learning enough of Jekyll to post a series of pdf-based articles on a simple website. 
The raw posts have a little metadata - like a title and summary - and get aggregated from a folder of post entries into an index page (a "table of contents") of entries. 
Jekyll generates the index page and instances of the post pages. It uses a template to format structure the index page html and a different template for the post html.

In some cases, the posts might embed an image. Instances of posts are edited in [markdown](https://www.markdownguide.org/basic-syntax/). 
The markdown syntax is nice for a plain text editor and provides hints for generation of corresponding html. 
In my case, the posts link off to article .pdfs elsewhere on the site. 
I've been writing and editing articles in Word and rendering them to pdf. It would be interesting to see what markdown generated from Word looks like.

Jeykll seems very nice. Code generation has always seemed like a magic trick.
Around 2000, I wrote a static site generator in Perl, and then [Velocity](https://velocity.apache.org/), that used a site map specification and parameterized page templates to emitted a static site. 
It saved a lot of pain as we iterated on the site design and then grew the site. 
But, since then, I've ignored building websites, per se. I did spend a lot time designing interfaces for search. 
How much of software development is producing structured output over dynamic content - schema, bindings, iterators, and sinks? Rather, how much of software development is accommodating variation in source data?

Anyhow, the Jekyll quick and dirty pattern is find a [site](https://gdasoulas.github.io/) you like, fork its [base]( https://github.com/academicpages/academicpages.github.io) on git, and then tweak it to make your own variant. 
If your use case is clear, that's great. If you are poking around, or would like to understand more, I'd read the [docs](https://jekyllrb.com/docs/front-matter/) first.
