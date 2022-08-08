+++
title = "Amos"
date = "2021-12-21T18:17:47Z"
author = "Chris Beeley"
authorTwitter = "chrisbeeley" #do not include @
cover = ""
tags = ["AMOS", "Easy AMOS", "AMOS Professional", "Programming"]
description = ""
showFullContent = false
+++

As I mentioned in my [programming post]({{< ref "programming.md" >}}) I'm going to start with AMOS, because it's AMOS that defeated me all those years ago with Space Invaders. There is stuff scattered about to help you learn and install AMOS but honestly it's spread pretty thinly and there are quite a lot of broken links so I've had a bit of a frustrating start. I'm going to write down What I Did for everyone's benefit, including mine when I get stuck. 

* Easy AMOS/ Normal AMOS can be found in this [big archive of Amiga software](https://archive.org/details/Commodore_Amiga_TOSEC_2012_04_10)
* [AMOS Professional](https://github.com/marc365/AMOS-Professional-365/releases/tag/365)
* [Easy AMOS manual](https://www.retro-commodore.eu/download.php?file=Mandarian_Easy_Amos.pdf)
* [AMOS manual](https://www.retro-commodore.eu/download.php?file=Mandarin_Amos_The_Creator_User_Guide.pdf)
* [AMOS Professional manual](http://www.classicamiga.com/images/stories/jreviews/software/A/manuals/AmosPro.pdf)

Other resources:

* [Amiga game maker's manual with AMOS basic](https://archive.org/details/amiga-game-makers-manual/mode/2up)
* [Mastering Amiga AMOS](https://retro-commodore.eu/files/downloads/amigamanuals-xiik.net/eBooks/Mastering%20Amiga%20Amos%20-%20eBook-ENG.pdf)
* [Ultimate AMOS](https://gitlab.com/amigasourcecodepreservation/ultimate-amos/-/raw/master/pdf/ultimate-amos-1994-holborn.pdf)

I'm going to give instructions that work on FS-UAE for Linux, which is what I'm using. I imagine it will be even simpler on a real Amiga. As for other types of Amigas, I really have no idea what I'm doing so don't listen to me. Speaking of not knowing what I'm doing, I'm still sort of bobbing about trying to find the path of least resistance to learn this stuff, these are only notes really, hopefully in the future it will all make sense and I'll write a follow up post that makes more sense. I will *try* to put stuff on GitHub, but how the heck you get stuff from AMOS onto GitHub on an FS-UAE emulated instance of an Amiga I don't at the moment have a clue. If I write something that works and figure it out, it will be here, trust me on that.

## Easy AMOS

I started working through the manual of Easy AMOS. It's very readable and accessible, but for someone who knows how to program (badly) it was a bit *too* basic. It's all in there, I just wanted to move through the material a bit faster. If you don't know how to program and you feel like learning a 29 year old programming language on an emulated version of hardware that hasn't been manufactured in 26 years (not sure how many people there are in *that* Venn diagram) go for it. 

## Normal AMOS

//TODO

## AMOS Professional

Getting AMOS Professional working is very easy. Go to the link above and download the zip file where indicated. Extract it, and you just want the folder called "AMOS". Copy that folder somewhere you can keep it, then just drop it in as a hard drive in FS-UAE (go to the hard drive tab, select the little picture of a folder next to an empty hard drive slot, and then select the AMOS folder). You'll need to have a Workbench HD image too. That's another blog post. I learned the above in these [excellent blog posts](https://retrogamecoders.com/installing-amos-basic/) but the advice is in a video and I prefer to read stuff myself.

My next step is to work through the tutorials in the previous link which culminates in... yes... Space Invaders. I'm not going to count that as a "win" for this step though, I'll make my own. Good start though.
