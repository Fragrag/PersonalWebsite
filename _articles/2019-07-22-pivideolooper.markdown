---
layout: article
title: PiVideoLooper
description: Making video installations easier
tech: (Python, Flask)
date: 2019-07-22 18:00:00
---

Raspberry Pis are commonly used to create simple media players that display a video. Artists, companies and museums have been looking into this, often enticed by its low cost when compared to enterprise products. Unfortunately making a looping video player with a Raspberry Pi has been rather clumsy and never quite perfect. Solutions involve editing multiple system files, which makes adjustments complicated and difficult for a layperson. They also often rely on working in an appropriate environment with a WiFi setup and/or access to a keyboard and mouse, which is often not the case, especially for more esoteric installations.

I remember the hassle of setting up a couple of Raspberry Pis for an art installation in my final year at the art academy. I nearly had everything configured correctly. I booted the Pi up and everything was fine except I had forgotten to turn off the on-screen display. I plugged in a mouse and keyboard and tried to exit the videoplayer. As it turns out, the Pi's default player omxplayer could not be stopped with the GUI when it was started as a background process. The only way to kill it was via the terminal and as the Pi was not connected to a WiFi network at that moment, I had no choice but to format the SD card and start from zero.

Since then I've learned my lesson. When doing such an installation, a Pi will automatically connect to my phone's WiFi hotspot, and I always have a VM installed on my Windows laptop so I can root through the files in the Linux ext* filesystem. This way I have access to the Pi's system in the absence of peripherals and a monitor. This also means that to provide support I have to do it myself rather than have another person, e.g. a museum's technical staff, do the fixing unless I leave detailed instructions behind.

I've always thought about this common requested use for Pis and how surprisingly difficult it can be. How can this process be made simpler and idiot-proof while at the same time be more flexible. That's why I developed PiVideoLooper. What sets it apart is the front end interface. The user can start the player and stop it. He or she can reboot the pi if needed. New videos can be uploaded and unrequired videos deleted.

[Get PiVideoLooper on GitHub](https://github.com/Fragrag/PiVideoLooper){: style="text-decoration:underline"}