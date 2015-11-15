---
layout: post
title: Speaking of Heeks (and DolphinCAD)
comments: true
---

<p class="message">
Hmmm....
</p>

I mentioned [HeeksCAD/CAM](https://github.com/Heeks/heekscad) in a previous post.  For what it is (both CAD and CAM) and what it costs (nothing, it's an open source project), it seems like a pretty decent software package for starting out with.

After having issues installing it on OSX (missing 64 bit capable libraries/dependencies) and having little luck with it in a Ubuntu Linux Virtualbox due to issues with Mesa and the VirtualBox 3d driver, I just grabbed the Windows trial version to check it out real quick.

But then I noticed something.

![Screenshot]({{ site.url }}/public/heeks-dolphin2.png)

HeeksCNC icon in the upper left, the PM3D icon just below it to the right is DolphinCAD's import/export program that comes at a 500 dollar price premium to their standard cad/mill bundle.  Looking a bit further into what all is in there...

![Screenshot]({{ site.url }}/public/heeks-dolphin4.png)

Those look an awful lot like the exact same libs that come with HeeksCAD...

![Screenshot]({{ site.url }}/public/heeks-dolphin6.png)

And here's a shot from the opening screen of Heeks laid over a screenshot from the DolphinCAD manual...

![Screenshot]({{ site.url }}/public/heeks-dolphin.png)

Here's the manual page describing what the program in question does, it's obviously the IGES/STEP importer that Dolphin charges 500 dollars for...

![Screenshot]({{ site.url }}/public/heeks-dolphin5.png)

I don't know what the story here is.  Maybe the guy who controlled the Heeks code started Dolphin.  Maybe the people who started Dolphin just took it.  Not that there's anything legally wrong with that, HeeksCAD is under a BSD license, it's free to do whatever you want with.  I googled around quite a bit on the author of HeeksCAD's name and the company history of Dolphin CAD/CAM but couldn't turn up much.  I will say that out of all of the commercial CAD/CAM softwares I've tried evaluation versions of, Dolphin was the only one I got a 'high pressure sales' call from.  The others might have sent an email here and there (surely automated) or maybe a courtesy phone call.  But the Dolphin guy jumped right into the speech about how a university had "accidentally over-purchased their licenses, and for a limited time I could possibly get one of their leftovers at half price, but they're going fast so I should act SOON."  

Sure thing buddy, I'll get right on that...
