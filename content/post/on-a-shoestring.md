---
title: On a Shoestring
subtitle: Running a bunch of websites and newsletters... on a shoestring.
date: 2023-01-17
tags:
  - tech
  - hugo
  - newsletters
---

For various reasons, I've not updated this site for about six months. The second half of 2022 was super-busy, and so I didn't have much time to post here. But in the background, I've been busy. And one of the things I've been doing is overhauling a lot of the stuff I do online.

### Consolidating the empire 

By early last year, I'd accumulated quite an empire of websites. There was my philosophy project, Looking for Wisdom ([lookingforwisdom.com](https://www.lookingforwisdom.com)). There was the site for the social enterprise I co-direct, [Wind&Bones](https://www.windandbones.com). There was my own personal website, [WillBuckingham.com](https://www.willbuckingham.com). In addition, there were quite a few other little online projects sitting around as well: the site dedicated to the work of my late partner [Elee Kirk](https://www.eleekirk.com), this not-quite blog site, my site about the [Tanimbar islands](https://www.tanimbar.org.uk), and a few more.

For years, I ran all my longer-standing projects using WordPress. There were a few associated costs here in terms of hosting and ongoing costs for plugins and the like. These were starting to mount up. Then, more recently, during lockdown in Bulgaria, I was enthused by the idea of setting up a newsletter, so I set up Looking for Wisdom with the wonderful Ghost. Then, finding the platform a delight to use, I switched my own personal website to Ghost as well.

But there was one problem: running so many websites was turning out to be expensive. Ghost is about $348 a year, but I was paying this for two sites. And things were looking like they could escalate: Looking for Wisdom had around 600 subscribers and was still growing. But it made no money, and when projects are not really income-generating, growth is not necessarily good. After 1000 subscribers, the costs for running Ghost jump considerably. And I realised I simply couldn't afford it. 

### Websites on a shoestring

So over the past months, I got to work cutting my costs. First, I tackled my websites. Since the middle of 2022, I've been systematically migrating everything over from Ghost and/or WordPress to the static site generator [Hugo](https://gohugo.io/). 

Hugo is fast, database-free, and when the sites are pushed to Github and deployed via Netlify, it all works out as costing nothing at all. 

Getting to grips with Hugo was something of a learning curve. But once I got the hang of it, I was smitten with its elegance. Of all my sites, Looking for Wisdom was the most troublesome to migrate, largely because of the amount of content: 250,000 words, over 100 philosophy articles, and countless images and links to check. 

But now it's all done, I can say that it's been worth it. All of my sites are now happily built with Hugo, they're looking pretty nice, and they have no ongoing running costs (other than domain names).

### Newsletters on a shoestring

The next question I faced was how to run my newsletters. There was Looking for Wisdom. And there were also a couple of smaller newsletters that I used for my personal site and for Wind&Bones. One ran using MailerLite, and one used Revue, Twitter's now defunct newsletter tool. MailerLite was fine, but the costs also threatened to jump after 1000 subscribers. And Revue died a death after Elon Musk's takeover of Twitter. 

I started by migrating Looking for Wisdom over to the elegant little newsletter app [Buttondown](https://buttondown.email/). I love Buttondown. It does what it needs to do and gets out of your way while doing it. It also has nice, straightforward archive pages and — in theory — should integrate into Hugo with a nice little bit of JavaScript magic.

I read JavaScript like I read German: on a good day I can pick my way through and get the gist, without really knowing what is going on. So it took a while to get the integration with my static working. But with a bit of help over on the Netlify forums (see [this thread](https://answers.netlify.com/t/newsletter-with-buttondown-and-netlify-forms/16604/15)), everything was up and running.

Emboldened by my modest successes, I started to think about my two remaining newsletters for Wind&Bones and my own website, WillBuckingham.com. 

Here, Buttondown was an option again, but as I sent these newsletters so infrequently, I wanted something a bit cheaper still — more pay-as-you-go than subscription-based. After a bit of searching, I stumbled across [MailBluster](https://mailbluster.com/), which is a super-affordable tool for sending emails. I spent a day or so tweaking my Buttondown integration scripts to work instead with MailBluster, faced down the beast that is Amazon and got their SES up and running (Simple Email Service, which for the technologically challenged is something of a misnomer), and managed to get both newsletters working on my test server.

So over the last 24 hours, I have moved both remaining newsletters over to the new system. And so far, they are working well.

### The sums

It's taken a lot of work, and I've learned a lot. But it's been worth it. Previously, my website running costs were something like $348 for each of the two Ghost installations, plus Wordpress hosting, plus domain name costs, plus other stuff like updated plugins and so on.

When I added it all up, I realised I was spending close to $1000 on running my small online empire (on top of domain name costs).

Since the switch, this has fallen to $90 for Buttondown for a year, plus something like 0.05 per newsletter campaign I send out with Mailbluster (these newsletters are very small scale). Then there are the domain name costs on top of that. And that's all. This makes everything remarkably affordable.

Not only this, now everything is set up, it is all incredibly undemanding in terms of the work needed to keep all this running. If I want to update one of the sites I run, I just write a new Markdown file and push it to GitHub. Netlify and Hugo do the rest. And if I want to send a newsletter, I just login and write, then click send. Everything is pretty much taken care of.

Now all of this is done, I am free to go back to thinking about other stuff. Like philosophy! I'll try to keep this site updated as an informal notebook of my thoughts and my work in progress.