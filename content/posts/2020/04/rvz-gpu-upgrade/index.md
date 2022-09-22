---
title: "Actually upgrading my Desktops GPU"
date: "2020-04-17T00:00:00Z"
template: "post"
draft: false
published: true
category: "Hardware Upgrade"
tags:
  - "Tech"
  - "PC"
  - "RVZ"
description: "Trying to play Forza at that low framerates finally got to me"
---

So I went ahead and plumped for a new Graphic card, spending about a week and a bit trying to understand which was the correct one for me.
I wanted a card that would last a good couple of years but also not break the bank (so I was setting myself £200 as a max limit).
Also - I wanted to ensure it worked with my existing system as is - so it had to match the wattage, sizing and PCI version (even in backwards compatibility mode) of the Radeon R9 270X currently in my Desktop.

This lead me down the path to one of a couple of cards:

- Team Green (Nvidia)
  - GTX 1650
  - GTX 1650 Super
  - GTX 1660
  - GTX 1660 Super

- Team Red (AMD)
  - R270
  - And I think that was it

At this point I was way in deep over my head over what to choose, price per FPS, etc.
This was further complicated by the outputs I was wanting:

See - the XFX R9 270X had 4:

- DVI (Dual Link I think) that I never used
- HDMI (which I run to my TV)
- 2 x Mini DisplayPort (which I was running my monitors for WFH for)

So a couple of years ago, I had "standardised" to using Displayport and Mini Displayport everywhere.
All my monitors have Displayport at least, plus I had invested in long cables already
My Laptop (2011 MacBook Pro 13") uses Mini Displayport, so does the Intel NUC I use as a Home Server and so does my Desktop - so for me, this was a must.

Turns out - getting Mini Displayport and HDMI on a graphics card now is [limited at best](https://uk.pcpartpicker.com/products/video-card/#o=2,8&H=1,3&X=0,22997).
So, in the end I went with a Nvidia GTZ 1650 Super - specifically the [MSI GeForce GTX-1650 SUPER GAMING X](https://www.msi.com/Graphics-card/GeForce-GTX-1650-SUPER-GAMING-X), mainly as it was a newer GPU compared to the R270 (the Super was released late 2019), it was in budget and all the reviews online suggested the Nvidia was the horse to bet on right now. Plus - it has 3 Displayport and 1 HDMI output (so new cables required, but still Displayport for monitors).

So - why did I not go for the GTX 1660 Super then if I was looking for future-proofing? In a nutshell - I felt the value proposition was not as strong as the 1650. Top of my head I would need to spend ad extra £30 (and top my budget) to get an increase of maybe 10fps (going from 60fps to 70fps). As I'm going from some games struggling to get 30fps consistently, plus I would need to splash out on new cables (remember - I'm going from Mini Displayport to Displayport), the 1660 Super started to look unattractive.

Overall, the install was ok. My case (a [Silverstone RVZ01](https://www.silverstonetek.com/raven/product-rv.php?pid=487)) is a pain at times to work in - mainly that fact the GPU is mounted upside down and connects to the Motherboard via a special PCI-E riser card, but it fits (just). As the GPU is upside now, the case has an adjustable bracket which I think is definably required but takes a good 15 mins to actually get it mounted and secure. This is before I realised that the card is physically taller forcing the power connector inside the case (as the PSU at the front of the case an has a cable that runs to a IEC connector on the back), meaning the power connector is now hanging out the back of the case...

With all this in mind: I think the card looks very well designed with the angles, etc - I won't see it as I don't intend to get that GPU out again to look at it considering the pain to get it in.

Software install was OK and picked up my monitors and my TV. HDR is support to my TV which is nice and the Nvidia software seems OK. I prefer it over the AMD equivalent - mainly as it seems to keep the drivers up to date without me constantly poking it - but 'optimises' the games graphics settings. I honestly don't know if this is good or not compared to manually dialing it every setting in every game, but this a nice touch.

So - in the end it was worthwhile investment. I have not upgraded my CPU yet, so I fulled expect the GPU is now CPU bottlenecked but I'm ok with that at the moment. 

Playing Forza Horizon 4 has become a dream again: I've went from 1920x1080 playing on the Low graphics present and getting 22fps most of the time - to going to 4k (3840x2160) at Medium preset and not dipping below 60fps.

So, as of this post the spec are now:

| Component    | Selection                                                           |
|--------------|---------------------------------------------------------------------|
| CPU          | Intel Core i5-4460 3.2 GHz Quad-Core Processor                      |
| Motherboard  | MSI Z87I AC Mini ITX LGA1150 Motherboard                            |
| Memory       | Kingston HyperX Fury Blue 8 GB (1 x 8 GB) DDR3-1600 Memory          |
| Storage      | Western Digital Caviar Blue 1 TB 3.5" 7200RPM Internal Hard Drive   |
| Storage      | Samsung 850 EVO-Series 250 GB 2.5" Solid State Drive                |
| Video Card   | MSI GeForce GTX-1650 SUPER GAMING X                                 |
| Case         | Silverstone RVZ01B Mini ITX Desktop Case                            |
| Power Supply | Silverstone 500 W 80+ Gold Certified Fully Modular SFX Power Supply |
| Case Fan     | be quiet! Pure Wings 2 120 51.4 CFM 120 mm Fan                      |

If I move to doing an upgrade of the CPU, Motherboard, etc I'll try to write that up also - although I am due to replace my MacBook Pro first....
