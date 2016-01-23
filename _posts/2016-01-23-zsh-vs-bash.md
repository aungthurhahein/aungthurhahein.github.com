---
layout: post
title: Why zsh?
thumb: https://camo.githubusercontent.com/5c385f15f3eaedb72cfcfbbaf75355b700ac0757/68747470733a2f2f73332e616d617a6f6e6177732e636f6d2f6f686d797a73682f6f682d6d792d7a73682d6c6f676f2e706e67
backgrounds: 
    - https://raw.githubusercontent.com/tannhuber/oh-my-zsh-budspencer/master/budspencer.png
categories: Tech    
tags: Linux
published: True

---
I've been using bash as primay shell since I started using linux. It's ok. Don't bother looking for a better solution until I ran into this blog post about <a href="http://code.joejag.com/2014/why-zsh.html">My favourite zsh features</a>. The following youtube video is form the same author of the blog post. TLDR people? Watch this one. 

{% youtube 1S3MUVIAieE %}

It seems pretty good for interactive tasks and that auto completion feature is a dope. 
So,I decided to give a try.

### Installation
For debian system, just install it with aptitude tool by

```
sudo apt-get install zsh
```

Details of installing *zsh* can be seen at <a href="https://github.com/robbyrussell/oh-my-zsh/wiki/Installing-ZSH">Installing ZSH</a>.

To replace the default shell to zsh, there are several ways to do it. However, I recommend installing *oh-my-zsh* and switching shell is done automically.

### Oh-my-zsh
<a href="https://github.com/robbyrussell/oh-my-zsh">oh-my-zsh</a> is an extension of zsh shell, which provides <a href="https://github.com/robbyrussell/oh-my-zsh/wiki/Themes">themes</a> and <a href="https://github.com/robbyrussell/oh-my-zsh/wiki/Plugins">plugins</a>. 

#### Installation 
 It can be installed using wget or curl by

```
sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```

OR 

```
sh -c "$(wget https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh -O -)"
```

if you encounter an authentication problem, it can be solved by downloading the *install.sh* file first and install it manually.


#### Features

So far, it's quite similar to bash with additional features. It's quite easy to adapt for bash users.
For coders, I think zsh is a better option than bash. check out this LevelTutsPlus youtube video about how themes and plugins can help developers to aid at cmd tasks.

{% youtube csJV1exZAjA %}

From my a week long experince with zsh, The following points can be made:

- It's fancy and looks better than bash.
- Plugins are helpful but too much plugins make the shell slow down.
- Developer related plugins are really intuitive and working nicely.
- Error prompting and giving feedbacks and predicted actions make it friendly.
- Opening files and some actions are slightly slower than bash. It might be the drawbacks of oh-my-zsh plugins.
- I am still exploring the usage of zsh features from this <a href="https://www-s.acm.illinois.edu/workshops/zsh/why.html">Zsh features</a>.

So, try it and I kinda believe that you will fall in love with it in no time.
Cheers!

