---
title: "Command Prompt Mastery: Quick and Easy Ways to Lock Your Windows 10 Computer"
date: 2024-12-23T20:58:59.118Z
updated: 2024-12-24T20:08:53.338Z
tags:
  - deals
categories:
  - tech
thumbnail: https://thmb.techidaily.com/0b08703f0711aa278d64397e12272d17e9628dac2d52aa808134158c2c218743.jpg
---

## Command Prompt Mastery: Quick and Easy Ways to Lock Your Windows 10 Computer

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2Iv3DjT2Fyw?si=pR_z8ZDDVGF2MvKJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Quick Links

* [Lock Your Windows 10 PC Using Command Prompt](https://vp-tips.techidaily.com/new-audiovisual-adaptability-in-free-fire-for-2024/)
* [Set the Lock Screen Timeout Setting Using Command Prompt](https://eaxpv-info.techidaily.com/new-finding-a-different-way-to-naming-your-channel-with-filmora-for-2024/)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/n4cc4BSqJls?si=Hkd9vwQDqeCGN7XG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Key Takeaways

* To lock your Windows PC using Command Prompt, run "**Rundll32.exe user32.dll,LockWorkStation"** in the Command Prompt
* To set the lock screen timeout, run "**powercfg.exe /SETACVALUEINDEX SCHEME\_CURRENT SUB\_VIDEO VIDEOCONLOCK <time>"** in Command Prompt as Admin
* Activate the lock screen timeout setting by running "**powercfg.exe /SETACTIVE SCHEME\_CURRENT"** after you set the timeout.

 One of the first rules of cyber security is to always lock your PC before stepping away. While it may not be the quickest way to lock your Windows 10 PC, you can do it using the Command Prompt.

##  Lock Your Windows 10 PC Using Command Prompt

 First, [open the Command Prompt](https://android-frp.techidaily.com/in-2024-step-by-step-tutorial-how-to-bypass-oppo-a78-frp-by-drfone-android/) on your PC by opening the Start menu, typing “cmd” in the Windows Search bar, and then selecting “Command Prompt” from the search results.

![Click the Start button, search for 'cmd,' then open 'Command Prompt.'](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/1-launch-cmd.png) 

 Command Prompt will now open. Here, run this command to lock your Windows 10 PC.

Rundll32.exe user32.dll,LockWorkStation

![Locking your PC with Command Prompt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/2-lock-pc-command-prompt.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RJNYTGHVlLc?si=heERQcpMi77lqToE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once executed, your PC will be locked. You'll have to sign back in with your PIN, password, or whatever sign-in method you usually use.

##  Set the Lock Screen Timeout Setting Using Command Prompt

 Once you’ve locked your PC, the lock screen will generally be displayed for a certain amount of time before it time outs. You can set the amount of time that needs to pass before timing out using the Command Prompt.

 To do this, you’ll need to [open Command Prompt as an admin](https://screen-mirror.techidaily.com/how-to-screen-mirroring-xiaomi-14-ultra-drfone-by-drfone-android/). Do so by typing “cmd” in the Windows Search bar and then right-clicking “Command Prompt” from the results. Next, select “Run As Administrator” from the menu that appears.

![Launching Command Prompt as admin.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/3-launch-cmd.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_7AYCS7zBU0?si=7R9oIpE4hyEbtk3x" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 With Command Prompt open, run this command.

powercfg.exe /SETACVALUEINDEX SCHEME_CURRENT SUB_VIDEO VIDEOCONLOCK <time>

 Replace `<time>` with your desired amount of time in seconds. That means if you want to time out the lock screen after two minutes, you’d enter this command:

powercfg.exe /SETACVALUEINDEX SCHEME_CURRENT SUB_VIDEO VIDEOCONLOCK 120

![Change the timeout to 120.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/4-changing-timeout-to-120.png) 

 This command sets the lock screen timeout setting for your PC if it’s plugged in to a power source. To set the lock screen timeout setting for your PC if it’s running on battery, change`/SETACVALUEINDEX` to`/SETDCVALUEINDEX` and run the command as normal.

 Next, run this command:

powercfg.exe /SETACTIVE SCHEME_CURRENT

![Apply the setting to the currently active scheme.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/5-set-active.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/w7c5EHp-GDw?si=UTw7lZR0wTmRjp8W" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-how-to-move-and-manage-your-social-snapshots-locally/"><u>[New] In 2024, How To Move and Manage Your Social SnapShots Locally</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-no-8-visual-artists-choice-for-photo-assembly/"><u>[New] No. 8 Visual Artist's Choice for Photo Assembly</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-3-easy-youtube-audio-extraction-methods-free-and-secure-for-2024/"><u>[Updated] 3 Easy YouTube Audio Extraction Methods Free & Secure for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-the-step-by-step-process-for-perfecting-screencast-video-quality/"><u>[Updated] In 2024, The Step-by-Step Process for Perfecting Screencast Video Quality</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-mastering-instagram-filters-applying-them-to-old-memories/"><u>[Updated] Mastering Instagram Filters Applying Them to Old Memories</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-ultimate-quick-access-handbook-for-rapid-srt-to-text-change/"><u>[Updated] The Ultimate, Quick-Access Handbook for Rapid SRT to Text Change</u></a></li>
<li><a href="https://screen-capture.techidaily.com/1715701161630-best-free-call-apps-on-android-ranks-them/"><u>Best Free Call Apps on Android, Ranks Them!</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-affordable-accessible-top-10-budget-friendly-mobile-viewing-apps/"><u>In 2024, Affordable, Accessible Top 10 Budget-Friendly Mobile Viewing Apps</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-fix-my-motorola-moto-g73-5g-location-is-wrong-drfone-by-drfone-virtual-android/"><u>In 2024, How to Fix My Motorola Moto G73 5G Location Is Wrong | Dr.fone</u></a></li>
<li><a href="https://youtube-web.techidaily.com/24-maximizing-yt-videos-for-igtv-presence/"><u>In 2024, Maximizing YT Videos for IGTV Presence</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-ultimate-selection-best-8-websites-with-striking-3d-and-glamourous-text/"><u>In 2024, Ultimate Selection Best 8 Websites with Striking 3D & Glamourous Text</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-unlocking-studio-secrets-extensive-xvideoreview/"><u>In 2024, Unlocking Studio Secrets Extensive XVideoReview</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-unveiling-lost-reddit-content-instant-access-techniques/"><u>In 2024, Unveiling Lost Reddit Content Instant Access Techniques</u></a></li>
<li><a href="https://some-guidance.techidaily.com/unveiling-the-secrets-of-srt-creation-from-text-formats-for-2024/"><u>Unveiling the Secrets of SRT Creation From Text Formats for 2024</u></a></li>
</ul></div>

