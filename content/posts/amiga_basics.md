+++
title = "Amiga basics"
date = "2021-10-17T18:52:04+01:00"
author = ""
authorTwitter = "chrisbeeley" #do not include @
cover = ""
tags = ["Amiga", "FS UAE", "Raspbery pi", "hardware", "FPGA", "emulation"]
keywords = ["", ""]
description = "An intro to Amiga in the year 2021"
showFullContent = false
+++

In the [introduction of this blog]({{< ref "/posts/intro.md" >}}) there is a list of some of the different ways that you can get hold of an Amiga in modern times and this is the thing that by far confused me the most when I started back after 25 years away. There are a lot of different ways of getting your Amiga fix and this post is designed to help you to understand what the heck they are. Let's go back to the list from the introduction:

* Original hardware
* FS-UAE (emulation- Windows, Mac, Linux)
* Raspberry pi (several options here)
* A5000 (new hardware)
* Vampire (new FPGA powered hardware)
* MiSTer FPGA
* A500 mini

This list breaks down essentially into the following types:

* Original hardware
* Emulation
* A500 mini
* New hardware based on PowerPC
* FPGA

Don't worry if you don't know what half that stuff is, I'm going to tell you, as well as providing some links. 

## Original hardware

This is the simplest, sort of. There's a surprising amount of original Amiga hardware that is still alive and kicking. Very often things will be sold recapped, which means that the capacitors have been replaced. Often they will have had a good clean and test too. Recapping is pretty important because old capacitors can leak and damage the hardware. Other times you see listings that say "I just got this out of my loft, I've no idea if it works, you can buy it and find out if you want". This is fine but clearly you are going to want to spend a lot less on such a purchase because you really don't know if it's going to work.

There are some companies that sell old Amiga hardware. I feel sure I will buy an A1200 as soon as I find space for one.

* [Ami64.com](https://www.ami64.com/amiga-computers)
* [Retro Passion](https://www.retropassion.co.uk/). The thing I love about this shop is that they will even sell you a replica box! There were some very fancy Amiga boxes back in the day but I don't think I had one, both my A500 and A1200 came in plain white boxes.

There are loads of upgrades you can get now for original hardware, such as CF based solid state hard drives, loads of accelerators, USB flash drives. Plugging an Amiga in to a modern TV can be a bit of a challenge, I don't understand this well enough to help you but I gather it's possible with the right adapter.

## Emulation

This is also the simplest, sort of. There are two main types of emulation, really, normal PC and raspberry pi, so let's have a look at both

### Normal PC

If you use Windows, I would just pick up a copy of [Amiga Forever](https://www.amigaforever.com/). It comes with emulation, Workbench, ROM files, everything you need really. It's a little easier as far as I can tell, on Windows. For Linux and Mac you may end up buying Amiga Forever anyway, I did, because it comes as I mentioned with Workbench and ROM files. These files are not open source and so you can steal or buy them, basically. The cheapest way to get them is [on Android](https://play.google.com/store/apps/details?id=com.cloanto.amigaforever.essentials&hl=en_GB&gl=US) but I use Linux and I bought Amiga Forever anyway because it comes with some free games and stuff.

Speaking of free games and stuff, there is absolutely masses of software [for download here](https://archive.org/details/Commodore_Amiga_TOSEC_2012_04_10).

For Linux/ Windows/ Mac we have the excellent [FS UAE](https://fs-uae.net/). It's an absolute doddle to get it working. If you want to play games I suggest you go to [open retro](https://openretro.org/), create an account, and then add your favourite games to your favourites list. You can then [import the list into FS UAE](https://openretro.org/fs-uae-launcher) and they will appear in a list within the application.

One more thing to say is that FS UAE supports [WHDLoad](http://whdload.de/) out of the box. WHDLoad is a way of bundling old Amiga games so they load from a hard drive even if the original didn't support hard drives. Many games (like Turrican) even add multi button support. It's absolutely wonderful and you need it in your life. DON'T do what I did and spend ages installing WHDLoad inside the actual OS (via Workbench). Although this will work, you don't need to do this. Just get a WHDLoad file, stick it somewhere FS UAE can see it, click launch, and you're off.

### A500 mini

Speaking of WHDLoad, the forthcoming [A500 mini console](https://retrogames.biz/thea500-mini) supports WHDLoad too. It comes with 25 games, plugs in via HDMI, has an old style "tank" mouse", and allows you to sideload your own WHDLoad games. It sounds wonderful. I have quite obviously pre-ordered one.

### Raspberry pi

Quite a few options here, if you just want to play games you can use something like [Amiberry](https://blitterstudio.com/amiberry/) which you can download in things like [Retro Pie](https://retropie.org.uk/) or is available in [Amibian](https://gunkrist79.wixsite.com/amibian). Another nice option is [PiMiga](https://retrogamecoders.com/pimiga/), which gives a souped up desktop, applications, and games straight out of the gate. It's awesome. At the moment there is a 1.5 version, I gather 2.0 is in the works. 

Another option for Raspberry pi is [AmiKit](https://www.amikit.amiga.sk/raspberry), I fiddled around with the free Linux version and didn't love it, but you might, have a look, don't take my word for it. There's a free and a paid version. 

## New hardware based on PowerPC

This is the thing I know the least about, to be honest. There's a type of computer called PowerPC, not just Amigas, it's A Thing, and there was an AmigaOne X1000, and there is an [AmigaOne X5000 imminent](https://www.amigaos.net/hardware/133/amigaone-x5000). That's all I know. There doesn't seem to be a lot of stuff online. Sounds super interesting, just don't really know what it is.

## FPGA

FPGA is what all the cool kids are doing now. It's a system to emulate systems down to the chip level, like programmable silicon. The new [Analogue Pocket](https://www.analogue.co/pocket) uses FPGA (it looks gorgeous, I may get one). [MiSTer](https://www.theverge.com/22323002/mister-fpga-project-retro-computer-console-early-pc) is what you want for an Amiga- it will emulate all kinds of things, including Amigas. The [Vampire project](https://www.apollo-accelerators.com/) also uses FPGA technology and they make very, very fast Amigas which come in small cases and are reasonably priced. I really want one.

## What is an Amiga?

I probably can't really leave this post without discussing what an Amiga actually is. Some people in the Amiga community get quite het up about this. Original hardware obviously is an Amiga. Emulation is pretending to be a real Amiga. But some of the stuff I've talked about isn't recognisably "Amiga" as such- more what the Amiga would have become, if you like. The likes of PiMiga, Vampire, AmigaOne X5000, they all have different operating systems and desktop environments. I don't understand the technical bits well enough to give a good answer to what an Amiga is from a technical point of view. Amigas are special. They're not like normal computers. There are people who love Amigas for whom only the original will do. And there are people who love Amigas who are trying to imagine the future of Amiga. To me, if you love Amiga, and you tell me something is an Amiga, that's good enough for me. I'm really glad we have both types of enthusiast. I really think that the Amiga will never die, and that's amazing, and that's partly why I'm writing this blog, to help you understand how amazing it is.