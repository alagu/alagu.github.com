---
layout: post
title: Checking Disk Usage across Platforms (Including AWS)
---

PS: This post is mostly for my personal note. 

Whenever the disk usage goes up, I had to find out which folder takes maximum storage and a visual way to show that was super helpful aways. 

Here are some options if you hadn't used.
- For OSX - [DiskInventoryX](http://www.derlien.com) 
- For Windows - [WinDirStat](https://windirstat.net)
- For Android - [DiskUsage](https://play.google.com/store/apps/details?id=com.google.android.diskusage&hl=en_IN&gl=US) 

For our AWS servers, it seemed like [ncdu](https://dev.yorhel.nl/ncdu) was a great option, but later I found [GDU](https://github.com/dundee/gdu) and it is brilliant. 

As a sidenote, I've been seeing more blazing fast disk usage applications being built using golang.
