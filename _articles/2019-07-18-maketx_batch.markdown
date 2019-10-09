---
layout: article
title: MakeTX_batch
description: A helpful script for 3ds max and Arnold
tech: (Powershell, 3ds max, Arnold)
date: 2019-08-08 18:00:00
---

Arnold is a ray tracing renderer that is commonly used in VFX, CGI and architectural industries. One of its features is its ability to use .tx texture files. These textures are designed to be used as efficiently as possible by the renderer. It already contains mipmaps and tiled. This means that Arnold can efficiently load the exact chunks of image data that it needs rather than loading the whole image into memory and wasting resources.

Depending on your software packet of choice, Arnold might create these .tx files automatically, easing the workflow. Unfortunately 3ds Max lacks such support. Thus they have to be made manually outside the program using maketx.exe, a command line application provided by the developers of the .tx format that converts images to .tx. When dealing with dozens, maybe even hundreds of these files, this can be encumbersome.

To ease this process, I created a simple Powershell script. It goes through each file in a directory and subdirectory and creates a .tx file for every appropriate image file that it finds. Click on the link below for the GitHub repository, where you can download the script and view its source:

[Get MakeTX_batch on GitHub](https://github.com/Fragrag/MakeTX_batch)
