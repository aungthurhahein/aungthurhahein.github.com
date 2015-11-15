---
title: Zeal:Document Browser
layout: post
backgrounds:
    - https://images.unsplash.com/photo-1444837881208-4d46d5c1f127?fit=crop&fm=jpg
thumb: https://i.imgur.com/m2MS8py.png
date: 2014-03-24 
tags: Linux
category: Notes
---

I just found out that there is a document browser called <a href="http://zealdocs.org/" target="_blank">Zeal</a> which is inspired by <a href="http://kapeli.com/dash" target="_blank">Dash</a> for MacOS. You can save dozens of reference documents into your machine for offline browsing.

You can install to your ubunut machine by adding these ppas:


{%highlight bash%}
//QT5 dependencies && zeal ppa
sudo add-apt-repository ppa:ubuntu-sdk-team/ppa &&
sudo add-apt-repository ppa:jerzy-kozera/zeal-ppa &&
sudo apt-get update &&
sudo apt-get install zeal
{%endhighlight%}

