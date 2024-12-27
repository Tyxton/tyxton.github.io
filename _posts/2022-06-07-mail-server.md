---
layout: post
title: "Setting up a mail server"
date: 2022-06-07 08:00:00 -0500
categories: homelab
tags: homelab mail

---

# Setting up a mail server

So I made the decision to make my own email for the Otacon alias and the process has been quite an interesting one for sure. As of writing this I am currently waiting for Sendinblue to Authorize the tyxton.net domain for the various emails I have/will have set up.


Basically the mail server is just iRedMail set up through nginx almost everything is standard. However, thanks to ATT and it's fun mess of an ISP to have dealt with over the years, port 25 is blocked to all customers that aren't strictly purchasing a buisiness model from them. Port 25 esentially is the server's way of telling all the other mail servers "Hey I have this message for you, take it." And because it's blocked the server can't do that on its own. This leads us to rely on a third-party program called Sendinblue. This basically bypasses the SMTP protocol (and by that I mean just utilize another port) and everything works fine. In the current moment I am just waiting on Sendinblue to Authenticate tyxton.net with the new TXT records placed through my DNS provider. This is proving itself to be impossible or just taking an extraordinarily long time to do so... in any case, Sendinblue did mention it could take 24-48hours for the DNS provider to update the records, however NameCheap mentions it should only take about 30minutes. I'll keep updated. As soon as I get the mail setup properly I'll update /contact/, but for now it's a bit of a waiting game.

### UPDATE: 7 June 2022
Alright, So it's been a while since I've updated this site at all, I wish I could say I've just been busy, but I've had little motivation in updating the project.

So, for whatever reason, the mail server does not want to work through Sendinblue's SMTP server. I will have to continue work on it, however, I haven't really touched any project in a few weeks now. I'd say it's been roughly two since I've touched the mail server, and about a week since I've attempted tp setup a web-based music player. I just need to start working on the projects again, but I've just been sidetracked by various things in life. Addictions resurfacing and whatnot. I'll try to continue the project in due time. I'll try to update this and document the process.
