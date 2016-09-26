---
layout: post
title: Free version of Moonsols Memory Forensic Toolkits
date: 2016-09-26
thumb: http://www.patterndiagnostics.com/files/AdvancedWMDA.png
backgrounds: 
    - http://67.media.tumblr.com/bc7385bd365d2c7879900b6878c53152/tumblr_odoypfuNaM1slhhf0o1_1280.jpg
tags: Memory Tools
category: Research DFIR
---

During my master research on Digital Forensic of Data Discovery of Private browsing of Chrome Incognito mode, I run into one major problem. The problem is to uncompress Windows 8 crash dump files to memory dumps file with address that [Volatility](https://www.volatilityfoundation.org/) Framework can parse. The only tool that can achieve this is is [moonsols](http://moonsols.com/) Hibr2Bin and there are only commercial products that I can't afford. I have to give up from using the result I can collect from Hibernation dump files.

I posted for an alternative solution from fellow DFIR practitioners and an interesting twitter [conservation](https://twitter.com/AtrHein/status/657079376467464193) started with Volatility Core Developer and Moonsols  Developer. He mentioned that the tool will be open-sourced late 2016 and now it [happens](https://blog.comae.io/your-favorite-memory-toolkit-is-back-f97072d33d5c#.bl3bwdcya)!!. 

Just fill a form to download the Comae Free Toolkits that includes 2 tools: *DumpIt* and *Hibr2Bin*. 
I downloaded it and tested it by dumping the physical memory and it works smoothly.
A very good news for DFIR community!

