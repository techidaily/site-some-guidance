---
title: "Resolving 'Disk Utility Cannot Duplicate DVD Files': Proven Techniques"
date: 2024-08-27T00:36:41.984Z
updated: 2024-08-28T00:36:41.984Z
categories:
  - macxdvd
thumbnail: https://thmb.techidaily.com/992704407ab581931890c09cce338091c04f10f6ec09034fcef1854347c08c6c.jpg
---

## Resolving 'Disk Utility Cannot Duplicate DVD Files': Proven Techniques

[![macx video converter pro icon](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/icon11.png)](https://tools.techidaily.com/macxdvd/products/)

* [MacX Video Converter Pro](https://tools.techidaily.com/macxdvd/products/)
* [Guide](https://tools.techidaily.com/macxdvd/products/)
* [Support](https://tools.techidaily.com/macxdvd/products/)
* [Free Download](https://tools.techidaily.com/macxdvd/products/)



![](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/icon7.png) [Home](https://tools.techidaily.com/macxdvd/products/) \> [DVD](https://tools.techidaily.com/macxdvd/products/) \> [Decrypt DVD](https://tools.techidaily.com/macxdvd/products/) \> Disk Utility Won't Copy DVD

## Fix Disk Utility DVD Copy Errors and Copy Protected DVDs



![](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/icon6.png) By [Bella Brown](https://tools.techidaily.com/macxdvd/products/) ｜Last updated on September 26, 2023

* [![](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/share-fa.jpg)](https://www.facebook.com/sharer/sharer.php?u=https://www.macxdvd.com/mac-dvd-video-converter-how-to/disk-utility-wont-copy-dvd-fixed.htm)
* [![](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/share-tw.jpg)](https://twitter.com/intent/tweet?url=https://www.macxdvd.com/mac-dvd-video-converter-how-to/disk-utility-wont-copy-dvd-fixed.htm&text=)
* [![](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/share-email.jpg)](https://www.macxdvd.com/mac-dvd-video-converter-how-to/mailto:info@example.com?&subject=&body=https://www.macxdvd.com/mac-dvd-video-converter-how-to/disk-utility-wont-copy-dvd-fixed.htm)
* [![](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/share-in.jpg)](https://www.linkedin.com/shareArticle?mini=true&url=https://www.macxdvd.com/mac-dvd-video-converter-how-to/disk-utility-wont-copy-dvd-fixed.htm&title=&summary=&source=)

_"I am trying to copy a DVD using Disk Utility. I do all the steps: open Disk Utility > Choose DVD > New Image From Name of Disc, Save, all that. But every time it copies, it inevitably fails, giving the same error message 'The operation couldn't be completed. (com.apple.diskutility error 3.)'."_

This is a user on Apple Communities who can't copy a DVD with Disk Utility. In fact, besides com apple diskutility error 3, there are many other errors like operation failed with status 5, error status 27, "cannot copy - input/output error", stuck screen loading disks with a spinner graphic, etc. that prevent Disk Utility to copy a DVD on Mac successfully. In this post, we're going to solve all these Disk Utility DVD copy errors and let you copy protected DVDs on Mac without trouble.

![disk utility copy DVD error](https://www.macxdvd.com/mac-dvd-video-converter-how-to/article-image/disk-utility-error.jpg) 

## Understand the Limitations of Disk Utility

Before we start to fix Disk Utility DVD copy errors, there are some limits that you should know. Make sure they are not the reasons to "Disk Utility will not copy DVD" issues. 

1. Apple products including iDVD, DVD Studio Pro, Disk Copy, and Disk Utility **can't copy DVDs with protections**. So if you're trying a commercial disc, it may give your problems like cannot copy - input/output error. If you want to [copy protected DVD to Mac](https://tools.techidaily.com/macxdvd/products/), you will the help from a third-party helper.
2. You **can't** burn DVD using Disk Utility anymore if you're running **OS X 10.11 or later** as Apple has removed the burning functionality since El Capitan.
3. You should know that Disk Utility is a great tool to create disk image of a DVD, portable drive or desktop drive. The CDR image is a DVD/CD Master file used to create DVD copies, **not a playable** video format or the like.

## When Disk Utility will Not Copy DVD, You May Try:

**1\. Kill the FSCK process** 

Killing the FSCK process has solved many Disk Utility DVD copy errors, especially errors like Disk Utility won't load discs... 

in terminal  
 ps -ef | grep fsck

* $ ps -ef|grep fs
* 0 55 1 0 3:39PM ?? 0:03.45 /System/Library/Frameworks/CoreServices.framework/Versions/A/Frameworks/FSEvent s.framework/Versions/A/Support/fseventsd
* 0 110 1 0 3:39PM ?? 0:00.02 autofsd
* 0 126 1 0 3:39PM ?? 0:01.44 /usr/sbin/cfprefsd daemon
* 501 326 1 0 3:39PM ?? 0:01.47 /usr/sbin/cfprefsd agent
* 0 14893 86 0 4:45PM ?? 1:41.64 /System/Library/Filesystems/hfs.fs/Contents/Resources/./fsck\_hfs -y /dev/disk2s2
* 501 18726 3828 0 5:02PM ttys000 0:00.00 grep fs

Then sudo kill the fsck process. Once the fsck process is killed, the Disk Utility should restart and copy the DVD as expected. 

**2\. Reset PRAM/NVRAM or SMC**

Resetting the PRAM/SMC is a way to clear corrupted files related to stuff like RAM disk, Disk cache, Startup disk, etc. It can also help solve many DVD playback and copy problems on Mac like [Mac DVD player not responding](https://tools.techidaily.com/macxdvd/products/). Also there are users reported that they successfully solved Disk Utility DVD copy errors by resetting them.

Reset the SMC: shut down the Mac > press and hold the power button for 10s and restart > press and hold the right Shift, Option and left Control key for 10s > keep holding the keys and then press and hold the Power button for 10s > then release and wait for seconds > restart. 

Reset the NVRAM/PRAM: shut down the Mac > press the Power button > before you see a grey screen, press the Command, Option, P and R keys at the same time until you see a grey screen > keep holding the keys until the Mac restarts and hear a second startup chime > release.

**3\. Restart the computer in Safe Mode**

Restart the computer in Safe Mode: restart your Mac, press and hold the Shift key when it lights up > release it when you see the login screen. Then restart again and check if it solves com apple diskutility error 3 DVD/status 5 or the like. 

If this doesn't help, then boot to the Recovery Mode: Restart the computer and press and hold down the COMMAND and R keys once you hear the startup chime. Keep holding the keys until the Apple logo appears. After several minutes, the Utilities menu screen appears.

**4\. Copy DVD from folder**

If Disk Utility will not copy DVD to disk image, as reported by a user on Apple Communities, you can copy all the contents of the DVD to, for example VIDEO\_TS folder or ISO image (but since El Capitan, you can no longer just drag disk images from the Finder into Disk Utilities; instead, you must choose the relevant image using the File > Open Disk menu). Then use Disk Utility > click New Image > Create new image from folder.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## If Disk Utility will Not Copy DVD, Try MacX (Any DVD Supported) 

The above are the methods that are reported to be efficient to fix part of Disk Utility DVD copy errors like com apple diskutility error 3, status 5, etc. Trying the above fixes may cost you a lot of time and energy as some of them are quite complicated. Most importantly, they won't fix all the "Disk utility won't copy DVD" issues. If you can't fix it or want to bypass the limits of Disk Utility (Disk Utility won't copy protected DVDs, limited output formats), use[**MacX DVD Ripper Pro**](https://tools.techidaily.com/macxdvd/products/) to copy DVDs.

* Four DVD copy modes: clone DVD to ISO image in 1:1 ratio, copy the main title/full title to MPG, backup DVD to MKV.
* Create digital copies of DVDs in any formats: MP4, HEVC, MOV, AVI, WMV, MP3, other video/audio formats and Mac, PC, iPhone, iPad, TVs, 350+ other devices.
* Support DVDs of any types: discs protected with Region, RCE, CSS, Disney-X project, Sony ARccOS, UOPs, etc. as well as scratched DVDs, latest titles, workout DVDs, etc.
* Unique Level-3 Hardware Acceleration enables 47x real-time faster to convert DVD to MP4!
* Safe Mode and special title check mechanism bypass any errors with Disk Utility when you copy DVD.

[Download for Mac](https://tools.techidaily.com/macxdvd/products/) [Download for PC](https://tools.techidaily.com/macxdvd/products/) 

**Step 1.** Insert the DVD that Disk utility will not copy into the computer. Run the program and click the Disc button to load the DVD. 

**Step 2.** Once loaded, it will automatically detect the correct title of the DVD and then pop up a window asking you to select and output format. 

* To copy a DVD to DVD: select DVD Backup > [copy DVD to ISO Image](https://tools.techidaily.com/macxdvd/products/). You will get a 1:1 image copy and then you can burn it to a blank disc using Finder.
* To simply copy a DVD to Mac: select Backup > Main Title/Full title will do. These options are faster than ISO image and will contain the main content of the DVD.
* To copy a DVD for eaier playback on other devices: select General Profiles > choose MP4 or other video formats. Or you can find the exact profile for your device.

![Copy a DVD for macOS](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../mac-dvd-ripper-pro/step-images/dvd-to-iso-700.jpg) 

<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398457/3022" target="_top" id="398457"><img src="//a.impactradius-go.com/display-ad/3022-398457" border="0" alt="www.sentrypc.com" width="980" height="120"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398457/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
**Step 3.** Click Run to start the DVD copy.

_Disclaimer: This post is to help users whose Disk Utility will not copy DVD or get com apple diskutility error 3 status 5, input/output error, or the like. It does not in any way advocate copying a DVD for any commercial or other illegal use. Please consult the law in your country before you copy any disc._

ABOUT THE AUTHOR

![author- bella](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/bella.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726960&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/forexrobotronbox.gif" border="0">Forex Robotron Basic Package</a>
<!-- affiliate ads end -->
[Bella Brown ![](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/share-in1.jpg)](https://www.linkedin.com/in/bella-brown-920145104/) 

Bella has been working with DVD digitization for over 12 years. She writes articles about everything related to DVD, from disc drive, DVD copyright protection, physical structure, burning and backup tips. The unceasing passion of DVD movies helps her build a rich DVD library and ensure a practical solution to address almost all possible DVD issues. Bella is also a crazy fan for Apple products.



Related Articles

![](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/pic7.jpg)

<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=27889512&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/728__90.jpg" border="0"></a>
<!-- affiliate ads end -->
[Top 10 Free DVD Copy Software Burning Freeware for PC Mac](https://tools.techidaily.com/macxdvd/products/) 

![](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/pic6.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4737285&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/b2f83c409ce63012229fb9cd465bdcfe/products/copy_reporting_system.png" border="0">  KoolReport Pro  is an advanced solution for creating data reports and dashboards in PHP. Equipped with all  extended packages , KoolReport Pro is able to connect to various datasources, perform advanced data analysis, construct stunning charts and graphs and export your beautiful work to PDF, Excel, JPG or other formats. Plus, it includes powerful built-in reports such as pivot report and drill-down report which will save your time in building ones. 

 It will help you to write dynamic data reports easily, to construct intuitive dashboards or to build a whole business intelligence cockpit. 

  KoolReport Pro  package goes with Full Source Code, Royal Free, ONE (1) Year Priority Support, ONE (1) Year Free Upgrade and 30-Days Money Back Guarantee. 

  Developer License  allows  Single Developer  to create Unlimited Reports, deploy on Unlimited Servers and able deliver the work to Unlimited Clients. </a>
<!-- affiliate ads end -->
[DVD Won't Play with "Supported Disc Not Available" Error](https://tools.techidaily.com/macxdvd/products/) 

![](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/pic5.jpg)

[Fix "Can't Rip Lionsgate DVDs" or Rip Protected DVDs Smoothly](https://tools.techidaily.com/macxdvd/products/) 

![](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/pic4.jpg)

[Best DVD Decrypters for Mac - 100% Work to Rip Protected DVD Movies](https://tools.techidaily.com/macxdvd/products/) 

![](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/pic3.jpg)

<!-- affiliate ads begin -->
<a href="https://store.advancedwebranking.com/order/checkout.php?PRODS=4715051&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/14edc6ebfdae2e23bbed83d67f50e983/products/33_awr%20logo.png" border="0"></a>
<!-- affiliate ads end -->
[How to Rip Protected DVD Movies on Mac for FREE](https://tools.techidaily.com/macxdvd/products/) 

![](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/pic2.jpg)

[Fixed: Can't Rip Sony DVDs with Bad Sectors](https://tools.techidaily.com/macxdvd/products/) 



![Digiarty Software](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../icon/logo.png) 

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1047974&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-04_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
Digiarty Software, Inc. (MacXDVD) is a leader in delivering stable multimedia software applications for worldwide users since its establishment in 2006.

### Hot Products

* [MacX DVD Ripper Pro](https://tools.techidaily.com/macxdvd/products/)
* [MacX Video Converter Pro](https://tools.techidaily.com/macxdvd/products/)
* [MacX MediaTrans](https://tools.techidaily.com/macxdvd/products/)

### Tips and Tricks

* [DVD Topics >>](https://tools.techidaily.com/macxdvd/products/)
* [Video Solutions >>](https://tools.techidaily.com/macxdvd/products/)
* [Data Transfer >>](https://tools.techidaily.com/macxdvd/products/)
* [Online Video >>](https://tools.techidaily.com/macxdvd/products/)
* [Hot Topics >>](https://tools.techidaily.com/macxdvd/products/)

### Company

* [About Us >>](https://tools.techidaily.com/macxdvd/products/)
* [Tech & Sales FAQ >>](https://tools.techidaily.com/macxdvd/products/)
* [User Guides >>](https://tools.techidaily.com/macxdvd/products/)
* [Contact Us >>](https://tools.techidaily.com/macxdvd/products/)
* [Partner >>](https://tools.techidaily.com/macxdvd/products/)



[Home](https://tools.techidaily.com/macxdvd/products/) | [About](https://tools.techidaily.com/macxdvd/products/) | [Privacy Policy](https://tools.techidaily.com/macxdvd/products/) | [Terms and Conditions](https://tools.techidaily.com/macxdvd/products/) | [License Agreement](https://tools.techidaily.com/macxdvd/products/) | [Resource](https://tools.techidaily.com/macxdvd/products/) | [News](https://tools.techidaily.com/macxdvd/products/) | [Contact Us](https://tools.techidaily.com/macxdvd/products/)

Copyright © 2024 Digiarty Software, Inc (MacXDVD). All rights reserved

Apple, the Apple logo, Mac, iPhone, iPad, iPod and iTunes are trademarks of Apple Inc, registered in the U.S. and other countries.  
Digiarty Software is not developed by or affiliated with Apple Inc.

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>


