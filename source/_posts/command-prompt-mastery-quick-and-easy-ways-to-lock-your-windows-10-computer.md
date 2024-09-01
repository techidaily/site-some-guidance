---
title: "Command Prompt Mastery: Quick and Easy Ways to Lock Your Windows 10 Computer"
date: 2024-08-31T06:13:18.334Z
updated: 2024-09-01T06:13:18.334Z
tags:
  - deals
categories:
  - tech
thumbnail: https://thmb.techidaily.com/0b08703f0711aa278d64397e12272d17e9628dac2d52aa808134158c2c218743.jpg
---

## Command Prompt Mastery: Quick and Easy Ways to Lock Your Windows 10 Computer

### Quick Links

* [Lock Your Windows 10 PC Using Command Prompt](https://vp-tips.techidaily.com/new-audiovisual-adaptability-in-free-fire-for-2024/)
* [Set the Lock Screen Timeout Setting Using Command Prompt](https://eaxpv-info.techidaily.com/new-finding-a-different-way-to-naming-your-channel-with-filmora-for-2024/)

### Key Takeaways

* To lock your Windows PC using Command Prompt, run "**Rundll32.exe user32.dll,LockWorkStation"** in the Command Prompt
* To set the lock screen timeout, run "**powercfg.exe /SETACVALUEINDEX SCHEME\_CURRENT SUB\_VIDEO VIDEOCONLOCK <time>"** in Command Prompt as Admin
* Activate the lock screen timeout setting by running "**powercfg.exe /SETACTIVE SCHEME\_CURRENT"** after you set the timeout.

 One of the first rules of cyber security is to always lock your PC before stepping away. While it may not be the quickest way to lock your Windows 10 PC, you can do it using the Command Prompt.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296685&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2022/video-pp/ScreenshotSlider/Nero-Video-Advanced-editing.JPG" border="0">Simple and intuitive video editing
🎬 Nero Video:
The powerful video editing program for your Windows PC</a>
<!-- affiliate ads end -->
##  Lock Your Windows 10 PC Using Command Prompt

 First, [open the Command Prompt](https://android-frp.techidaily.com/in-2024-step-by-step-tutorial-how-to-bypass-oppo-a78-frp-by-drfone-android/) on your PC by opening the Start menu, typing “cmd” in the Windows Search bar, and then selecting “Command Prompt” from the search results.

![Click the Start button, search for 'cmd,' then open 'Command Prompt.'](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/1-launch-cmd.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726960&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/forexrobotronbox.gif" border="0">Forex Robotron Basic Package</a>
<!-- affiliate ads end -->
 Command Prompt will now open. Here, run this command to lock your Windows 10 PC.

Rundll32.exe user32.dll,LockWorkStation

![Locking your PC with Command Prompt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/2-lock-pc-command-prompt.png) 

 Once executed, your PC will be locked. You'll have to sign back in with your PIN, password, or whatever sign-in method you usually use.

<!-- affiliate ads begin -->
<a href="https://bluetties.sjv.io/c/5597632/2039292/17094" target="_top" id="2039292"><img src="//a.impactradius-go.com/display-ad/17094-2039292" border="0" alt="BLUETTI NEW LAUNCH AC240" width="954" height="1020"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2039292/17094" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  Set the Lock Screen Timeout Setting Using Command Prompt

 Once you’ve locked your PC, the lock screen will generally be displayed for a certain amount of time before it time outs. You can set the amount of time that needs to pass before timing out using the Command Prompt.

 To do this, you’ll need to [open Command Prompt as an admin](https://screen-mirror.techidaily.com/how-to-screen-mirroring-xiaomi-14-ultra-drfone-by-drfone-android/). Do so by typing “cmd” in the Windows Search bar and then right-clicking “Command Prompt” from the results. Next, select “Run As Administrator” from the menu that appears.

![Launching Command Prompt as admin.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/3-launch-cmd.png) 

<!-- affiliate ads begin -->
<a href="https://parisrhonecom.sjv.io/c/5597632/1896607/21553" target="_top" id="1896607"><img src="//a.impactradius-go.com/display-ad/21553-1896607" border="0" alt="" width="750" height="422"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1896607/21553" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 With Command Prompt open, run this command.

powercfg.exe /SETACVALUEINDEX SCHEME_CURRENT SUB_VIDEO VIDEOCONLOCK <time>

 Replace `<time>` with your desired amount of time in seconds. That means if you want to time out the lock screen after two minutes, you’d enter this command:

powercfg.exe /SETACVALUEINDEX SCHEME_CURRENT SUB_VIDEO VIDEOCONLOCK 120

![Change the timeout to 120.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/4-changing-timeout-to-120.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901369&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix 4K - Software based live production. vMix 4K includes everything in vMix HD plus 4K support, PTZ control, External/Fullscreen output, 4 Virtual Outputs, 1 Replay, 4 vMix Call, and 2 Recorders. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
 This command sets the lock screen timeout setting for your PC if it’s plugged in to a power source. To set the lock screen timeout setting for your PC if it’s running on battery, change`/SETACVALUEINDEX` to`/SETDCVALUEINDEX` and run the command as normal.

 Next, run this command:

powercfg.exe /SETACTIVE SCHEME_CURRENT

![Apply the setting to the currently active scheme.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/5-set-active.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-spreadsheet-free-excel-editor-online-offline-1x.93e269d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
 Now your [lock screen](https://driver-download.techidaily.com/1722977751917-synaptics-drivers-download-and-update-for-windows-easily/) will timeout after the set amount of time. Give it a try!

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
<li><a href="https://fox-links.techidaily.com/new-2024-approved-mastering-aquatic-cinematography-with-these-7-essential-strategies/"><u>[New] 2024 Approved  Mastering Aquatic Cinematography with These 7 Essential Strategies</u></a></li>
<li><a href="https://youtube-data.techidaily.com/024-approved-the-premier-selector-master-your-video-grabs/"><u>[New] 2024 Approved  The Premier Selector  Master Your Video Grabs</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/new-asus-proart-pa-329q-the-pinnacle-in-high-definition-viewing/"><u>[New] Asus ProArt PA 329Q  The Pinnacle in High-Definition Viewing</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-chuckle-chest-selecting-15-hilarious-video-treasures-for-your-viewing-pleasure-for-2024/"><u>[New] Chuckle Chest  Selecting 15 Hilarious Video Treasures for Your Viewing Pleasure for 2024</u></a></li>
<li><a href="https://article-files.techidaily.com/new-comic-crafting-on-apple-devices-for-2024/"><u>[New] Comic Crafting on Apple Devices for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-effective-strategies-to-capture-and-save-google-voice-dialogues/"><u>[Updated] 2024 Approved  Effective Strategies to Capture and Save Google Voice Dialogues</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-synchronized-device-tutorial-for-efficient-movie-logging/"><u>2024 Approved  Synchronized Device Tutorial for Efficient Movie Logging</u></a></li>
<li><a href="https://some-guidance.techidaily.com/macdvdmp4/"><u>如何在Mac电脑上无成本地将DVD改编为MP4格式 - 全程解答</u></a></li>
<li><a href="https://some-guidance.techidaily.com/1724765879269-dvd/"><u>無料対策説明：パソコンレスでコピープロテクト付きDVDをスマートフォンに取り込む方法</u></a></li>
<li><a href="https://some-guidance.techidaily.com/a-compatible-graphics-card-with-opengl-support/"><u>A Compatible Graphics Card with OpenGL Support</u></a></li>
<li><a href="https://some-guidance.techidaily.com/best-free-h264-to-mp4-converter-software-for-mac-and-windows-10-quick-and-easy-guide/"><u>Best FREE H.264 To MP4 Converter Software for MAC & Windows 10 – Quick and Easy Guide!</u></a></li>
<li><a href="https://some-guidance.techidaily.com/best-of-low-budget-cinema-free-downloads-of-iconic-b-films-ranked-1-to-100/"><u>Best of Low-Budget Cinema: Free Downloads of Iconic 'B' Films Ranked #1 to #100</u></a></li>
<li><a href="https://buynow-help.techidaily.com/best-processor-driven-tablets-in-depth-evaluation-and-comparison/"><u>Best Processor-Driven Tablets: In-Depth Evaluation and Comparison</u></a></li>
<li><a href="https://games-able.techidaily.com/breakdown-fixing-faulty-xbox-series-xs/"><u>Breakdown: Fixing Faulty Xbox Series X|S</u></a></li>
<li><a href="https://some-guidance.techidaily.com/conversione-facile-e-veloce-da-mxf-a-formati-video-piu-diffusi-mp4-mov-avi-per-utenti-mac/"><u>Conversione Facile E Veloce Da MXF a Formati Video Più Diffusi: MP4, MOV, AVI per Utenti Mac</u></a></li>
<li><a href="https://some-guidance.techidaily.com/conversione-gratuita-dei-file-vob-in-mp4-per-mac-un-tutorial-facile-da-seguire/"><u>Conversione Gratuita Dei File VOB in MP4 per Mac: Un Tutorial Facile Da Seguire</u></a></li>
<li><a href="https://some-guidance.techidaily.com/die-top-6-beliebtesten-dvd-extraktionswerkzeuge-fur-eine-optimale-nutzung/"><u>Die Top 6 Beliebtesten DVD-Extraktionswerkzeuge Für Eine Optimale Nutzung</u></a></li>
<li><a href="https://some-guidance.techidaily.com/1724766589072-digiarty-18/"><u>Digiarty 祝開業18週年スペシャルコレクション</u></a></li>
<li><a href="https://some-guidance.techidaily.com/download-free-hd-dvd-ripper-play-your-favorite-films-worry-free-on-ios-devices/"><u>Download Free HD DVD Ripper: Play Your Favorite Films Worry-Free on iOS Devices</u></a></li>
<li><a href="https://some-guidance.techidaily.com/download-macx-pro-the-ultimate-free-mac-based-tool-to-effortlessly-convert-and-edit-your-mkv-videos/"><u>Download MacX Pro: The Ultimate Free Mac-Based Tool to Effortlessly Convert and Edit Your MKV Videos</u></a></li>
<li><a href="https://some-guidance.techidaily.com/download-superior-quality-mp3s-from-youtube-a-guide-to-finding-and-using-the-premier-video-to-audio-tool/"><u>Download Superior Quality MP3s From YouTube - A Guide to Finding and Using the Premier Video to Audio Tool</u></a></li>
<li><a href="https://some-guidance.techidaily.com/dvd/"><u>DVDへ完全移行!最高効果で動画録画を保存する究極手段</u></a></li>
<li><a href="https://some-guidance.techidaily.com/effective-techniques-for-downsizing-big-videos-into-dvd-ready-sizes/"><u>Effective Techniques for Downsizing Big Videos Into DVD-Ready Sizes</u></a></li>
<li><a href="https://some-guidance.techidaily.com/efficient-methods-for-quickly-moving-4k-footage-from-your-iphone-onto-a-mac-computer/"><u>Efficient Methods for Quickly Moving 4K Footage From Your iPhone Onto a Mac Computer</u></a></li>
<li><a href="https://some-guidance.techidaily.com/facile-conversion-du-fichier-mkv-au-format-mp4-sur-macos-transformation-rapide-sans-compromettre-la-qualite/"><u>Facile Conversion Du Fichier MKV Au Format MP4 Sur macOS - Transformation Rapide Sans Compromettre La Qualité</u></a></li>
<li><a href="https://win-amazing.techidaily.com/get-your-logitech-hd-c270-camera-up-and-running-on-windows-11-with-updated-drivers/"><u>Get Your Logitech HD C270 Camera Up and Running on Windows 11 with Updated Drivers</u></a></li>
<li><a href="https://some-guidance.techidaily.com/gultiger-macx-video-konvertierungsprogramm-schlussel-fur-die-pro-version-downloaden-und-aktivieren-im-jahr-2023/"><u>Gültiger MacX Video Konvertierungsprogramm-Schlüssel Für Die Pro Version – Downloaden Und Aktivieren Im Jahr 2023</u></a></li>
<li><a href="https://some-guidance.techidaily.com/handbrake-compatibility-with-m1-apple-silicon-solutions-and-troubleshooting/"><u>Handbrake Compatibility with M1 Apple Silicon: Solutions & Troubleshooting</u></a></li>
<li><a href="https://some-guidance.techidaily.com/high-quality-film-transfer-convert-your-dvd-isos-and-burn-them-onto-an-external-usb-drive-for-enhanced-playback-on-ios-devices/"><u>High-Quality Film Transfer - Convert Your DVD ISOs and Burn Them Onto an External USB Drive for Enhanced Playback on iOS Devices</u></a></li>
<li><a href="https://some-guidance.techidaily.com/how-to-seamlessly-transform-mp3-videos-into-ipad-ready-formats-the-best-methods/"><u>How to Seamlessly Transform MP3 Videos Into iPad-Ready Formats - The Best Methods</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-harmonizing-your-device-importing-to-inshot-app/"><u>In 2024, Harmonizing Your Device  Importing to InShot App</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-sony-a6400-video-failure-what-to-do-next/"><u>In 2024, Sony A6400 Video Failure  What To Do Next?</u></a></li>
<li><a href="https://some-guidance.techidaily.com/key-challenges-and-concerns-facing-the-new-iphone-xs-insider-information-for-consumers/"><u>Key Challenges and Concerns Facing the New iPhone XS – Insider Information for Consumers</u></a></li>
<li><a href="https://some-guidance.techidaily.com/1724765539671-macx-dvd-ripper-pro/"><u>MacX DVD Ripper Pro正規版割引キー入手ガイド</u></a></li>
<li><a href="https://some-guidance.techidaily.com/mastering-itunes-the-ideal-video-file-type-for-seamless-playback-on-apples-platform/"><u>Mastering iTunes: The Ideal Video File Type for Seamless Playback on Apple's Platform</u></a></li>
<li><a href="https://some-guidance.techidaily.com/problem-application-crashes-upon-launch-or-during-operation-n-indicates-a-new-line-for-readability/"><u>Problem: Application Crashes upon Launch or During Operation (\\N Indicates a New Line for Readability)</u></a></li>
<li><a href="https://some-guidance.techidaily.com/solving-the-youtube-4k-playback-issue-in-safari-a-comprehensive-guide/"><u>Solving the YouTube 4K Playback Issue in Safari: A Comprehensive Guide</u></a></li>
<li><a href="https://some-guidance.techidaily.com/struggling-with-secure-and-latest-dvd-ripping-issues-discover-our-fixes-now/"><u>Struggling with Secure & Latest DVD Ripping Issues? Discover Our Fixes Now!</u></a></li>
<li><a href="https://some-guidance.techidaily.com/superior-data-handling-with-reimagined-macx-mediatrans-a-top-alternative-to-itunes-transfer-tools/"><u>Superior Data Handling with Reimagined MacX MediaTrans: A Top Alternative to iTunes Transfer Tools</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-complete-iphone-handbook-expert-strategies-for-seamless-data-movement-and-error-solutions/"><u>The Complete iPhone Handbook: Expert Strategies for Seamless Data Movement & Error Solutions</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/the-ultimate-guide-to-selecting-powerful-chipsets/"><u>The Ultimate Guide to Selecting Powerful Chipsets</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/top-11-free-apps-to-check-imei-on-itel-a70-phones-by-drfone-android/"><u>Top 11 Free Apps to Check IMEI on Itel A70 Phones</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/top-7-best-free-music-streaming-applications-for-apple-devices-and-smartphones/"><u>Top 7 Best Free Music Streaming Applications for Apple Devices & Smartphones</u></a></li>
<li><a href="https://some-guidance.techidaily.com/top-free-mac-software-convert-avi-files-to-3gp-format-at-no-cost/"><u>Top Free Mac Software: Convert AVI Files to 3GP Format at No Cost</u></a></li>
<li><a href="https://some-guidance.techidaily.com/top-rated-dvd-regions-unlocker-apps-bypass-and-remove-dvd-restrictions-on-pcmac/"><u>Top Rated DVD Regions Unlocker Apps - Bypass and Remove DVD Restrictions on PC/Mac</u></a></li>
<li><a href="https://some-guidance.techidaily.com/troubleshooting-instagram-video-glitches-proven-techniques-and-advice/"><u>Troubleshooting Instagram Video Glitches: Proven Techniques and Advice</u></a></li>
<li><a href="https://some-guidance.techidaily.com/troubleshooting-steps-when-itunes-doesnt-recognize-your-iphone-device/"><u>Troubleshooting Steps when iTunes Doesn't Recognize Your iPhone Device</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/what-is-the-best-pokemon-for-pokemon-pvp-ranking-on-honor-x9b-drfone-by-drfone-virtual-android/"><u>What is the best Pokemon for pokemon pvp ranking On Honor X9b? | Dr.fone</u></a></li>
<li><a href="https://some-guidance.techidaily.com/dmm/"><u>コツを学べ！DMMで購入したりダウンロードした動画の最善再生＆録画技術</u></a></li>
</ul></div>
