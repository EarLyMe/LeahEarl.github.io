---
layout: post
title:  "Slaying the Empty Screen"
date:   2016-05-19 17:01:08 -0400
---

![Empty Screen Dragon](http://i.imgur.com/KqCdXyI.jpg?1)

The absolute most difficult part of the CLI Data Gem Project was getting started. Hands down, the blank screen of my computer was terrifying and its vacant gaze was piercing my soul. It knew all of my fears and projected them back at me (a video AND a demo with talking?!?!? There’s no way you’re going to be able to do that without looking ridiculous) making the blank screen seem monstrous and incredibly large, a demonic black dragon that needed to be slain. I was frozen and unable, it seemed, to even start. The walkthrough submitted by Avi for the creation of his Daily Deals gem was the steed that allowed me to slay this terrible dragon. Ok, I’ll stop with the pseudo-fantasy metaphors. In the end, “I get by with a little help from -” if not necessarily my friends, then from the undoubtedly supportive community at Learn.

Watching the walkthrough gave me a place to start working on my code. I had all of the pieces of the puzzle sitting right in front of me, I knew about objects in Ruby, I knew how to scrape a website, and I even knew exactly which website I’d like the information to come from (I had decided to make a CLI that let the user find upcoming dance events, which is something I need in my other life). I just didn’t know how to piece all of these things together into a gem. Oh yeah, and the gem was something that I didn’t really know about either. Watching the walkthrough gave me an idea of where to look for this information. I used:

* [How to Write a Command Line Ruby Gem](http://robdodson.me/how-to-write-a-command-line-ruby-gem/)
* [Make Your Own Gem Guide on RubyGems](http://guides.rubygems.org/make-your-own-gem/)
* [[Engineering Lunch Series] Step-by-Step Guide to Building Your First Ruby Gem](https://quickleft.com/blog/engineering-lunch-series-step-by-step-guide-to-building-your-first-ruby-gem/)

Honestly, it took about 10 different websites total to find the majority of my answers but mostly it happened in those right up there.

One of the things I like about learning from Learn is that they give you fairly explicit instructions and if they don’t hit all the fine points, they send you to someone who does. Also, Google. They love Google. But seriously, who doesn’t?

Finally came the time for the actual programming, [rubs hands together with glee] and I found out that this was mostly something that I could do. I couldn’t do it exactly the way Avi did in the walkthrough, starting from the front end and working backward seemed to me to be, well, backward. I did start by working on my CLI and getting that to a pretty good point before diving into the web scraping and forming my other classes. This process also helped me to know if everything was working without having a test suite; it enabled me to make sure the program still did all the things I had envisioned it doing. Eventually, I ended going back and forth a lot, working on one class, trying to determine the smallest amount of methods for that class that I needed, making sure that the stuff I did to the class still jived with my CLI, and back again.

There were a few stumbling blocks, one of which was in the information that I scraped from the website. The problem was that when I tried to scrape URL information, some of the events didn’t have URLs. I tried to incorporate this part of the scraping in an if statement that would rule out any events that didn’t have URLs, but unfortunately couldn’t get it to work. That block ended up being insurmountable for me with most of two days spent in trying just to figure it out. I plan on revisiting this idea later but for now I’ve decided to let it go and move on for the sake of getting this thing done.

I also took a bit of time working on having my objects relate realistically to each other. I wanted to be sure that each class was only doing what they needed and not something that could be done by another. In the end, I ended up calling on my other three classes from the CLI class rather than have them each speaking directly to each other. It seemed more logical to me that way, where the CLI would take care of operations while the other classes were just taking care of themselves.

The other bit of a hang-up I had was getting the gemspecs sorted and tackling customary file organization. I have a feeling that since enrolling in Learn online was my first real relationship with programming, aside from a few HTML and CSS one night stands, I’m a bit behind on this sort of thing.

And well, eventually, I overcame that darn screen dragon of mine and made a working program. I even ended up doing the demo walkthrough and actually talked about how the program can be used. It took me much longer than I expected, mostly because of my blank screen anxiety and overactive imagination, but it is finally completed. And I’ve actually got a working something to show for it (at least I hope it’s working). Huzzah for the slayer of the empty screen and her trusty Learn.co steed!

