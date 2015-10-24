---
layout: page
title: HeeksCAD
published: true
---


<p class="message">
Start with the free one...
</p>

[HeeksCAD/CAM](https://github.com/Heeks/heekscad) seems to be a fairly robust open-source CAD/CAM alternative, at least from the screenshots and feature list.  Unfortunately, as you can see its git is turning into a ghost town, no commits in 2-3 years.  But hey, maybe it just works and there's nothing to update?

![Screenshot]({{ site.url }}/public/heeks.png)

Firstly, I'm not using Linux as my primary OS and while it [may be possible](https://code.google.com/p/heekscad/wiki/CompilingForMacOSX) to build this package for OSX, I'm not really looking to do so when I keep a Linux VirtualBox around for other things anyway.

But there's a problem right off the bat...

[VirtualBox's OpenGL implementation](https://www.virtualbox.org/ticket/12746) for 64 bit Linux hosts is in various stages of broken, and this being a 3d application, it is going to require and build from your installed OpenGL libs.

Goint by [this comment](https://www.virtualbox.org/ticket/12746#comment:11) it may be possible to get Ubuntu 14 going with the required package versions in order.  Ubuntu 14 ships with Virtualbox 4.3.10 tools/versions.  The standard install of Ubuntu 14 currently installs a 3.19 series kernel which the 4.3.10 Guest Additions package (required for 3d acceleration) will [not build against](https://www.virtualbox.org/ticket/13741).  The Ubuntu 'mini' CD will by default install a 3.13 series kernel so that's the route to go here.  Ubuntu 14 also appears to have the desired [10.1.0](http://packages.ubuntu.com/trusty/libegl1-mesa) mesa package versions.

So as of now...

* Install Ubuntu 14.04 'trusty' from the [Mini ISO](https://help.ubuntu.com/community/Installation/MinimalCD)
* Pick the base install
* As soon as it's up and running, try to install the 10.1.0 mesa packages and the destkop
* ??? See what we've got at that point...
