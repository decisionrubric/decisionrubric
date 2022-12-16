---
title: "Hello world."
collection: posts
permalink: /posts/hello-world
summary: 'Hello world! means more than hello.'
date: 2022-12-16
link:   /articles/hello-world.pdf
---

I recall "Hello world!" as the birth announcement for the Mac. It actually predates the Mac - it's attributed to [Brian Kernighan](https://www.thesoftwareguild.com/blog/the-history-of-hello-world/). 
What's it for? If your program can render "Hello world", it works end to end. Per the Kernighan post, it's also that what's being rendered is also complex enough to excercise important functions. 

I'm using this post as a tool for learning enough of Jekyll to post a series of pdf-based articles on a simple website. 
Posts have a little metadata - like a title an summary - and get aggregated from a folder of post entries into a index page. 
Jekyll generates the index page and intances of the post pages. It uses a template to format structure the index page html and a different template for the post html.

In my case, the posts link off to .pdfs else where on the site. In some cases, the posts might embed an image. 
Instances of posts are edited in [markdown](https://www.markdownguide.org/basic-syntax/). 
The markdown syntax is nice for a plain text editor and provides hints for generation of  corresponding html.

Jeykll seems very nice. Code generation has always seemed like a magic trick.
Around 2000, I wrote a static site generator in Perl that used a site map specification and parameterized page templates and emitted a static a Cold Fusion site. 
It saved a lot of pain as we iterated on the site design and grew the site. 

But, since then, I've ignored building websites, per se. I did spend a lot time designing interfaces for search. 
How much of software development is producing structured output over dynamic content?

Anyhow, the Jekyll quick and dirty pattern is find a [site](https://gdasoulas.github.io/) you like, fork its base on git, and then tweak it to make your own variant. 
That has its limitations. I'd read the [docs](https://jekyllrb.com/docs/front-matter/) first.
