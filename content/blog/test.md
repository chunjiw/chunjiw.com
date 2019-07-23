---
title: How I Solved My YouTube Problem
author: ''
date: '2018-06-19'
slug: how-i-solved-my-youtube-problem
categories: []
tags:
  - life
comments: no
showcomments: yes
showpagemeta: yes
description: "The story of me blocking my own access to Youtube."
---

<img class = "middle" src="/blog/2018-06-18-how-i-solved-my-youtube-problem_files/youtube_fallback.jpg" alt="Youtube Blocked" width="90%"/>

## The Problem
In the early days, right after I just arrived in the US, YouTube helped me tremendously to hone my listening comprehension skills. 
I watched videos repeatedly and consistently, with no caps or only English caps. 
After two years I became quite comfortable with slang that people use every day. 
Cases when my Chinese peers didn't understand what I did understand were not few. 

However, the habit sticked although the need faded. 
YouTube became my No. 1 source of news, talk shows, and tech reviews. 
I launched YouTube without thinking about it whenever I had some alone time. 
Every now and then I entrapped myself in an endless swirl of meaningless videos whose only function was to keep the mind occupied with gibberish. 
It happened both in late nights and mornings, interuppting my sleep schedule.

I do not think it was an addiction since I do not have strong cravings for it. 
But once triggered, I couldn't get myself out quickly. 
It was a problem to be solved for sure.

## Failed Methods
I've tried a few methods that failed.

- Avoid / Change Triggers.

One trigger was cooking and meal time. 
It felt natural to watch some videos while eating, but I would continue watching after the meal. 
I tried not to watch videos during meals, but it was simply too difficult to do.

Another trigger was waking up in the morning. 
Sometimes I did not get out of bed immediately, so I ended up in a deep conversation with my phone. 
This trigger was also too difficult to avoid or change. 
In a way, the YouTube problem was also the cause of getting up late: these two friends definitely got along. 

- Get an Accountability Partner.

I asked a close friend to be my accountability partner<sup>[1](#footnote1)</sup>. 
I proposed to report to her whenever I watched some YouTube, hoping that this layer of behavior would reduce my YouTube time. 
My friend, being a behavioral analyst, asked me to keep a record and share it with her. 
Took her advice, I created a Google Spreadsheet titled [Chunji's Video Entertainment Log](https://docs.google.com/spreadsheets/d/1OkupxntwN2B_u2c-08DuM7bAAAi4kIAl-agdeezlwZA/edit?usp=sharing), in which I kept a daily record ... for only a month. 
In the end, the recording became a sole endeavor, and I gave it up.

- Keep Electronic Devices out of Home.

I tried this method maybe five times in total. 
I brought all my laptops and tablets to work, and left them there, along with my cell phone. 
The night at home would be tranquil and peaceful, and I usually read till bedtime. 
I loved the tranquility, but it was at the same time unnerving to be disconnected from the world. 
Apparently, this method was not sustainable.

- MobiLock Pro

[MobiLock](https://mobilock.in/) was a service provider to help companies manage "work devices". 
The administrator had great control over what apps were available on a particular device. 
I set it up and left the admin passcode at work so that I could not change the setup after I got home. 
The obvious thing to do was to enable WeChat but disable YouTube; however, WeChat had a built-in browser through which m.youtube.com was available. 
Not to mention that MobiLock was a complex system that made the Android device very cumbersome to use.

## Resolve

At this point, I already fully admitted to myself that my self-control is weak to keep myself out of the YouTube black hole. 
It sounds awful, but the mentality of seeking help from without brings hope; it also reduces the burden over my shoulder. 

The other day I was reading Jordan Peterson's _12 Rules For Life_, and the second rule, "Treat yourself like someone you are responsible for helping" made me more resolved.
I do not intend to fight with myself, so why demand high and scold when fail? 
I should __help__ myself instead. 
The problem stems partly from technology; why not seek help from technology, rather than demonize it and shun it?

So I started my research. 
The rule of thumb is to set roadblocks, to make it very inconvenient to watch YouTube, while not sacrificing other conveniences. 
Mobilock is a failed attempt. 

## My Solution

There are three ways to access YouTube, in order of frequency:

1. YouTube App via mobile phones,
2. YouTube desktop site www.youtube.com via desktop browsers,
3. YouTube mobile site m.youtube.com via mobile browsers.

#### YouTube App
The YouTube App can be blocked via [AppLock](https://play.google.com/store/apps/details?id=com.domobile.applock). 
[AppLock](https://play.google.com/store/apps/details?id=com.domobile.applock) can block several apps from launching in a period of time or when the device is connected to certain wifi networks. 
So all I need to do is to block YouTube and Settings when the device is connected to home wifi, and leave the password at work.

#### YouTube Mobile Site
To block m.youtube.com on my Android, I [rooted the device](https://forum.xda-developers.com/oneplus-5/how-to/oneplus-5-unlock-bootloader-flash-twrp-t3624877), installed an [editor](https://play.google.com/store/apps/details?id=com.estrongs.android.pop), and edited the `/etc/hosts` file to add a line:

```
    127.0.0.1  m.youtube.com
```

After reboot, YouTube could not be accessed via browsers anymore. 
At this point, I also blocked the editor app via AppLock so that I cannot change the `hosts` file at home.

My Android is now YouTube-proof, that is, when the device is in my home.

#### YouTube Desktop Site

`hosts` file of desktops can also be edited similarly. 
The challenge was that I needed a way to lock the file against further change. 
I found this easy to do with my Ubuntu laptop. 

After editing the `hosts` file, I created an admin account, and demoted my personal account to a standard one. 
I chose a complex password for the admin account, and keep it at work so that I cannot use the admin account back at home, therefore cannot change the `hosts` file. 
Viola, now my Ubuntu is YouTube-proof as well. 

Similar procedures work for my Windows laptops.

## Two Months Later
It has been almost two months since I blocked my access to Youtube at home.
At first, I became immediately aware of the time that exists, that I wasted before.
I would pick up a book after dinner and read peacefully.
I even started drawing with encouragement from a friend<sup>[2](#footnote2)</sup>. 
I have drawn about 15 drawings.

#### Insignificant Relapse and Shifted Perspective towards Youtube
I could still watch some Youtube at home if I turn off wifi before I get back home, at the cost of cellular data quota.
But it fails to work very so often; 
also I don't feel OK to binge on Youtube on my cellular data.

Or I could launch Youtube before I get back home.
Then even though Youtube is blocked from launching, it is still running in the background, such that I could listen to the video.
In this case, there would be no binge watching because I could only listen and I couldn't switch videos.

When I get a chance to watch some Youtube at work, I see clearly what I didn't: 
the videos are really boring. 
Even when they are entertaining, most of them are just that: entertaining. No more.
I see how content creators scrap their brains to come up with banal ideas to make videos.
Very, very few of them actually create something that is worth watching, and those, are what I watch during work. 
Because I don't have time for others anymore.

#### Not-So-Healthy Replacements
- Netflix

Binge watching Netflix is not too bad since the shows are of a little higher quality.
I found a show called _Californication_ that I binged the first two seasons in a few days.
I finally decided that the harm outweighed the benefit, so I dropped Netflix as well.

- TV Networks

TV networks such as CBS offers some free clips and episodes.
It suits me very well: I would watch a few episodes and then I have to stop because free episodes are limited.

- Movies

I got a Moviepass.
To drive to a theatre and watch a movie feels totally different.

#### Healthy Replacements
Besides reading and drawing, the extra time gives me an opportunity to pursue other goals that I always have.
I have kept a journal for more than one month now.
I started to rebuild my personal website as a blog and write articles.
I rearranged my room; I clean it regularly.
I probably will restart my workout routine. 

## Reference
I got the most help from [WikiHow](https://www.wikihow.com/Block-YouTube).

#### Footnotes
<a name="footnote1">1</a>: Big thanks to Sharon!  
<a name="footnote2">2</a>: Big thanks to Lishan!
