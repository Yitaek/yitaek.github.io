---
layout: post
section-type: post
title: SSD + RAM Upgrade
category: tech
tags: [ 'tutorial']
---

<script src="//cdnjs.cloudflare.com/ajax/libs/highlight.js/8.2/highlight.min.js"></script>
<script>hljs.initHighlightingOnLoad();</script>

This week, I decided to give my Macbook Pro (mid-2012) a hardware upgrade. Although I was patient enough to tolerate the intense lags when I used SolidWorks or Quartus, when it began to take too long to open up the new versions of Microsoft Office, I knew it was time for an upgrade.

For a more detailed specs of what I used to have, check out: <a href="https://support.apple.com/kb/sp694?locale=en_US">Macbook Pro (15-inch, Mid-2012)</a>

<h3>List of Parts</h3>

<a href="https://www.amazon.com/Samsung-850-EVO-2-5-Inch-MZ-75E500B/dp/B00OBRE5UE/ref=sr_1_2?ie=UTF8&qid=1469840722&sr=8-2&keywords=ssd+samsung+850+evo">• Samsung 850 EVO - 500 GB </a><br>
<a href="https://www.amazon.com/gp/product/B005LDLVAO/ref=oh_aui_detailpage_o01_s00?ie=UTF8&psc=1">• Crucial 16GB kit</a><br>
<a href="https://www.amazon.com/gp/product/B00HJZJI84/ref=oh_aui_detailpage_o02_s00?ie=UTF8&psc=1">• StarTech USB 3.0 to 2.5" SATA Cable</a><br>
• Philips #00 Screwdriver <br>
• Torx T6 Screwdriver <br>
• USB Stick

<h3>Preparations</h3>
In case the procedure goes wrong, I backed up my data to an external hard drive first. Some people use Carbon Copy Cloner or similar software to clone all the data, but I'm a poor recent college grad, so I just used Apple's Time Machine. While the data was being backed up, I made a bootable USB with a copy of El Capitan OS X.

First, the USB stick has to be properly formatted. Access Disk Utility, select the USB, and click Erase with the correct Format: Mac OS X Extended (journaled) and GUID Partition Table. A step-by-step guide with pictures are found <a href="http://www.macworld.com/article/2055589/storage/how-to-format-a-startup-drive-for-a-mac.html#slide2">here</a>. I left the USB <b>Untitled</b>. Next, I redownloaded the El Capitan Installer from the App Store. Finally, open Terminal and run the following code to complete the process:

<pre><code data-trim="" class="c">sudo /Applications/Install\ OS\ X\ El\ Capitan.app/Contents/Resources/createinstallmedia --volume /Volumes/Untitled --applicationpath /Applications/Install\ OS\ X\ El\ Capitan.app
</code></pre><br>
Make sure you can boot off the USB before trying anything else. Otherwise you will get a screen with a gray, crossed out circle indicating that the Mac cannot find an OS.

<h3> Installing the SSD</h3>

I followed the directions here to install my SSD, but before you close the lid up, also install the new RAM.

<iframe width="560" height="315" src="https://www.youtube.com/embed/jBgjnIv0a7w" frameborder="0" allowfullscreen></iframe><br>

<h3> Installing the RAM </h3>

<iframe width="560" height="315" src="https://www.youtube.com/embed/k9oCMLoTAc8" frameborder="0" allowfullscreen></iframe>

<br>
Now you have a faster Macbook that's good as new!
<br>

