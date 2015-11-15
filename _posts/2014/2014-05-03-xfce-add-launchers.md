---
title: how to add new custom application launcher at xfce environment
layout: post
backgrounds:
    - http://data.hdwallpapers.im/big_xfce.jpg
thumb: https://i.warosu.org/data/g/img/0508/52/1445054033824.png 
date: 2014-05-03
tags: Linux
category: Notes
---
Now, my choice of desktop environment for Linux production machine is xfce. I am stuck at making new custom launcher because it is missing in my whisker menu somehow. 

For guys who having same problem, this is the command to get create launcher wizard for xfce. 

{%highlight bash%}
$ gksu -l 'exo-desktop-item-edit --create-new /usr/share/applications/'
{%endhighlight%}



