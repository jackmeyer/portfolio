---
title: Shower TV Build
date: 2021/3/18
description: Learn more about Next.js pages.
tag: home development
author: Jack M
---

# MagicMirror build

### Purpose

My partner and I are almost always plugged in to YouTube, watching content ranging from beauty product reviews to sports talk shows. We're often watching at our desktop computers, laptops on the couch, phone in the kitchen, or even... in the shower. 

The truth is, it's **hard** to watch videos in the shower. I don't want to get my phone wet, and often the iPhone speakers aren't loud enough to hear over the running water. Sure, I've used a water-resistant Bluetooth speaker before, but I was in the middle of an interview prep course and wanted to see the visual explanations on the screen. 

With this bright idea, I looked to Amazon. Took me all of 5 minutes to realize that there were no commercially available _shower screens!_ Without spending thousands on a no-name brand [mirror TV](https://www.amazon.com/Haocrown-Waterproof-Television-Bluetooth-Touchscreen/dp/B08D3NYPFZ/ref=sr_1_13?keywords=shower+tv&qid=1642804348&sr=8-13), the only way to find the entry-level shower screen I was looking for was to build it myself.

### Brainstorming

Since I was only ready to make a prototype, I figured that I'd have to construct this device with all consumer parts. It would be made of the following components:

- a screen, obviously
- a video source
- speakers louder than my phone
- and a battery big enough to power it all

#### The Screen

I had experience stripping down the plastic assembly of a PC monitor before, but knew that I had to find something thinner and lighter. Plus, I'd need something USB-powered. 
I've seen plenty of ads for portable USB-C monitors, and was excited to find one that had built-in speakers as well. I picked up this [12.5in 1080p display from Amazon](https://www.amazon.com/gp/product/B08FX18FXM) for about $80 at the time.

#### The Source

A video source, which I decided an old Chromecast I had laying around would be perfect for. No fussing with the device itself, just turn it on and cast to it from your phone.

#### The Sound

No surprise, the built-in speakers on the USB-C monitor mentioned above were terrible. Good enough for a quiet room, but not any better than phone speakers.

I had some USB-powered speakers that I had taken apart for a previous project, and they were small (but mighty) enough that they'd fit my needs. 

import Image from 'next/image'
<Image 
src="/images/showertv/speakers.jpg"
alt="Speakers"
priority
className="next-image"/>

#### The Juice

- A battery with enough capacity to power a 1080p60 screen and Chromecast simultaneously. A 20000mAh portable battery would have enough juice to power the setup for at least a few hours, but realistically I'd only be using it for 10-20 minutes at a time. 


