---
layout: post
title: Hello World!
---

So, here's the thing: whenever I try to *do* something (in the 'tinkering with software' field), I almost always end up stuck somewhere. Which is not to say that I've never managed to tinker with stuff, I eventually figure something out, but the point here is that nothing ever goes smoothly with me. Part of the reason is that I use windows primarily for my dev needs (story for another post), but I think there is something mroe to it. Either I try to switch to other solutions too quickly (which means I run into problems *there*, and the cycle continues), or I'm just too dumb, or something. Not quite sure what, but I feel that I have to go through more issues and for longer than other people. This could just be perception, of course, but it sure doesn't feel like it.

This essentially means that whenever I start installing something, or trying something out, I know in the back of my mind that its going to be a pretty long ride.

### The Strange Case of Dr. Jekyll and Mr. Hyde

Going by my usual experience, getting this blog set up was surprisingly simple. The truth is, I have never really looked into setting up a blog myself, and so had no idea about jekyll, poole, hyde, octopress, ghost, or whatever. I basically had no idea that there existed something called static site generator until I *did* decide to set something up on a server I 've rented. So I asked one of my friends what the state of the server was (5 friends share the server amongst ourselves), and when I told him I wanted to set up a blog, he was like, why dont you just go with a static site generator? I, of course, had no idea what he meant, so he directed me to google Jekyll. So I googled, and googled, and googled, till I figured most of it (read: some of it) out. And then I decided to set it up for myself.

The setting up part was, thanks to a bunch of amazing people on the internet, easy-peasy. A bunch of links for those interested:

* [The official Jekyll page](http://jekyllrb.com/) was an intro, but surprisingly unhelpful, as I had no idea what gems were (or that jekyll was ruby based).
* [This](http://joshualande.com/jekyll-github-pages-poole/) blogpost that explains how to set this stuff up, step-by-step. Also, it introduced me to poole.
* I then stumbled onto [poole](http://getpoole.com/), which was pretty darn cool. I checked out its themes, and decided on [Hyde](http://hyde.getpoole.com/).
* Poole's [github page](https://github.com/poole/poole) directed me to [this page](http://jekyll-windows.juthilo.com/) for windows. By and far the most useful page on the list for win users.

and that was it! In a  pretty small time, I had a pretty good idea about how stuff works, and I had it all setup on my machine too, all in one go.

Of course, it helped that I was kinda-sorta familiar with templating engines (Jinja2), so didn't have to look into those (Even though understanding the basics is pretty easy for templating engines, all in all). The config file, too, is smart, but I've used similar concepts earlier, so it didn't take time to figure that out.

### Up Next

Now all that remains it tweaking the page till I'm satisfied, and figuring out how syntax highlighting for jekyll works. The jekyll-for-windows page had some info, but I wasn't completely sure I understood it. So have to look into that. 
Poole has a bunch of things that are configurable, so the first part should be easy to do. The second part, I'm hoping, will be smooth sailing like the rest of this blog.

And with this, I come to a rather abrupt end to this blogpost. Thanks for reading!

PS: Who would've thought. I got stuck at hosting this on gh-pages. Fairly easy fix, though, so that was nice. Shoutout to [Shivam Rana](https://github.com/trigonaminima) for helping me out.
