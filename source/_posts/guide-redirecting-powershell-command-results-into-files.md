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


