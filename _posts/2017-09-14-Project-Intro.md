---
layout: post
title: Project intro
---

# 9/13/17 - First steps
I make software. I like my job very much, and I'm good at it. I get paid to sit at home and code all day, which is exactly what I would be doing if I didn't have a job.

Hardware is just _cooler_ though. Hardware hacking will always be cooler. Creating a beast and then taming it.

I don't really know anything about computers, so I'm going to make one. This project will be serving as a sort of exploratory experience, and I'll be trying to stick to reading datasheets and probing around with meters rather than following any guides and tutorials too closely. I will surely be making a lot of mistakes along the way, so I wouldn't recommend following my steps too closely either.

## Why Z80?
I don't know enough about any microprocessors to choose from an engineering standpoint. Some quick googling showed that I've unknowingly been interacting with Z80s my entire life through calculators, video games, and embedded systems everywhere. I like that. They're still used today, 40 years later. The name is cool. Good enough for me.

## Project Goals
I plan to let this project be a learning experience and nothing more, but we'll see how that plays out. Hooking up a keyboard, tape drive, monitor, and modem would be very, very cool, but I'll be thrilled if I can get a computer I built myself to turn on and listen to a few instructions that I toggle in with switches.

I have seen a few homebrew builds with backplanes, custom bus patterns, and card-based hardware, and I like that very much. I think that my Z80 build will end up organized like that inside a nice enclosure eventually, but I think that would be biting off more than I can chew. I'll be starting the project off as a single board computer. Getting the componenents to play nice together without worrying about bus and power issues will enough of a challenge for now.

I'd like to keep everything in the build simple and handmade. I'll be using some newer test equipment while learning and debugging, but hopefully the end product will consist solely of hardware that would have been available in the 70s and 80s. I'm going to avoid buying any pre-fabricated boards or controllers, since that would really just be buying a slow, outdated computer for too much money. I'm also broke as shit.

I want the computer to have a name, too. I'll be working on that.

## Resources
I've been reading through Steve Ciarcia's _[Build Your Own Z80 Computer](https://books.google.com/books?id=mVQnFgWzX0AC&lpg=PP1&pg=PP1#v=onepage&q&f=false)_ repeatedly for the past week, and it's been a godsend. Ciarcia explains _why_ as much as he explains _how_, so I don't think I'll have too much trouble adapting his plans into my own designs. Donn Stewart's [CPUVille](http://cpuville.com) website has also been a source of inspiration. His schematics are simple and self-explanatory, and his expansion boards were all functioning prototypes on perfboard at some point, which shows that you don't need printed circuits to make something functional. He's even put out a guide for getting the Palo Alto Tiny BASIC from _Dr. Dobb's_ working on the Z80. One of the most motivating resources I've found is [this video](https://www.youtube.com/watch?v=AZb4NLXx1aM) of Julian Ilett hooking up a minimal Z80 setup in a matter of minutes. No RAM, no ROM, and a 555 circuit as a clock. Shows that it's possible to isolate components and take things one step at a time.

## Components
I spent a night or two scanning all of the schematics in _BYO Z80_ and getting an idea of the parts I'll be needing to get a basic setup running. I ordered a 6MHz CMOS Z80, 64k RAM, and a bunch of 74HC series ICs from Mouser. In my excitement, I also drove to Fry's the next day to pick up a few extra chips to play around with while waiting on the shipment, as well as a bigger breadboard and some solid wire. I've never worked with ICs before, so having some extras around can't hurt.

Since I don't really know what I'm doing yet, I decided to wait to order a board until I knew I could fit everything on it. S100 prototype boards seem pretty expensive and hard to come by, and I'm not sure if a single 160x100mm eurocard will be big enough. For the next few weeks, I'll be testing each module out on a breadboard and moving them onto something more permanent once I know everything will work.

![Box o' parts](/images/posts:2017-09-14/box_o_parts.jpg)
