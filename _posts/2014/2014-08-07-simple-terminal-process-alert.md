---
title: Simple terminal process alert
layout: post
backgrounds: 
    - https://images.unsplash.com/photo-1429743433956-0e34951fcc67?ixlib=rb-0.3.5&q=80&fm=jpg
thumb: http://www.geeky-gadgets.com/wp-content/uploads/2015/01/Raspberry-Pi-Linux-Console.jpg
date: 2014-08-07
tags: Linux
category: Tech
---

For people who are working with terminal all the time, you runs pipeline and tasks and you don't know whethere it's finished or not. This small trick will alert you.

{%highlight bash%}
#step1: install espeak
$sudo apt-get install espeak

#step2: try 
espeak "Hello World"

#step3: create several alias to reuse for different alert messages
#success process
alias sp='espeak "process finished successfully"'
#fail process
alias fp='espeak "process failed"'

#example usage

 #!/bin/bash
 if [ "foo" = "foo" ]; then
    echo expression evaluated as true
    sp
 else
    echo expression evaluated as false
    fp
 fi

 {%endhighlight%}
