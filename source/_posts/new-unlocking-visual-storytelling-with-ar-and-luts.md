---
title: "[New] Unlocking Visual Storytelling with AR & LUTs"
date: 2024-08-21T20:14:00.118Z
updated: 2024-08-22T20:14:00.118Z
tags: 
  - screen-recording
  - ai video
  - ai audio
  - ai auto
categories: 
  - ai
  - screen
description: "This Article Describes [New] Unlocking Visual Storytelling with AR & LUTs"
excerpt: "This Article Describes [New] Unlocking Visual Storytelling with AR & LUTs"
keywords: "AR Storytelling Tech,Augmented Reality Insight,VR Narrative Tools,Lighting LUTs in AR,AR Visual Effects,Creative AR Applications,Enhancing Stories with AR"
thumbnail: https://thmb.techidaily.com/6ceaa9d96bf5780755ddbca816a35f96a83ab3ae5f8b95d2f15a6366810c2463.png
---

## Unlocking Visual Storytelling with AR & LUTs

Color LUTs (Lookup Textures) are tables of RGB color values. In Spark AR, you can use color LUTs to quickly create color gradation effects throughout the scene. Go through the article and create your color LUT effect.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726960&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/forexrobotronbox.gif" border="0">Forex Robotron Basic Package</a>
<!-- affiliate ads end -->
## Part 1\. What are Luts in Spark AR used for?

To create a color filter effect in [Spark AR](https://sparkar.facebook.com/ar-studio/), you need a color LUT in Spark AR.

To develop AR effects for mobile cameras, you can use the Mac and Windows augmented reality platform Spark AR Studio. Imagine it like Sketch or Photoshop for augmented reality. The color values of the camera texture are mapped to the x, y, and z coordinates of the location in the color LUT. This location contains a corresponding output color that is drawn over the scene to create a color gradient effect.

![create a color gradient effect](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-1.jpg)

<!-- affiliate ads begin -->
<a href="https://ship7com.pxf.io/c/5597632/1509856/17634" target="_top" id="1509856"><img src="//a.impactradius-go.com/display-ad/17634-1509856" border="0" alt="" width="730" height="383"/></a>
<!-- affiliate ads end -->
## Part 2\. How to use LUTs in Spark AR?

**How to apply a color LUT to the whole scene in Spark AR:**

##### Step1Add a color LUT to your project

1. In the Assets panel, click Add Asset.
2. Select Import, then Color LUT, and select your file from your computer.

When you import a color LUT, compression is always set to None, and filtering is set to Low by default.

##### Step2Apply to the whole scene

1. In the Assets panel, right-click the LUT color.
2. Select Actions and then **Apply to Camera**.

A patch graph is automatically set that applies a color LUT to the entire scene.

![apply to the whole scene](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-2.jpg)

**The color LUT patch graph**

The patch graph that renders the color gradation effect looks like this:

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-writer-free-word-processor-1x.3d9c80d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
![color lut patch graph](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-3.jpg)

**To create the effect:**

* Fix Scene Render Pass renders cameraTexture0 and all objects in the scene that are children of the device. This creates the output texture.
* ColorLUTShader looks up the RGBA values of this texture in the Tension color LUT array and converts them to a new green color. This will change the texture and create a gradient effect.
* Finally, the Screen Output patch renders the green color.

<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892108/21290" target="_top" id="1892108"><img src="//a.impactradius-go.com/display-ad/21290-1892108" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892108/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Part 3\. Free LUTs resource for Spark AR

Here are the best free LUTs resources for Spark AR:

### 1\. [Frost Zombie (Technical Showcase)](https://we.tl/t-1uj4wJKluG)

Client filter pieces occasionally end up on the scrap heap. It was a poor Frost Zombie in this instance. Since this is one of my simpler filters, I felt it was okay to publish the build information. Four objects make up much of the scene: an EyeColor block, a custom canvas segmentation, a face mesh, and an emitter for the breath mist (my personal favorite). To show the layers used in generating the primary zombie texture, I also moved to Substance Painter. This is a demonstration of my methods rather than a step-by-step manual.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4531356&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8fdd149fcaa7058caccc9c4ad5b0d89a/products/tss-box.JPG" border="0">The Tube Sites Submitter is a fast and efficient tool for anyone who needs to upload videos quickly, easily and automatically to hundreds of tube sites in mere minutes . </a>
<!-- affiliate ads end -->
![frost zombie](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-4.jpg)

### 2\. Fur

Here are the key building principles.

* Geometric layers, often known as shells, produce depth.
* Normals is used to create shells from a single mesh.
* Alpha decreases with each shell.
* Deeper shells are darker.
* Height is generated from a single grayscale channel.
* No fur is generated in the black areas of the height texture.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087264/19272" target="_top" id="2087264"><img src="//a.impactradius-go.com/display-ad/19272-2087264" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087264/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![fur](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-5.jpg)

### 3\. Shockwave

Even while using large image sequences is frequently discouraged, you can still use them to make some extremely spectacular effects! I'll explain how the screen tap computation procedure relates to texture position in this walkthrough. If you want to apply this approach and texture sequence in your projects or give it a try.

<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/336__280a.jpg" border="0"></a>
<!-- affiliate ads end -->
![shockwave](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-6.jpg)

### 4\. Transition Curves

There are 11 distinct animation curves included with Spark AR in the Transition patch. Here is a helpful visual aid because it might be challenging to distinguish between a quartic and a quintic when working on a project. With the SDF circle doubled (to sharpen the edge) and inserted into the Patch Pack's alpha channel, the circles are likewise straightforward rectangles. Since RGB values are three times one, the object is white.

![transition curves](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-7.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37540879&QTY=1&AFFILIATE=108875&CART=1"><img src="https://paperscan.orpalis.com/img/content/You_prefer_to_use.png" border="0">PaperScan Professional： PaperScan Scanner Software is a powerful TWAIN & WIA scanning application centered on one idea: making document acquisition an unparalleled easy task for anyone.</a>
<!-- affiliate ads end -->
### 5\. Realistic Smoke

By adding smoke to a scene, you can easily add a lot of detail and realism. Nothing revolutionary is happening here. The particle emitter creates flat planes of smoke texture that are forced upward. The force slowly shifts left and right as seen in the patch editor. The Fade particle script (created by Josh Beckwith) enlarges the particles and fades them out at the same time.

![realistic smoke](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-8.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068425/7443" target="_top" id="2068425"><img src="//a.impactradius-go.com/display-ad/7443-2068425" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068425/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 6\. Rainbow Glitter

Given how beautifully Glitter Rain was received, I believed it would be fitting to broaden the potential with an HDR setting. While Glitter Rain made use of two different colors, this technique makes use of an entirely colorless substance and gets its color information via HDR.

![rainbow glitter](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-9.jpg)

### Closing Thoughts

Spark AR is an amazing website for LUTs and color grading. Whether you're a new student or a seasoned pro, Spark AR Studio has all the features and capabilities you need to become a good video editor. You can download free LUTs from Spark AR and apply them to your videos. The article guides on how to use LUTs in Spark AR and how to download free LUTs. So, Spark AR is one of the best online websites for LUTs I have tried.

[Free Download](https://tools.techidaily.com/wondershare/filmora/download/)For Win 7 or later(64-bit)

[Free Download](https://tools.techidaily.com/wondershare/filmora/download/)For macOS 10.14 or later

[Free Download](https://tools.techidaily.com/wondershare/filmora/download/)For macOS 10.14 or later

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

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






<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://some-techniques.techidaily.com/new-in-depth-synopsis-gopro-slr4-sliver-camera-review/"><u>[New] In-Depth Synopsis  GoPro SLR4 Sliver Camera Review</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-syncing-voice-with-images-online-for-2024/"><u>[New] Syncing Voice with Images Online for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-the-art-of-blending-audio-with-video-in-premiere-pro/"><u>[New] The Art of Blending Audio with Video in Premiere Pro</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-unlocking-windows-10-indispensable-hacks-and-fixes/"><u>[New] Unlocking Windows 10  Indispensable Hacks & Fixes</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-2024-approved-automatic-youtube-playback-made-simple-for-social-networking-sites-like-facebook/"><u>[Updated] 2024 Approved  Automatic YouTube Playback Made Simple for Social Networking Sites Like Facebook</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-groupcapture-hd-toolkit-fb-edition/"><u>[Updated] In 2024, GroupCapture HD Toolkit, FB Edition</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-key-elements-for-compelling-facebook-ad-textual-content-for-2024/"><u>[Updated] Key Elements for Compelling Facebook Ad Textual Content for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-master-upside-down-and-sideways-iphone-photo-rotation/"><u>[Updated] Master Upside-Down and Sideways iPhone Photo Rotation</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-streamlining-your-video-collection-converting-mp4-with-vlc/"><u>[Updated] Streamlining Your Video Collection  Converting MP4 with VLC</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-path-to-pure-audio-pazera-free-tool-review/"><u>[Updated] The Path to Pure Audio  Pazera Free Tool Review</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-ultimate-list-of-twitter-video-convertors/"><u>[Updated] The Ultimate List of Twitter Video Convertors</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-top-vr-films-that-you-should-never-miss/"><u>[Updated] Top VR Films That You Should Never Miss</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-transforming-mobile-devices-into-business-and-personal-video-platforms-for-2024/"><u>[Updated] Transforming Mobile Devices Into Business & Personal Video Platforms for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-ultimate-8-filtration-options-for-professional-streams/"><u>[Updated] Ultimate 8 Filtration Options for Professional Streams</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-understanding-apples-audio-content-guidelines/"><u>[Updated] Understanding Apple’s Audio Content Guidelines</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-unlocking-the-potential-of-your-youtube-channel-subscribers/"><u>[Updated] Unlocking the Potential of Your YouTube Channel (Subscribers)</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-unveiling-30-preferred-steadicam-models-for-high-quality-dslr-projects/"><u>[Updated] Unveiling 30 Preferred Steadicam Models for High-Quality DSLR Projects</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-unveiling-the-best-ways-to-watch-360-videos-on-android/"><u>[Updated] Unveiling the Best Ways to Watch 360 Videos on Android</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-virtual-warriors-journey-7-intense-fps-games-for-2024/"><u>[Updated] Virtual Warriors’ Journey - 7 Intense FPS Games for 2024</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/approved-achieving-affiliate-success-with-online-videos/"><u>2024 Approved  Achieving Affiliate Success with Online Videos</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-streamline-shipment-5-methods-of-transporting-files/"><u>2024 Approved  Streamline Shipment  5 Methods of Transporting Files</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-the-ace-guide-to-smooth-laptop-video-editing-via-inshot/"><u>2024 Approved  The Ace Guide to Smooth Laptop Video Editing via Inshot</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-understanding-livestream-technology-explained/"><u>2024 Approved  Understanding Livestream Technology Explained</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-uniting-your-soundtrack-sets-from-different-spaces/"><u>2024 Approved  Uniting Your Soundtrack Sets From Different Spaces</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-unleash-potential-discovering-free-onlineoffline-animations/"><u>2024 Approved  Unleash Potential  Discovering Free Online/Offline Animations</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-unleash-the-power-of-online-livestreams-with-us-today/"><u>2024 Approved  Unleash the Power of Online Livestreams with Us Today</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-unlock-creative-potential-macs-top-free-drawing-tools/"><u>2024 Approved  Unlock Creative Potential  Mac's Top Free Drawing Tools</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-unlock-potential-with-free-premiere-pro-plans/"><u>2024 Approved  Unlock Potential with Free Premiere Pro Plans</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/4-easy-ways-for-your-xiaomi-redmi-13c-5g-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>4 Easy Ways for Your Xiaomi Redmi 13C 5G Hard Reset | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/best-motorola-edge-40-pattern-lock-removal-tools-remove-android-pattern-lock-without-losing-data-by-drfone-android/"><u>Best Motorola Edge 40 Pattern Lock Removal Tools Remove Android Pattern Lock Without Losing Data</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/crafting-your-instagram-business-blueprint-for-2024/"><u>Crafting Your Instagram Business Blueprint for 2024</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/finalcut-pro-101-crafting-professional-youtube-edits/"><u>FinalCut Pro 101  Crafting Professional YouTube Edits</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-tips-for-finding-christian-choir-songs-online-and-personalizing-them/"><u>In 2024, Tips for Finding Christian Choir Songs Online & Personalizing Them</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-tricks-to-download-twitter-videos-and-turn-into-mp3-files/"><u>In 2024, Tricks to Download Twitter Videos and Turn Into MP3 Files</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-ultimate-list-low-cost-high-definition-cameras/"><u>In 2024, Ultimate List  Low-Cost, High Definition Cameras</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-unveil-the-art-of-creating-astonishing-gopro-time-lapse-videos/"><u>In 2024, Unveil the Art of Creating Astonishing GoPro Time-Lapse Videos</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-2024-approved-unleash-your-creativity-10-public-domain-image-sites/"><u>New 2024 Approved Unleash Your Creativity 10 Public Domain Image Sites</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/online-streaming-capture-a-comprehensive-guide/"><u>Online Streaming Capture  A Comprehensive Guide</u></a></li>
<li><a href="https://fox-that.techidaily.com/1721474268860-safari-image-woes-beat-the-glitch-discover-9-reliable-strategies-for-iphone-users/"><u>Safari Image Woes? Beat the Glitch: Discover 9 Reliable Strategies for iPhone Users.</u></a></li>
<li><a href="https://location-social.techidaily.com/set-your-preferred-job-location-on-linkedin-app-of-your-apple-iphone-se-2022-drfone-by-drfone-virtual-ios/"><u>Set Your Preferred Job Location on LinkedIn App of your Apple iPhone SE (2022) | Dr.fone</u></a></li>
<li><a href="https://some-guidance.techidaily.com/streamline-your-shots-a-windows-11-guide-for-2024/"><u>Streamline Your Shots  A Windows 11 Guide for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-apex-of-narrative-content-youtubes-finest-in-23-for-2024/"><u>The Apex of Narrative Content  YouTube’s Finest in '23 for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-ultimate-guide-to-top-tier-360-pro-cams-for-2024/"><u>The Ultimate Guide to Top-Tier 360 Pro Cams for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/top-5-sites-to-download-text-effects-for-2024/"><u>Top 5 Sites to Download Text Effects for 2024</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/troubleshooting-tips-for-correcting-ntdlldll-issues-across-different-windows-systems/"><u>Troubleshooting Tips for Correcting ntdll.dll Issues Across Different Windows Systems</u></a></li>
<li><a href="https://fake-location.techidaily.com/what-is-geo-blocking-and-how-to-bypass-it-on-vivo-v30-lite-5g-drfone-by-drfone-virtual-android/"><u>What is Geo-Blocking and How to Bypass it On Vivo V30 Lite 5G? | Dr.fone</u></a></li>
</ul></div>
