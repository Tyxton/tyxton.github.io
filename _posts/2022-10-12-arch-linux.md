---
layout: post
title: "Why should one choose Arch Linux?"
date: 2022-10-12 08:00:00 -0500
categories: linux
tags: linux arch

---

# Why should one choose Arch Linux?

I will lay out the reasonings one should consider Arch as their main distro in a bit of a list, however several of the points will overlap with each other.

### - Customizaton
Arch Linux has the benefit that many minimalistic distrobutions do: you decide what is on the system. This is a large reason to use Arch as well as Gentoo. There is no bloatware unless if you install it onto the system, you won’t be wasting resources and you especially won’t be installing anything you don’t want onto your system. This is unlike many “mainline” distros (like Ubuntu and Linux Mint) where it comes preinstalled with a Desktop Environment as well as a bunch of (useless) apps. With Arch, you choose what is on the system. From the Kernel all the way up to the web browser you want to use.

### - Cutting-Edge
This can be argued as either a pro or a con, however, Arch Linux is a rolling release distro which means that an update is available as soon as it’s released rather than a fixed release distro where the updates only come out periodically and take quite some time to test before release. Now of course, fixed release distros do this to ensure the product works as intented and without vulnerabilites before release. However, with my several years using Arch Linux, I’ve had no more problems than I’ve had on anything fixed release. And in the event something did break, it was quite simple just to roll back the update and have everything working properly again. This goes for the software installed on Arch as well, all cutting-edge releases of the software, which means that everything installed on the system is up-to-date. One may argue that this would leave many security vulnerabilities in the software, but no more have been found in these up-to-date releases than the tested ones.

### - The AUR
Some people hate on the AUR, however I don’t think I would be able to return to a distrobution without it. The AUR (Arch User Repository) is essentially a **gigantic** database of user-submitted PKGBUILDs and because of this, any software not found in the pacman repositories (more on this later) are rather easily found in the AUR. The AUR, along with software like yay, allows you the freedom from Github and having to clone the repository and run mkpkg everytime you wish to install a program not found in the “official” repositories. Almost everything on Github is found on the AUR and you can install it from cli just like any other program so long as you know the AUR name (which you can easily find in the archwiki).

### - Pacman
The Arch package manager (pacman) is a great mid-point between apt (Debian-based distros) and emerge (Gentoo-based distros). Unlike apt, pacman installs the latest release of the software from the repository, much like emerge. However, unlike emerge, you don’t have to compile the software from source, which is much faster. While there are some benefits to compiling from source, for many people these benefits are miniscule. And (especially) on older hardware, compiling from source takes too much time due to CPU usage. So Pacman is the best of both worlds! (It also has great customizaton).

### - The Community
Shitposts and “I use Arch btw” aside, the Arch Linux community is a very resourceful and cooperative bunch. Because of the community that backs Arch, it’s completely free from corperate garbage cough cough Ubuntu… everything Arch is developed by the community that uses the operating system and it’s software. This same community keeps the AUR up to date and keeps the whole system up and running. Without the community that backs Arch, it would be another forgotten distrobution much like Void.

This is my sort of love letter to Arch Linux, and I may add or revise this as time goes forward, but as of 13 July, 2022, this is where my opinion on Arch stands and I emplore all those who enjoy linux to use it!
