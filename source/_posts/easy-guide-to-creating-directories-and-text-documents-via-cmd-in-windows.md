---
title: Easy Guide to Creating Directories & Text Documents via CMD in Windows
date: 2024-08-31T06:09:45.034Z
updated: 2024-09-01T06:09:45.034Z
tags:
  - desktop
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/11/52880885497_b08e2e684f_o-4.jpg
---

## Easy Guide to Creating Directories & Text Documents via CMD in Windows

### Quick Links

* [Before You Begin: Copy the Folder Path and Launch Command Prompt](https://desktop-recording.techidaily.com/updated-iphone-filmmaking-101-capturing-time-in-pixels/)
* [Create a Single Folder](https://howto.techidaily.com/troubleshooting-guide-how-to-fix-an-unresponsive-honor-x7b-screen-drfone-by-drfone-fix-android-problems-fix-android-problems/)
* [Create a Folder Inside Another Folder (Subfolder)](https://www.howtogeek.com/how-to-create-folders-and-files-from-windows-command-prompt/#create-a-folder-inside-another-folder-subfolder)
* [Create Multiple Folders at Once](https://apple-account.techidaily.com/how-to-delete-icloud-account-on-apple-iphone-xr-without-password-by-drfone-ios/)
* [Create a File with Command Prompt](https://fake-location.techidaily.com/thinking-about-changing-your-netflix-region-without-a-vpn-on-infinix-hot-40i-drfone-by-drfone-virtual-android/)

### Key Takeaways

* To create a folder with Command Prompt, use the mkdir command followed by the folder name.
* Mkdir can also be used to create nested folders, multiple folders simultaneously, or a combination of both.
* If you want to create a file, enter type in Command Prompt, followed by nul > filename.ext, replacing ".ext" with the file type you want.

 Whether you’re looking to create a script, make several folders at once, or you simply prefer command-line methods over graphical ones, it’s quick and easy to make folders or files using Command Prompt. We’ll show you how to do it on your Windows 11 or Windows 10 PC.

##  Before You Begin: Copy the Folder Path and Launch Command Prompt

 To use the following methods, you must first copy the path of the folder where you’ll create new folders or files, and then run the Command Prompt utility.

 To copy a folder’s full path, [launch File Explorer](https://pokemon-go-android.techidaily.com/how-to-get-and-use-pokemon-go-promo-codes-on-realme-c67-4g-drfone-by-drfone-virtual-android/) using Windows+E and find your folder. Hold down the Shift key on your keyboard, right-click your folder, and choose "Copy as Path."

!['Copy as Path' highlighted for a folder on a Windows PC.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/1-copy-folder-path-windows.jpg) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=11224199&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/copy_boxshot_lyricvideo.png" border="0">Lyric Video Creator Professional Version</a>
<!-- affiliate ads end -->
 To [open Command Prompt](https://android-frp.techidaily.com/in-2024-step-by-step-tutorial-how-to-bypass-oppo-a78-frp-by-drfone-android/), click the Start button, search for **command prompt**, then click the relevant result or press Enter. While making folders, if you encounter an error, [run Command Prompt as an admin](https://instagram-videos.techidaily.com/updated-2024-approved-unlocking-instagram-potential-a-comprehensible-guide/) by right-clicking the utility and choosing "Run as Administrator." Make sure to select "Yes" in the User Account Control prompt.

!['Run as Administrator' highlighted for Command Prompt in Start Menu.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/2-open-command-prompt-as-admin.jpg) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=174416&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.easygifanimator.net/images/gif-animator.png" border="0">Easy GIF Animator is a powerful animated GIF editor and the top tool for creating animated pictures, banners, buttons and GIF videos. You get extensive animation editing features, animation effects, unmatched image quality and optimization for the web. No other GIF animation software matches our features and ease of use, that's why Easy GIF Animator is so popular.</a>
<!-- affiliate ads end -->
 After opening Command Prompt, type **cd**, press Spacebar, paste the folder path you copied by pressing Ctrl+V, and press Enter. This [makes your chosen folder the current working directory](https://extra-information.techidaily.com/quick-and-easy-iphone-burst-techniques/) in the tool. Each command you run will perform the specified action in this directory.

!['cd' command typed in Command Prompt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/3-change-current-directory-command-prompt.jpg) 

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
##  Create a Single Folder

 To make a single folder, type the following command, replacing "FolderName" with the name you want to assign to your folder. Then, press Enter.

mkdir FolderName

 For example, to make a folder named "Mahesh", use the following command:

mkdir Mahesh

![Create a single folder from Command Prompt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/4-create-single-folder-cmd.jpg) 

 To create a folder that has spaces in its name, enclose the name with double quotes like this:

mkdir “Mahesh Makvana”

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653808&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
##  Create a Folder Inside Another Folder (Subfolder)

 One way to make a folder inside another folder is to make that other folder the current working directory. To do that, type **cd**, press Spacebar, enter the name of the folder in which you want to create a new folder, and press Enter. Then, type the following command, replace "MyFolder" with the name you want to give to your new folder, and press Enter.

mkdir MyFolder

 Another way to create a folder inside a folder is to specify the other folder right in the mkdir command itself. For example, if you have a subfolder named "Photos" and you want to create a new folder named "Personal" inside it, use the following command:

mkdir Photos\Personal

![Create a subfolder using Command Prompt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/5-create-subfolder-cmd.jpg) 

##  Create Multiple Folders at Once

 To [make several folders at once](https://phone-solutions.techidaily.com/in-2024-what-are-location-permissions-life360-on-motorola-razr-40-ultra-drfone-by-drfone-virtual-android/), add the required folder names to the mkdir command.

 For example, to create three separate folders named Documents, Photos, and Videos, use the following command:

mkdir Documents Photos Videos

![Create multiple folders with Command Prompt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/6-create-multiple-folders-cmd.jpg) 

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1821134/17882" target="_top" id="1821134"><img src="//a.impactradius-go.com/display-ad/17882-1821134" border="0" alt="" width="320" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1821134/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Make sure to enclose the folder name with double quotes if its name has spaces.

##  Create a File with Command Prompt

 Command Prompt allows you to create empty files, which you can then use with appropriate apps. The syntax for creating a new file is as follows:

type nul > name.ext

 Here, "name" is the name of the file you want to create and "ext" is the [extension of the file](https://twitter-videos.techidaily.com/updated-the-dos-and-donts-of-youtube-videos-on-twitter-for-2024/).

 For example, to make a text file named document.txt, you’ll use the following command:

type nul > document.txt

![Create a file with Command Prompt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/7-create-file-cmd.jpg) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4572700&QTY=1&AFFILIATE=108875&CART=1"><img src="	https://www.tubedigger.com/wp-content/uploads/2020/08/tubedigger-software-new.png" border="0">TubeDigger - online video downloader from mostly any site</a>
<!-- affiliate ads end -->
 To create a text file and add some actual text to it, use the following command. Replace "Welcome to How-To Geek" with the text you want to add and "howtogeek" with the name you want to use for the file.

echo Welcome to How-To Geek > howtogeek.txt

 When you open howtogeek.txt in a text editor you'll find it has "Welcome to How-To Geek" written in it. 

---

 And that’s how you make folders and files without using graphical tools on your Windows machine.

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
<li><a href="https://screen-sharing-recording.techidaily.com/1716069981133-new-in-2024-best-linux-screen-capture-software-ranked/"><u>[New] In 2024, Best Linux Screen Capture Software Ranked!</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-in-2024-smart-choices-best-video-call-programs-on-devices/"><u>[New] In 2024, Smart Choices  Best Video Call Programs on Devices</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-inside-out-a-thorough-examination-of-dji-phantom-4/"><u>[New] Inside Out  A Thorough Examination of DJI Phantom 4</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-2024-approved-reactivate-and-enhance-photo-viewing-with-ease-win-11/"><u>[Updated] 2024 Approved  Reactivate and Enhance Photo Viewing with Ease (Win 11)</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-live-broadcast-converter-decoder/"><u>[Updated] Live Broadcast Converter Decoder</u></a></li>
<li><a href="https://some-guidance.techidaily.com/1-top-high-definition-video-player-apps-for-macos-ultimate-guide-for-el-capitan-users/"><u>1. Top High-Definition Video Player Apps for macOS - Ultimate Guide for El Capitan Users</u></a></li>
<li><a href="https://some-guidance.techidaily.com/macx-iphone-ipad-androidgoogle/"><u>最高にするMacXモバイル - iPhone iPad AndroidおよびGoogleデバイス向け動画変換器</u></a></li>
<li><a href="https://some-guidance.techidaily.com/appleand-macx-mediatrans-ios/"><u>Appleデバイス同期&管理 完全解析：MacX MediaTrans使い方指南 - iOS端末への写真・動画・音楽共有</u></a></li>
<li><a href="https://some-guidance.techidaily.com/comprehensive-macx-dvd-converter-pro-tutorial-mastering-mp4-mov-and-ios-format-conversions-on-mac/"><u>Comprehensive MacX DVD Converter Pro Tutorial: Mastering MP4, MOV and iOS Format Conversions on Mac</u></a></li>
<li><a href="https://some-guidance.techidaily.com/comprehensive-tutorial-on-downgrading-your-macs-operating-system-from-ventura-to-monterey-or-older-oses/"><u>Comprehensive Tutorial on Downgrading Your Mac's Operating System From Ventura To Monterey or Older OSes</u></a></li>
<li><a href="https://some-guidance.techidaily.com/conversion-video-sans-limites-avec-freemake-sur-macos-instructions-de-download-gratuitement/"><u>Conversion Vidéo Sans Limites Avec Freemake Sur macOS - Instructions De Download Gratuitement</u></a></li>
<li><a href="https://some-guidance.techidaily.com/convert-videos-seamlessly-with-macx-free-video-converter-across-all-formats-and-gadgets/"><u>Convert Videos Seamlessly with MacX Free Video Converter Across All Formats and Gadgets!</u></a></li>
<li><a href="https://some-guidance.techidaily.com/descubre-las-ventajas-de-comprar-la-aplicacion-mediatrans-en-linea-con-descuento/"><u>Descubre Las Ventajas De Comprar La Aplicación MediaTrans en Línea Con Descuento</u></a></li>
<li><a href="https://some-guidance.techidaily.com/effortless-conversion-change-m4v-files-into-mp4-using-handbrake/"><u>Effortless Conversion: Change M4V Files Into MP4 Using HandBrake</u></a></li>
<li><a href="https://some-guidance.techidaily.com/enhance-your-ipad-air-experience-flawless-wmv-video-playback-tutorial/"><u>Enhance Your iPad Air Experience: Flawless WMV Video Playback Tutorial</u></a></li>
<li><a href="https://win-dash.techidaily.com/ensuring-razer-naga-compatibility-driver-downloads-and-updates-on-windows-systems/"><u>Ensuring Razer Naga Compatibility: Driver Downloads & Updates on Windows Systems</u></a></li>
<li><a href="https://some-guidance.techidaily.com/get-your-favorite-disney-tunes-for-free-childrens-songs-iconic-scores-and-enchanting-princess-ballads/"><u>Get Your Favorite Disney Tunes for Free! Children's Songs, Iconic Scores, and Enchanting Princess Ballads</u></a></li>
<li><a href="https://tech-hub.techidaily.com/going-beyond-chatgpt-what-does-the-future-hold-for-generative-ai-and-chatbots/"><u>Going Beyond ChatGPT: What Does the Future Hold for Generative AI and Chatbots?</u></a></li>
<li><a href="https://some-guidance.techidaily.com/herausragende-iphone-klingeltone-kreieren-top-klingelton-editor-fur-iphones/"><u>Herausragende iPhone-Klingeltöne Kreieren - Top Klingelton-Editor Für iPhones</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-5-ways-to-track-infinix-smart-7-hd-without-app-drfone-by-drfone-virtual-android/"><u>In 2024, 5 Ways to Track Infinix Smart 7 HD without App | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-protecting-your-privacy-how-to-remove-apple-id-from-iphone-13-pro-max-by-drfone-ios/"><u>In 2024, Protecting Your Privacy How To Remove Apple ID From iPhone 13 Pro Max</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-unlock-apple-iphone-11-pro-max-without-passcode-easily-by-drfone-ios/"><u>In 2024, Unlock Apple iPhone 11 Pro Max Without Passcode Easily</u></a></li>
<li><a href="https://some-guidance.techidaily.com/learn-how-to-speed-up-mp4-compression-while-preserving-image-clarity-an-online-guide/"><u>Learn How to Speed Up MP4 Compression While Preserving Image Clarity: An Online Guide</u></a></li>
<li><a href="https://some-guidance.techidaily.com/macx-dvd-ripper-pro-dvdiphoneipadipodmp4mov/"><u>MacX DVD Ripper Pro: 完全なユーザーマニュアル - DVDからiPhone、iPad、iPod用MP4/MOVに簡単リッピングガイド</u></a></li>
<li><a href="https://some-guidance.techidaily.com/macx-dvd-ripper-pro-a-cost-free-way-to-transform-dvd-audiovideo-into-mp3-and-mp4-for-macos-users/"><u>MacX DVD Ripper Pro: A Cost-Free Way to Transform DVD Audio/Video Into MP3 & MP4 for macOS Users</u></a></li>
<li><a href="https://some-guidance.techidaily.com/macx-dvd-video-converter-pro-pack-online-order-enjoy-exclusive-discounts-on-official-site/"><u>MacX DVD Video Converter Pro Pack Online Order - Enjoy Exclusive Discounts on Official Site</u></a></li>
<li><a href="https://some-guidance.techidaily.com/1724766284382-macx-mediatrans/"><u>MacX MediaTrans 在线下单-专业版可信任的数据传输解决方案</u></a></li>
<li><a href="https://some-guidance.techidaily.com/quick-and-easy-video-downloader-for-mac-atube-catcher/"><u>Quick and Easy Video Downloader for Mac - ATube Catcher</u></a></li>
<li><a href="https://some-guidance.techidaily.com/reibungslos-von-mxf-in-beliebte-videoformate-konvertieren-speziell-fur-apple-nutzer/"><u>Reibungslos Von MXF in Beliebte Videoformate Konvertieren, Speziell Für Apple-Nutzer</u></a></li>
<li><a href="https://some-guidance.techidaily.com/steven-spielbergs-legendary-cinema-top-titles-that-defined-an-era-and-outlived-it/"><u>Steven Spielberg's Legendary Cinema: Top Titles That Defined an Era and Outlived It</u></a></li>
<li><a href="https://some-guidance.techidaily.com/successful-setup-a-step-by-step-guide-to-downloading-and-installing-handbrake-v100-on-windows-or-macos/"><u>Successful Setup: A Step-by-Step Guide to Downloading & Installing HandBrake v1.0.0 on Windows or macOS</u></a></li>
<li><a href="https://data-wizards.techidaily.com/tackle-errored-avs-mpeg-2-files/"><u>Tackle Errored AVS, MPEG-2 Files</u></a></li>
<li><a href="https://some-guidance.techidaily.com/troubleshooting-tips-overcoming-the-ios-17-update-installation-hurdle-for-iphone-and-ipad-users/"><u>Troubleshooting Tips: Overcoming the iOS 17 Update Installation Hurdle for iPhone and iPad Users</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/ultimate-guide-to-the-lg-bp350-visual-experience/"><u>Ultimate Guide to the LG BP350 Visual Experience</u></a></li>
<li><a href="https://some-guidance.techidaily.com/unveiling-heif-and-jpeg-essential-differences-explained/"><u>Unveiling HEIF and JPEG: Essential Differences Explained</u></a></li>
<li><a href="https://some-guidance.techidaily.com/1724766870962-dvd/"><u>ディズニーコピーガードキャンセルで快適にDVDをリッピング：フリーソフトウェアの最新メソッド</u></a></li>
</ul></div>
