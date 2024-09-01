---
title: "Streamline File Management: Enable Auto-Delete Feature for Downloads on Mac Computers"
date: 2024-08-31T06:10:21.787Z
updated: 2024-09-01T06:10:21.787Z
tags:
  - desktop
categories:
  - tech
thumbnail: https://thmb.techidaily.com/a05ae5ee6982c15ff3eed9139528bca4d5df10563908a6200578c04353f69c36.jpg
---

## Streamline File Management: Enable Auto-Delete Feature for Downloads on Mac Computers

### Key Takeaways

* Use Automator to create a Folder Action that automatically deletes old files in your Downloads folder.
* Customize when your files are deleted based on their age, such as those more than a week or month old.
* The action runs automatically whenever you download new files. It keeps the Downloads folder free from clutter without you needing to do anything.

 If you download a lot of files on your Mac, you'll need to delete the ones you no longer need regularly to avoid congesting your Downloads folder. Doing this manually can be a tedious task. Thankfully, there's a way to automate it. Let's show you how.

##  How to Create a Folder Action in Automator to Delete Downloads Automatically

 Apple ships the Automator app with macOS on all its Macs. With Automator, you can [automate repetitive tasks on your Mac](https://win-dash.techidaily.com/amd-ryzen-5-2600-driver-download-fast-simple-steps/), so you don't have to perform them manually.

 Automator supports multiple types of tasks. However, what we need for this guide is the Folder Action automation, which triggers an action every time there's a change to a specified folder. In our case, the Folder Action will automatically delete from the Downloads folder all files and folders that are more than seven days old whenever new ones get added.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4737285&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/b2f83c409ce63012229fb9cd465bdcfe/products/copy_reporting_system.png" border="0">  KoolReport Pro  is an advanced solution for creating data reports and dashboards in PHP. Equipped with all  extended packages , KoolReport Pro is able to connect to various datasources, perform advanced data analysis, construct stunning charts and graphs and export your beautiful work to PDF, Excel, JPG or other formats. Plus, it includes powerful built-in reports such as pivot report and drill-down report which will save your time in building ones. 

 It will help you to write dynamic data reports easily, to construct intuitive dashboards or to build a whole business intelligence cockpit. 

  KoolReport Pro  package goes with Full Source Code, Royal Free, ONE (1) Year Priority Support, ONE (1) Year Free Upgrade and 30-Days Money Back Guarantee. 

  Developer License  allows  Single Developer  to create Unlimited Reports, deploy on Unlimited Servers and able deliver the work to Unlimited Clients. </a>
<!-- affiliate ads end -->
###  Set Up a Folder Action

 To create the Folder Action, start by launching the Automator app on your Mac. When it asks you to choose a document type, click on "Folder Action" and hit "Choose."

![Choosing document type in Automator app on a Mac.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/automatically-delete-downloads-on-a-mac-1.jpg) 

 Look for a dropdown box in the rightmost pane at the top of the screen. It'll appear next to the text "Folder Action receives files and folders added to." Click on it and select "Other." Then, select the "Downloads" folder in the Finder and hit "Choose."

![Choosing a folder to perform action on in Automator app.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/automatically-delete-downloads-on-a-mac-2.jpg) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3546200&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.binteko.com/sites/default/files/banner01_468x60a.gif" border="0"></a>
<!-- affiliate ads end -->
###  Find the Files to Delete

 There are two ways to find your files and folders in the Downloads folder. The first method uses the "Filter Finder Items" action, whereas the second takes advantage of the "Run Shell Script" action. We'll be using the latter, as the former doesn't work as expected and fails to return the right files and folders.

 Click the search box in the middle pane and look for "Run Shell Script." Drag this action to the right-hand pane to add it to the workflow.

![Adding the Run Shell Script action to the workflow in Automator.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/automatically-delete-downloads-on-a-mac-4.jpg) 

 On this action, click the dropdown button next to "Shell" and select the "/bin/bash" option.

![Setting the default shell to bash in Automator.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/automatically-delete-downloads-on-a-mac-5.jpg) 

<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072199/17885" target="_top" id="2072199"><img src="//a.impactradius-go.com/display-ad/17885-2072199" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072199/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 In the text box below that, enter the following command:

find "[path to Downloads directory]/Downloads" -ctime +7d -o -mtime +7d -iname '*.*'

 The command looks for files created ("-ctime") or modified ("-mtime") more than seven days ago ("+7d"). You can change it to whatever time frame you like. For example, changing the "-ctime" figure to "+30d" would only delete files downloaded more than a month ago.

 You also need to replace \[path to Downloads directory\] with the path to the Downloads folder on your Mac. To find the path, open Finder, right-click on "Downloads" in the left sidebar, and select "Get Info."

 On the Downloads Info window that opens, expand the "General" section by clicking the arrow button before it.

![Expanding the General tab to view the path of Downloads folder.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/automatically-delete-downloads-on-a-mac-10-1.jpg) 

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=39694080&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/nbr/fire/Screenshot_1red_gb.jpg" border="0">Nero Burning ROM:
The ultimate burning program for all your needs!</a>
<!-- affiliate ads end -->
 Right-click on the address next to "Where," and select "Copy as Pathname."

![Copying the path of Downloads folder on Mac.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/automatically-delete-downloads-on-a-mac-11.jpg) 

 Finally, paste it into the command in Automator. Remember to ensure that /Downloads is on the end of the path. Now, click the "Run" button in the Automator window to run the workflow.

![Running the Folder Action workflow to verify if the Run Shell Script action returns right files and folders.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/automatically-delete-downloads-on-a-mac-8.jpg) 

 If you did everything correctly, it'll return all the files and folders in the Downloads folder that meet your criteria. You can look at the results by clicking the "Results" tab on the Run Shell Script action.

![Run Shell Scription action results.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/automatically-delete-downloads-on-a-mac-7.jpg) 

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B300x600%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-300x600.gif" border="0"></a>
<!-- affiliate ads end -->
###  Auto-Delete the Files

 If you're happy that it's working, proceed to add the final action to the workflow. Search for "Move Finder Items to Trash" or "Move Finder Items to Bin" in the search box on the middle pane and drag it to the workflow area below the Run Shell Script action such that the two are linked.

 Finally, click on File > Save or press Command+S. Then, name the Folder Action and click "Save." macOS saves all your Automator Folder Actions under the "\~/Library/Workflows/Applications/Folder Actions/" path.

![Saving a Folder Action workflow in Automator.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/automatically-delete-downloads-on-a-mac-9.jpg) 

 Now, any time you add new files to your Downloads folder, the existing files that are more than a week old will be automatically moved to the trash.

<!-- affiliate ads begin -->
<a href="https://ancheer.sjv.io/c/5597632/1657301/17326" target="_top" id="1657301"><img src="//a.impactradius-go.com/display-ad/17326-1657301" border="0" alt="" width="1920" height="933"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657301/17326" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  Keep Your Trash Decluttered as Well

 As the above Folder Action workflow moves files and folders from your Mac's Downloads folder into the Trash, your Trash will likely end up with a lot of unused files and folders, and will still eat up your Mac's storage space. However, you can avoid this by automatically emptying your Trash every 30 days.

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
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-essential-resources-for-crafting-eye-catching-youtube-ends/"><u>[New] 2024 Approved  Essential Resources for Crafting Eye-Catching YouTube Ends</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/024-approved-the-ultimate-playlist-guide-for-youtube-enthusiasts-online-and-mobile/"><u>[New] 2024 Approved  The Ultimate Playlist Guide for YouTube Enthusiasts Online & Mobile</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/n-2024-eye-openers-yearly-infographics-on-yts-surprising-stats-17/"><u>[New] In 2024, Eye-Openers! Yearly Infographics on YT's Surprising Stats ('17)</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-ultimate-10-survival-arena-matches-for-2024/"><u>[Updated] Ultimate 10 Survival Arena Matches for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/windows-11-dvd-top10/"><u>「Windows 11 DVD コピーを簡単に!無料のベストツール集Top10掲載」</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-dvd-dvd5/"><u>2024 年の無料 DVD 書き込み、埋め込み、DVD制作ソフトウェアベスト5ランキングをご紹介</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-musicfm/"><u>2024年度 MusicFM更新対策：ダウンロード不可アップデートに追いつける！信頼性の低下した開発元から救出方法</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/3-ways-to-erase-apple-iphone-x-when-its-locked-within-seconds-drfone-by-drfone-ios/"><u>3 Ways to Erase Apple iPhone X When Its Locked Within Seconds | Dr.fone</u></a></li>
<li><a href="https://some-guidance.techidaily.com/alternatives-to-powerdvd-on-mac-best-free-and-paid-options/"><u>Alternatives to PowerDVD on Mac: Best Free and Paid Options</u></a></li>
<li><a href="https://extra-hints.techidaily.com/best-slow-motion-cameras-for-2024/"><u>Best Slow-Motion Cameras for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/building-tailored-apple-playlists-with-ease-for-ios-devices/"><u>Building Tailored Apple Playlists with Ease for iOS Devices</u></a></li>
<li><a href="https://some-guidance.techidaily.com/die-besten-lol-filmen-finden-herunterladen-oder-online-ansehen-unsere-empfehlungen/"><u>Die Besten LOL-Filmen Finden, Herunterladen Oder Online Ansehen - Unsere Empfehlungen</u></a></li>
<li><a href="https://some-guidance.techidaily.com/downloads-vs-streams-showdown-which-is-superior-for-watching-videos-online/"><u>Downloads Vs. Streams Showdown: Which Is Superior for Watching Videos Online?</u></a></li>
<li><a href="https://some-guidance.techidaily.com/1724766421493-dvd/"><u>DVD複写時に発生する容量超過問題解決法 - 成功体系公開</u></a></li>
<li><a href="https://some-guidance.techidaily.com/effortless-guide-creating-a-musical-photo-slideshow-for-youtube-success/"><u>Effortless Guide: Creating a Musical Photo Slideshow for YouTube Success</u></a></li>
<li><a href="https://some-guidance.techidaily.com/effortless-macx-dvd-ripper-convert-your-movies-seamlessly-from-dvds-to-apple-tv-format-on-mac/"><u>Effortless MacX DVD Ripper - Convert Your Movies Seamlessly From DVDs to Apple TV Format on Mac</u></a></li>
<li><a href="https://some-guidance.techidaily.com/expert-techniques-for-editing-images-in-macos-a-comprehensive-photos-tutorial/"><u>Expert Techniques for Editing Images in macOS: A Comprehensive Photos Tutorial</u></a></li>
<li><a href="https://some-guidance.techidaily.com/fixing-imovies-audio-video-desynchronization-problem-a-step-by-step-guide-including-visual-assistance/"><u>Fixing iMovie's Audio-Video Desynchronization Problem: A Step-by-Step Guide Including Visual Assistance</u></a></li>
<li><a href="https://some-guidance.techidaily.com/free-guide-streaming-4k-content-on-imac-and-macbook-your-ultimate-netflix-setup/"><u>Free Guide: Streaming 4K Content on iMac and MacBook - Your Ultimate Netflix Setup</u></a></li>
<li><a href="https://some-guidance.techidaily.com/giggle-away-with-babies-comedy-moments-from-youngsters-get-them-for-free/"><u>Giggle Away with Babies: Comedy Moments From Youngsters - Get Them for Free!</u></a></li>
<li><a href="https://some-guidance.techidaily.com/guide-easily-transfer-and-backup-your-ios-data-by-turning-your-iphone-into-a-storage-drive/"><u>Guide: Easily Transfer and Backup Your iOS Data by Turning Your iPhone Into a Storage Drive</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-nubia-red-magic-9-pro-without-the-home-button-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset Nubia Red Magic 9 Pro Without the Home Button | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-stop-my-spouse-from-spying-on-my-htc-u23-drfone-by-drfone-virtual-android/"><u>How to Stop My Spouse from Spying on My HTC U23 | Dr.fone</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/in-2024-dynamic-presentations-how-to-integrate-screens-into-online-spaces/"><u>In 2024, Dynamic Presentations  How to Integrate Screens Into Online Spaces</u></a></li>
<li><a href="https://some-guidance.techidaily.com/lossless-conversion-tactics-transforming-hd-m2ts-files-into-high-quality-mkv-format/"><u>Lossless Conversion Tactics: Transforming HD M2TS Files Into High-Quality MKV Format</u></a></li>
<li><a href="https://some-guidance.techidaily.com/mac-dvd-duplication-guide-achieving-perfect-bit-by-bit-replicas/"><u>Mac DVD Duplication Guide: Achieving Perfect Bit-by-Bit Replicas</u></a></li>
<li><a href="https://some-guidance.techidaily.com/macx-dvd-ripper-pro-ultimate-key-unlock-full-features-at-no-cost/"><u>MacX DVD Ripper Pro Ultimate Key : Unlock Full Features at No Cost</u></a></li>
<li><a href="https://some-guidance.techidaily.com/macx-hd-master-converter-tool-for-windows-10-seamless-mkvavchdmp4-transformation-upload-ready-videos-for-all-devices/"><u>MacX HD Master Converter Tool for Windows 10 - Seamless MKV/AVCHD/MP4 Transformation, Upload-Ready Videos for All Devices!</u></a></li>
<li><a href="https://some-guidance.techidaily.com/macx-ultimate-video-transcoder-activation-codes-and-serial-keys-2022/"><u>MacX Ultimate Video Transcoder: Activation Codes and Serial Keys 2022</u></a></li>
<li><a href="https://some-guidance.techidaily.com/macxdvds-festive-bonanza-score-20k-free-copies-of-the-pro-version-of-macx-dvd-ripper-this-thanksgiving-holiday-season/"><u>MacXDVD's Festive Bonanza: Score 20K Free Copies of the Pro Version of MacX DVD Ripper This Thanksgiving Holiday Season!</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/quick-fame-quest-mastering-content-video-and-likes-for-2024/"><u>Quick Fame Quest - Mastering Content, Video, and Likes for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/quick-guide-bulk-deleting-images-on-your-iphone-8-plus-or-x-top-five-methods/"><u>Quick Guide: Bulk Deleting Images on Your iPhone 8, Plus or X – Top Five Methods</u></a></li>
<li><a href="https://some-guidance.techidaily.com/revolutionize-your-media-conversions-with-macx-video-converter-pro-v59-the-ultimate-in-high-speed-efficiency-through-innovative-hardware-acceleration/"><u>Revolutionize Your Media Conversions with MacX Video Converter Pro v5.9 - The Ultimate in High-Speed Efficiency Through Innovative Hardware Acceleration!</u></a></li>
<li><a href="https://some-guidance.techidaily.com/seamlessly-stream-or-play-dvds-on-apples-latest-tablets-mini-pro-and-air-tips/"><u>Seamlessly Stream or Play DVDs on Apple's Latest Tablets: Mini, Pro & Air Tips</u></a></li>
<li><a href="https://some-guidance.techidaily.com/secure-your-macx-dvd-ripper-pro-at-a-bargain-shop-now-with-special-offers/"><u>Secure Your MacX DVD Ripper Pro at a Bargain - Shop Now With Special Offers!</u></a></li>
<li><a href="https://some-guidance.techidaily.com/solving-handbrake-woes-ensuring-full-movie-transfers-successfully/"><u>Solving HandBrake Woes: Ensuring Full Movie Transfers Successfully</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/stand-out-design-and-customize-professional-logos-via-free-templates-for-2024/"><u>Stand Out  Design and Customize Professional Logos via Free Templates for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/step-by-step-tutorial-on-ripping-and-transforming-pal-dvds-into-mp4-files-for-ntsc-playback/"><u>Step-by-Step Tutorial on Ripping and Transforming PAL DVDs Into MP4 Files for NTSC Playback</u></a></li>
<li><a href="https://some-guidance.techidaily.com/supercharged-macx-mediatrans-lightning-fast-iphone-photography-backup/"><u>Supercharged MacX MediaTrans: Lightning-Fast iPhone Photography Backup</u></a></li>
<li><a href="https://some-guidance.techidaily.com/tiktokiphoneandroid/"><u>TikTok動画を安全に保管・ダウンロードする方法｜iPhone/Androidユーザー向けガイド</u></a></li>
<li><a href="https://some-guidance.techidaily.com/top-10-methods-for-seamlessly-moving-images-from-your-iphone-onto-a-mac/"><u>Top 10 Methods for Seamlessly Moving Images From Your iPhone Onto a Mac</u></a></li>
<li><a href="https://some-guidance.techidaily.com/top-rated-family-christmas-films-a-timeless-selection-for-children/"><u>Top-Rated Family Christmas Films: A Timeless Selection for Children</u></a></li>
<li><a href="https://some-guidance.techidaily.com/transfer-your-memories-top-10-methods-for-shifting-pictures-from-iphone-to-mac/"><u>Transfer Your Memories: Top 10 Methods for Shifting Pictures From iPhone to Mac</u></a></li>
<li><a href="https://sound-issues.techidaily.com/troubleshooting-steps-to-fix-audio-issues-on-hp-devices-running-windows-11/"><u>Troubleshooting Steps to Fix Audio Issues on HP Devices Running Windows 11</u></a></li>
<li><a href="https://some-guidance.techidaily.com/understanding-mac-os-x-comprehensive-definition-and-key-attributes/"><u>Understanding Mac OS X: Comprehensive Definition & Key Attributes</u></a></li>
<li><a href="https://some-guidance.techidaily.com/unlocking-your-device-a-comprehensive-guide-to-ios-17-jailbreaking/"><u>Unlocking Your Device: A Comprehensive Guide to iOS 17 Jailbreaking</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/wireless-joy-configuring-your-ps4-controller/"><u>Wireless Joy: Configuring Your PS4 Controller</u></a></li>
</ul></div>
