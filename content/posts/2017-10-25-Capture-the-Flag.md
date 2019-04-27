---
title: "Capture the Flag at Ruby in Hollywood"
date: 2017-10-26T10:23:50-07:00
featured_image: "/juiceshop.png"
tags:
- rubyinhollywood
- appsec
- owasp
- hacking
- whitehat
- juiceshop
- ctf
---

## The idea

Last night, Ruby in Hollywood held its first ever Capture the Flag event. [Jake Wilkins][cb743955] had the idea for us to attack [OWASP Juice Shop][aa118dbb], which is a node.js app full of security vulnerabilities. I did some research about CTFs and thought it sounded like a great idea. I sent around this video from UCSB's white hat team to all [Ruby in Hollywood][1d9160cf] members so they could prepare.

{{< youtube bxt-JidP3bU >}}

## The setup

### Sponsor

[Colleen's](https://colleenmcguckin.com/) work [Ethnio](https://ethn.io/) sponsored pizza and let us use their space to hack. Thanks to Colleen and Ethnio!


### Scoreboard

I launched an app called [CTFd][bbe08ff3], which is basically a scoreboard and list of challenges for people to complete.I served up the CTFd app on the local network, so that everybody participating could log their completions.

Normally there are two types of CTF, either you do Jeopardy style, or you can do attack/defense. For this one, we did Jeopardy style. Each challenge was graded by difficulty, and as the difficulty increased, so did the amount of points you would get if you won.

Here's the jeopardy challenge board:
![](/jeopardy.png "Challenges Board")


### Experience with CTFs

Most of us had never done a CTF before, and so were unsure how to get started. We had a bunch of interest from people who looked like they may have been more experienced CTF hackers. That was really cool to see, that there is definitely interest in CTFs here in our backyard. But for the rest of us, it was a great way to dive in.

### Juice Shop
![](/juiceshop.png "JuiceShop")

Juice Shop is an app specifically created to be vulnerable. There are about 50 flags you can get out of the app by completing challenges. When you complete a challenge, it gives you a code, or "flag". You can then enter it in the scoreboard app that I set up to get your points. The challenges are in categories from cross-site scripting, to account hacks, to SQL injection. It doesn't matter what order you do them in, but usually people start with the easier ones.


## Ready, set, hack!

Everybody got started by cloning Juice Shop locally in CTF mode (`NODE_ENV=ctf npm start`). Then each person had an instance of Juice Shop running on their machine and started hacking.

People paired up in teams for the most part, and talked out different ways they could attack the app. Juice Shop is one of the most popular apps for CTFs, so we were on the honor system not to google "juice shop vulnerabilities", because that would have given us all the answers.


The first couple challenges were out of the way pretty soon, and people got to work on some XSS, SQL injection, and rainbow tables.

We ended up staying way later than usual, until about 10:30, when everyone's batteries started to die. In the end, here were the final rankings:

1. Shannon and Colleen (and Jake?)
2. Roy and Vicken
3. Ernesto and Steph
4. Yanny also got a bunch of flags but couldn't access the scoreboard to log his points.


![](/scoreboard.png "CTFd Scoreboard")

## Great work to everybody who participated! We'll plan another CTF soon

![](/juiceshopflag.png "JuiceShop")

  [cb743955]: http://www.jakewilkins.com/ "Jake Wilkins"
  [bbe08ff3]: https://github.com/CTFd/CTFd "CTFd"
  [aa118dbb]: https://www.owasp.org/index.php/OWASP_Juice_Shop_Project "OWASP"
  [1d9160cf]: rubyinhollywood.com "Ruby in Hollywood"
