---
title: "Guide: Redirecting PowerShell Command Results Into Files"
date: 2024-08-31T06:13:19.630Z
updated: 2024-09-01T06:13:19.630Z
tags:
  - deals
categories:
  - tech
thumbnail: https://thmb.techidaily.com/cf44629f086fd2b8084bdc12a848844a50c0357a13a529d9a3d917fda81ba43e.jpg
---

## Guide: Redirecting PowerShell Command Results Into Files

### Quick Links

* [Send a PowerShell Command's Output to a Text File](https://eaxpv-info.techidaily.com/new-free-mobile-downloader-the-ultimate-apps-for-video-buffs-for-2024/)
* [Send a PowerShell Command's Output to a CSV File](https://facebook-record-videos.techidaily.com/updated-2024-approved-effortless-rearrangement-of-your-personalized-lists/)
* [View Your Text or CSV File’s Contents in PowerShell](https://some-guidance.techidaily.com/in-2024-the-ultimate-playbook-iphone-downloading-for-podcast-enthusiasts/)

### Key Takeaways

* To save a PowerShell command's output to a TXT file, type the command, press Spacebar, type the > (greater than) symbol, press Spacebar, and type the full path to the TXT file.
* To generate a CSV file from a PowerShell command, type your command, press Spacebar, type the | (pipe) sign, press Spacebar, type "Export-CSV", press Spacebar, enter the full path to the CSV file, press Spacebar, type "-NoTypeInformation", and press Enter.

 Do you want to save your PowerShell command’s result in a TXT (text) or CSV (comma-separated values) file on your computer? If so, it's easy to do, and we'll show you how on your Windows 11 or Windows 10 PC.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/300__250banner.jpg" border="0"></a>
<!-- affiliate ads end -->
##  Send a PowerShell Command's Output to a Text File

 To write your PowerShell command’s output to a text (TXT) file, first [launch a PowerShell window](https://techtrends.techidaily.com/what-are-the-stages-in-a-game-of-royal-match/). Here, type whatever command you need, the output of which you want in a text file. After you’ve typed the command, press Spacebar, type the > (greater than) symbol, press Spacebar, enter the full path to the text file where you want to save the output, and press Enter.

 For example, if you want to save the “[systeminfo](https://tech-haven.techidaily.com/has-chatgpt-simplified-or-compromised-academic-writings/)” command’s output to a file named "SystemInfo.txt" on your desktop, your command will look something like the following:

systeminfo > C:\Users\mahes\Desktop\SystemInfo.txt

!['systeminfo' command highlighted on a PowerShell window.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/10/1-systeminfo-command-output-txt-file.jpg) 

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698827&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/dex3REpage-newmainscreenshot.png" border="0">DEX 3 RE is Easy-To-Use DJ Mixing Software for MAC and Windows Designed for Today's Versatile DJ. 

 Mix from your own library of music, iTunes or use the Pulselocker subsciprtion service for in-app access to over 44 million songs. Use with over 85 supported DJ controllers or mix with a keyboard and mouse.  

 DEX 3 RE is everything you need without the clutter - the perfect 2-deck mixing software solution for mobile DJs or hard-core hobbiests.  
 PCDJ DEX 3 RE (DJ Software for Win & MAC - Product Activation For 3 Machines)</a>
<!-- affiliate ads end -->
 As soon as you press Enter, PowerShell creates your specified file and adds your command’s result to it. When that’s done, access your specified path, and you’ll find your newly created file there.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097467/26400?prodsku=B700" target="_top" id="2097467"><img src="//a.impactradius-go.com/display-ad/26400-2097467" border="0" alt="" width="640" height="640"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097467/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  Send a PowerShell Command's Output to a CSV File

 If you want to create a CSV file containing the output of your specified PowerShell command, use the tool’s "Export-CSV" [cmdlet](https://extra-guidance.techidaily.com/new-prophotomaster-the-ai-enhanced-editing-edge/).

 To do that, launch PowerShell. Here, enter your command (the results of which you want in a CSV file). Then, press Spacebar, enter the | (pipe) sign, press Spacebar, enter "Export-CSV", press Spacebar, enter the full path to the CSV file you want to create, press Spacebar, type "-NoTypeInformation", and press Enter.

 For example, if you want to save the current directory’s item list in a file called "List.csv" on your desktop, you’d use a command that looks like the following. Note that the "NoTypeInformation" parameter here tells the command not to include the #TYPE information header in your CSV file.

Get-ChildItem | Export-CSV C:\Users\mahes\Desktop\List.csv -NoTypeInformation

!['Get-ChildItem' cmdlet highlighted in PowerShell.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/10/2-directory-item-csv-file.jpg) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=11224199&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/copy_boxshot_lyricvideo.png" border="0">Lyric Video Creator Professional Version</a>
<!-- affiliate ads end -->
 When you’ve finished running the command, you’ll have a file called "List.csv" on your desktop containing the list of the items in your current directory.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=39694080&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/nbr/fire/Screenshot_1red_gb.jpg" border="0">Nero Burning ROM:
The ultimate burning program for all your needs!</a>
<!-- affiliate ads end -->
##  View Your Text or CSV File’s Contents in PowerShell

 You can view your newly created text or CSV file’s contents right inside PowerShell. You don’t have to leave the tool and use another app to open your files.

 To do that, open a PowerShell window, type the following command, replacing "PATH" with the full path to your text or CSV file, and press Enter.

Type PATH

 For example, if you want to [read the contents of a file](https://tiktok-video-files.techidaily.com/updated-key-points-to-consider-when-navigating-tiktok-web-on-macos-for-2024/) named "SystemInfo.txt" placed on your desktop, you’d use the following command:

Type C:\Users\mahes\Desktop\SystemInfo.txt

![A TXT file's contents displayed in PowerShell using the 'Type' command.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/10/3-read-file-powershell.jpg) 

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BOutlook%2BRecovery"><img src="https://www.systoolsgroup.com/box/outlook-recovery.png" border="0"></a>
<!-- affiliate ads end -->
 Instantly, PowerShell will load your file’s contents in your open window, allowing you to read the file content.

---

 And that’s all there is to know about saving your PowerShell command results in text or CSV files. Enjoy!

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
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-diy-photography-support-systems/"><u>[New] 2024 Approved  DIY Photography Support Systems</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-expert-guide-to-photo-transformation-tools/"><u>[New] Expert Guide to Photo Transformation Tools</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-action-cameras-face-off-gopro-hero-4-vs-ghost-s-drifting/"><u>[Updated] Action Cameras Face Off  GoPro Hero 4 Vs. Ghost-S Drifting</u></a></li>
<li><a href="https://some-guidance.techidaily.com/maccprm/"><u>「Mac用無料Cprm解除ツールを勧めます - スムーズな再生フリー化プロセス」</u></a></li>
<li><a href="https://some-guidance.techidaily.com/1-expert-guide-capturing-hd-videos-using-your-macbook-or-imac-webcam/"><u>1. Expert Guide: Capturing HD Videos Using Your MacBook or iMac Webcam</u></a></li>
<li><a href="https://some-guidance.techidaily.com/1-official-macx-hd-unlock-ultimate-convenience-with-free-mac-software-transferring-rip-protected-content-from-dvds-to-iphone-xs-xs-max-and-xr-devices/"><u>1. Official MacX HD: Unlock Ultimate Convenience with Free Mac Software Transferring Rip-Protected Content From DVDs to iPhone XS, XS Max, and XR Devices</u></a></li>
<li><a href="https://some-guidance.techidaily.com/1-solve-the-issue-of-missing-external-optical-drives-in-macos/"><u>1. Solve the Issue of Missing External Optical Drives in macOS</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-ultimate-budget-headphones-to-enhance-game-sounds/"><u>2024 Approved  Ultimate Budget Headphones to Enhance Game Sounds</u></a></li>
<li><a href="https://location-social.techidaily.com/3-things-you-must-know-about-fake-snapchat-location-on-vivo-s17e-drfone-by-drfone-virtual-android/"><u>3 Things You Must Know about Fake Snapchat Location On Vivo S17e | Dr.fone</u></a></li>
<li><a href="https://some-guidance.techidaily.com/windowsandmac102024/"><u>最新動画保存ツール：無料Windows&Macアプリランキングトップ10！2024年用</u></a></li>
<li><a href="https://some-guidance.techidaily.com/binge-the-2018-fifa-world-cup-top-wireless-streaming-options/"><u>Binge the 2018 FIFA World Cup: Top Wireless Streaming Options</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/bring-back-your-asus-notebooks-colorful-side/"><u>Bring Back Your Asus Notebook's Colorful Side</u></a></li>
<li><a href="https://some-guidance.techidaily.com/complete-guide-to-transferring-data-from-iphone-x-to-iphone-8-or-plus/"><u>Complete Guide to Transferring Data From iPhone X to iPhone 8 or Plus</u></a></li>
<li><a href="https://some-guidance.techidaily.com/digiarty-macxdvd-faqs-expert-answers-to-common-technical-questions-for-mac-users/"><u>Digiarty MacXDVD FAQs: Expert Answers to Common Technical Questions for Mac Users</u></a></li>
<li><a href="https://some-guidance.techidaily.com/four-effective-strategies-for-reorienting-your-quicktime-videos-on-a-mac/"><u>Four Effective Strategies for Reorienting Your QuickTime Videos on a Mac</u></a></li>
<li><a href="https://some-guidance.techidaily.com/frei-verfugbarer-film-downloads-auf-youtube-abrufen-ohne-zeitlimit/"><u>Frei Verfügbarer Film-Downloads Auf YouTube - Abrufen Ohne Zeitlimit</u></a></li>
<li><a href="https://change-location.techidaily.com/guide-how-to-unbrick-a-bricked-oppo-f25-pro-5g-phone-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Guide How To Unbrick a Bricked Oppo F25 Pro 5G Phone | Dr.fone</u></a></li>
<li><a href="https://some-guidance.techidaily.com/guide-accessing-and-enjoying-the-new-apple-tvplus-streaming-platform/"><u>Guide: Accessing and Enjoying the New Apple TV+ Streaming Platform</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-fix-error-1015-while-restoring-iphone-14-plus-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>How to fix error 1015 while restoring iPhone 14 Plus | Stellar</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-deleted-nokia-c110-contacts-an-easy-method-explained-by-fonelab-android-recover-contacts/"><u>How to Restore Deleted Nokia C110 Contacts  An Easy Method Explained.</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-a-lost-xiaomi-mix-fold-3-for-free-drfone-by-drfone-virtual-android/"><u>How to Track a Lost Xiaomi Mix Fold 3 for Free? | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-4-feasible-ways-to-fake-location-on-facebook-for-your-vivo-y27-5g-drfone-by-drfone-virtual-android/"><u>In 2024, 4 Feasible Ways to Fake Location on Facebook For your Vivo Y27 5G | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-does-airplane-mode-turn-off-gps-location-on-tecno-pova-5-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Does Airplane Mode Turn off GPS Location On Tecno Pova 5 Pro? | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-apple-iphone-se-2020-to-pc-via-usb-drfone-by-drfone-ios/"><u>In 2024, How to Mirror Apple iPhone SE (2020) to PC via USB? | Dr.fone</u></a></li>
<li><a href="https://some-guidance.techidaily.com/maintaining-original-quality-a-step-by-step-guide-on-converting-1080p-video-footage-to-720p/"><u>Maintaining Original Quality: A Step-by-Step Guide on Converting 1080P Video Footage to 720P</u></a></li>
<li><a href="https://some-guidance.techidaily.com/mastering-video-compression-top-techniques-for-optimizing-file-size-on-facebook-shares/"><u>Mastering Video Compression: Top Techniques for Optimizing File Size on Facebook Shares</u></a></li>
<li><a href="https://some-guidance.techidaily.com/robin-williams-film-anthology-top-picks-full-movie-lists-and-expert-tips-on-dvd-acquisition/"><u>Robin Williams Film Anthology: Top Picks, Full Movie Lists, and Expert Tips on DVD Acquisition</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/the-ultimate-guide-to-get-the-rare-candy-on-pokemon-go-fire-red-on-realme-c53-drfone-by-drfone-virtual-android/"><u>The Ultimate Guide to Get the Rare Candy on Pokemon Go Fire Red On Realme C53 | Dr.fone</u></a></li>
<li><a href="https://some-guidance.techidaily.com/top-pick-the-most-compatible-dvd-players-with-any-tv-ideal-for-mac-users/"><u>Top Pick: The Most Compatible DVD Players with Any TV, Ideal for Mac Users</u></a></li>
<li><a href="https://some-guidance.techidaily.com/troubleshooting-a-frozen-mac-ventura-update-effective-solutions-for-completion/"><u>Troubleshooting a Frozen Mac Ventura Update: Effective Solutions for Completion</u></a></li>
<li><a href="https://some-guidance.techidaily.com/ultimate-guide-high-quality-video-compression-techniques-for-the-web/"><u>Ultimate Guide: High-Quality Video Compression Techniques for the Web</u></a></li>
<li><a href="https://some-guidance.techidaily.com/unlock-high-quality-video-excellence-upgrade-from-windows-movie-maker-to-mp4-without-losing-a-single-detail/"><u>Unlock High-Quality Video Excellence: Upgrade From Windows Movie Maker to MP4 without Losing a Single Detail</u></a></li>
<li><a href="https://some-skills.techidaily.com/unlocking-the-top-5-virtual-title-designers-for-2024/"><u>Unlocking the Top 5 Virtual Title Designers for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/windowsmac-x-dvd/"><u>Windowsユーザー快適移行！Mac X DVDリッパーフリー版をご利用いただけますように！</u></a></li>
</ul></div>
