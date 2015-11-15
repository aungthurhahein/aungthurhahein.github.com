---
title: How to clone VMWare Player GuestOS
layout: post
backgrounds:
    - http://pix.toile-libre.org/upload/original/1318856119.png
thumb: http://blogs.vmware.com/kb/files/2015/05/vmware_cloud_logo.jpg
date: 2014-05-07
tags: Linux 
category: Tech
---

Unlike Virtualbox, there is no easy way to clone the GuestOS of VMWare VM.

These are the steps to perform to get a clone of desire VM.

1.  Copy/Paste the entire folder of VM you want to clone to another instance. E.g. Copy all the files from *Windows 8 x64* to a new folder,let say *windows 8 Clone*.
2. Replace all file names with *Windows 8 x64* to *windows 8 Clone*. E.g file name of *Windows 8 x64.vmdk* to *Windows 8 Clone.vmdk* and so on.
3. Edit .vmx and .vmxf file with preferred text editor and replace all occurrences of *Windows 8 x64* with *Windows 8 Clone*.
4. Now open VMWare Player and play the new cloned VM. If it doesn't display in the VM list, open it from the file menu.
5. You will get a pop-up window and click *I copied it* button. 

