---
title: Clean uninstall packages with debfoster tool
layout: post
backgrounds:
    - http://wallpapercave.com/wp/Ff5OJkT.png
    - http://www.kucuu.com/desktop-wallpaper-home/Purple-Ubuntu-Desktop-Wallpaper-1366x768.jpg
    - http://cdn.le-libriste.fr/wp-content/uploads/2012/03/ubuntu_u_wallpaper_by_rikulu-d3iid8f.png
thumb: http://tcphub.com/wp-content/uploads/2015/10/Linux-OS.jpg
date: 2014-02-11 18:12:49
tags: Linux
category: Tech
---

One problem that can leave your system unstable is dependencies or orphaned packages leaving after you uninstall a package.

This problem  can be solved by installing a tool called **debfoster**. It tracks what you have installed and ask you to uninstall dependencies files when you uninstalled a program. 

{% highlight bash%}
//install
sudo apt-get install debfoster

//help
sudo debfoster --help

//create initial keeper
sudo debfoster -q

//system to conform to keeper
sudo debfoster -f

//check orphaned/dependencies files
sudo debfoster

{% endhighlight %}

More information: <a href="http://ubuntuforums.org/showthread.php?t=24403" target="_blank">using debfoster in practice</a>
