---
title: 'Pomodoro timer for terminal'
layout: post
backgrounds:
    - https://images.unsplash.com/38/awhCbhLqRceCdjcPQUnn_IMG_0249.jpg?fit=crop&fm=jpg
thumb: https://upload.wikimedia.org/wikipedia/commons/3/34/Il_pomodoro.jpg
date: 2014-12-28
tags: Personal Programming Productivity
category: Tech
---

 Last night, I was wondering about availability of pomodoro timer for terminal. I saw several results with various technology.

* <a href="https://github.com/Juev/terminal-pomodoro" target="_blank"> terminal-pomodoro</a> with node.js
* <a href="http://magnatecha.com/very-simple-pomodoro-timer-for-a-terminal/" target="_blank">A very simple Pomodoro timer for a terminal</a> with bash script
* <a href="https://github.com/ggustafsson/Tim" target="_blank">Tim (Timer Script)</a> with Zsh script

What about python? I want the small tool which gives me visual and also audio notification. If I am away from terminal, audio notification is good for reminders. 

#### <a href="https://github.com/aungthurhahein/pomodoro_python" target="_blank">Pomodoro_Python V. 1.0</a>

So, I decided to implement a simple pomodoro timer with python. The code is roughly around ~50 lines but depends on SOX sound processor.

It should be working properly with *nix system and I will tested with Windows system soon. 

#### Plan for Version 2.0

I am planning to use argparse module to handle user customized parameters  and also additional features such as logging the activity in a flat file, taking session information and various notification schemes and so on.
 



