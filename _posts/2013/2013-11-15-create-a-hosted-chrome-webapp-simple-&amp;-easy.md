---
title: "Create a hosted Chrome webapp: Simple & Easy"
layout: post
backgrounds:
    - http://40.media.tumblr.com/ac9d3c7eeed9e7271efe5e0d9b88ae2d/tumblr_nqx8chHbKD1tubinno1_1280.jpg
    - https://images.unsplash.com/photo-1444837881208-4d46d5c1f127?fit=crop&fm=jpg
    - https://images.unsplash.com/photo-1440688807730-73e4e2169fb8?fit=crop&fm=jpg
thumb: https://uploads.disquscdn.com/images/df562a9e408784f9efe97430afd796d4ca08325dd26fcc9167a43de47951220e.png
date: 2013-11-15 01:28:55
tags: Browser
category: Tech
---

There are three types of chrome web apps:

1.	hosted app,which run on their own hosted server
2.	package app,that is app which downloaded the entire app and run on your browser(offline functionality)
3.	Extension is an extension for chrome browser
   
ok!Now,let’s see what we need for hosted chrome app.

 
### Manifest.json

The first thing we have to do is create a manifest.json file. This is the template of how manifest.json look alike.
{% highlight JSON%}
{
 "name": "CFML 10 Reference",
 "description": "Find your CFML 10 tags",
 "version": "1",
 "omnibox": { "keyword" : "cfml" },
 "manifest_version": 2,
 "background": {
 "scripts": ["background.js"]
 },
 
 "app": {
 "urls": [
 "*://help.adobe.com/en_US/ColdFusion/10.0/CFMLRef/index.html",
 "*://help.adobe.com/en_US/ColdFusion/10.0/CFMLRef/index.html"
 ],
 "launch": {
 "web_url": "http://help.adobe.com/en_US/ColdFusion/10.0/CFMLRef/index.html"
 }
 },
 
 "icons": {
 "16": "favicon.png",
 "128": "cf10.png"
 },
 
 "permissions": [
 "unlimitedStorage",
 "notifications"
 ]
}
{% endhighlight %}


### Icons

The next step is you need icons for your app.the first one is favicon(16px*16px) and the other is for the icon(128px *128px) on chrome’s new tab.
After that,you put these files altogether into a folder and name whatever you want.Now,you can test your application with chrome.

Go to chrome > settings > extensions > check developer mode and click on “load unpacked extension”. Choose the folder you created via file explorer.(there might be slightly variations according to chrome versions.)

If something wrong with your app,chrome gonna show you a pop-up message and give you the error message.
If you want a more detailed example.take a look at this <a href="http://londonwebstorenight.appspot.com/webstore/countdown/index.html" target="_blank">countdown app tutorial</a>.

The first tutorial I learned is <a href="http://developer.chrome.com/trunk/apps/first_app.html" target="_blank"> Chrome official helloworld! tutorial</a>.
Moreover,google also offers bunch of <a href="http://developer.chrome.com/trunk/apps/samples.html" target="_blank">sample apps</a>. So,you can download it and try it in your browser and see how they works.
It’s easy and fun and you can build your site’s chrome app within half an hour for sure.


