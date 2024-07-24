---
title: "[New] Unlocking Visual Storytelling with AR & LUTs"
date: 2024-07-23T09:04:27.477Z
updated: 2024-07-24T09:04:27.477Z
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
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-efficient-keyword-utilization-discover-the-best-7-online-video-tag-extractors-reviewed/"><u>[New] 2024 Approved  Efficient Keyword Utilization  Discover the Best 7 Online Video Tag Extractors Reviewed</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/new-in-2024-eliminating-fisheye-lens-distortions-with-gopro/"><u>[New] In 2024, Eliminating Fisheye Lens Distortions with GoPro</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-mastering-windows-10-essential-knowledge/"><u>[New] Mastering Windows 10  Essential Knowledge</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-precision-and-efficiency-incorporating-luts-in-after-effects/"><u>[New] Precision and Efficiency  Incorporating LUTs in After Effects</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-streamline-a-barrage-of-tiktok-drafts-with-editing-skills/"><u>[New] Streamline a Barrage of TikTok Drafts with Editing Skills</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-superior-websites-promoting-youtube-media/"><u>[New] Superior Websites Promoting YouTube Media</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-swift-solution-for-clownfish-vocal-alteration-on-pc-systems/"><u>[New] Swift Solution for Clownfish Vocal Alteration on PC Systems</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-the-secret-to-unbroken-snaps-keeping-streak-alive/"><u>[New] The Secret to Unbroken Snaps  Keeping Streak Alive</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-top-10-live-streamers-an-analytical-comparison-review/"><u>[New] Top 10 Live Streamers  An Analytical Comparison Review</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-top-10-vr-apps-for-iphoneandroid/"><u>[New] Top 10 VR Apps for iPhone/Android</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-top-picks-for-personalizing-mbp-screens-with-skins/"><u>[New] Top Picks for Personalizing MBP Screens with Skins</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-unleash-your-videos-potential-with-dynamic-titles/"><u>[New] Unleash Your Video's Potential with Dynamic Titles</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-from-concept-to-completion-building-effective-facebook-covers/"><u>[Updated] From Concept to Completion  Building Effective Facebook Covers</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/updated-laying-down-an-elegant-tiktok-credits-panel-for-2024/"><u>[Updated] Laying Down an Elegant TikTok Credits Panel for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-step-by-step-on-streaming-google-meet-directly-to-youtube-channel/"><u>[Updated] Step by Step on Streaming Google Meet Directly to YouTube Channel</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-syncing-your-favorite-tunes-moving-playlists-across-platforms/"><u>[Updated] Syncing Your Favorite Tunes  Moving Playlists Across Platforms</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-testing-titans-in-depth-comparison-of-gopros-hero5b-and-session/"><u>[Updated] Testing Titans  In-Depth Comparison of GoPro's Hero5B & Session</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-art-of-professional-gopro-filming/"><u>[Updated] The Art of Professional GoPro Filming</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-essence-of-polarr-revolutionizing-digital-photography/"><u>[Updated] The Essence of Polarr  Revolutionizing Digital Photography</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-future-shaped-by-quantum-hdr-tech/"><u>[Updated] The Future Shaped by Quantum HDR Tech</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-importance-of-non-primary-footage-in-editing/"><u>[Updated] The Importance of Non-Primary Footage in Editing</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-perfect-path-from-instagram-to-tiktok/"><u>[Updated] The Perfect Path  From Instagram to TikTok</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-unlock-your-potential-for-green-screen-excellence-in-kinemaster/"><u>[Updated] Unlock Your Potential for Green Screen Excellence in Kinemaster</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-unveiling-lightroom-for-android-a-complete-guide/"><u>[Updated] Unveiling Lightroom for Android  A Complete Guide</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-streaming-made-easier-learning-to-use-netflixs-dual-screen-feature/"><u>2024 Approved  Streaming Made Easier  Learning to Use Netflix's Dual-Screen Feature</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-the-ultimate-tv-show-prep-which-software-winsvirusmix-or-wirecast/"><u>2024 Approved  The Ultimate TV Show Prep  Which Software Wins—VirusMix or WireCast?</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-transform-your-mac-with-the-latest-macos-11-big-sur-overview/"><u>2024 Approved  Transform Your Mac with the Latest  MacOS 11 Big Sur Overview</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-unlock-15-simple-vlog-inspirations-today/"><u>2024 Approved  Unlock 15 Simple Vlog Inspirations Today</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-unlock-chromes-full-potential-with-pip-across-devices/"><u>2024 Approved  Unlock Chrome's Full Potential with PIP Across Devices</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-unveiling-vr-the-creation-gap/"><u>2024 Approved  Unveiling VR  The Creation Gap</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/4-manieres-francaises-de-celebrer-laccueil/"><u>4 Manières Françaises De Célébrer L'Accueil</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/from-sound-to-words-a-free-guide-to-youtube-transcribing-mastery-for-2024/"><u>From Sound to Words  A FREE Guide to YouTube Transcribing Mastery for 2024</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-watch-hulu-outside-us-on-apple-iphone-6-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Watch Hulu Outside US On Apple iPhone 6 | Dr.fone</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-the-art-of-using-kinemaster-techniques-and-top-online-video-editors/"><u>In 2024, The Art of Using KineMaster  Techniques and Top Online Video Editors</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-the-scope-of-panoramic-filmmaking-explained/"><u>In 2024, The Scope of Panoramic Filmmaking Explained</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-the-ultimate-guide-to-video-cuts-windows-edition-made-simple/"><u>In 2024, The Ultimate Guide to Video Cuts  Windows Edition, Made Simple</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-tips-and-tricks-for-setting-up-your-samsung-galaxy-a23-5g-phone-pattern-lock-by-drfone-android/"><u>In 2024, Tips and Tricks for Setting Up your Samsung Galaxy A23 5G Phone Pattern Lock</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-top-techniques-in-testimonial-production-an-experts-insight/"><u>In 2024, Top Techniques in Testimonial Production  An Expert's Insight</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-top-youtube-spots-for-video-marketing-success/"><u>In 2024, Top YouTube Spots for Video Marketing Success</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-unmatched-4k-hdtvs-for-intense-gaming/"><u>In 2024, Unmatched 4K HDTVs for Intense Gaming</u></a></li>
<li><a href="https://some-guidance.techidaily.com/narrative-noble-order-honors-hexagon-for-2024/"><u>Narrative Noble Order - Honor's Hexagon for 2024</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-make-your-videos-accessible-10-free-subtitle-makers-online/"><u>New Make Your Videos Accessible 10 Free Subtitle Makers Online</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-maximizing-visibility-how-to-create-custom-linkedin-video-thumbnails/"><u>New Maximizing Visibility How to Create Custom LinkedIn Video Thumbnails</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-beginners-guide-to-canon-time-lapse-shooting-for-2024/"><u>The Beginner's Guide to Canon Time-Lapse Shooting for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/this-years-narrative-pioneers-youtubes-top-20-channels-for-2024/"><u>This Year’s Narrative Pioneers  YouTube's Top 20 Channels for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/unlocking-the-realm-of-free-photo-frame-video-downloads-for-2024/"><u>Unlocking the Realm of Free Photo Frame Video Downloads for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/unrivaled-narratives-crafted-in-eight-film-fields-for-2024/"><u>Unrivaled Narratives Crafted in Eight Film Fields for 2024</u></a></li>
</ul></div>
