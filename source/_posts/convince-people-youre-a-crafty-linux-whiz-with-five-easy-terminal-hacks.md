---
title: Convince People You're a Crafty Linux Whiz with Five Easy Terminal Hacks
date: 2024-12-21T17:40:56.741Z
updated: 2024-12-24T23:35:26.753Z
tags:
  - desktop
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/ubuntu.jpg
---

## Convince People You're a Crafty Linux Whiz with Five Easy Terminal Hacks

While I am a Linux daily driver, and I do sprinkle the terminal with commands now and then, I'm by no means a hacker. That didn't stop me from looking the part, though, since it turns out several simple commands (and a whole app) exist to make you look like a star in a florid cyberthriller. Here they are and how to run them.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Vca--yEhtdo?si=7ijqjyP-oi3LYze1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1  neofetch 

![neofetch command output on an Ubuntu operating system.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/2024-02-14_16h38_17.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qNrOsjUdRz0?si=xGzhmNmtgxNTsRxN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Starting simple, neofetch is perfect for when you want to send your friends a screenshot of your sweet new Linux desktop with a terminal open to make it look like you know how to use it. You simply run the command and some stats about your system will be printed next to a big [ASCII art](https://en.wikipedia.org/wiki/ASCII%5Fart) version of your distro's logo. If you've ever checked out r/UnixPorn, you'll recognize it as one of the more popular outputs to have printed in an open terminal.

 You can install neofetch on Debian and Ubuntu-based systems with this command

sudo apt install neofetch

 On Fedora Linux, you want this command:

sudo dnf install neofetch

 If you "use Arch btw" and have Pacman installed, you can instead run this command:

sudo pacman -S neofetch

 Then simply enter the command **neofetch** in your terminal to see your unique printout. Remember that the colors used will depend on your terminal settings. If the defaults don't look good, learn [how to customize your Bash prompt](https://screen-mirror.techidaily.com/3-facts-you-need-to-know-about-screen-mirroring-honor-90-gt-drfone-by-drfone-android/).

## 2  cmatrix 

Your browser does not support the video tag. 

 I know you were waiting for it: the classic Matrix-style text waterfall animation in your terminal. Put this on with a simple command and you'll become Neo, or so your friends will think. It's also the perfect "screensaver" for a terminal you maybe keep open in another monitor for when you need it.

 You can install cmatrix with this command.

sudo apt install cmatrix

 Or, on Red Hat distributions, run this command:

sudo dnf install cmatrix

 On Arch-based systems, use pacman to install it:

sudo pacman -S cmatrix

 You run the basic version with this command:

cmatrix

 You've got several flags (short bits of text you add onto the command) that will let you customize the look or function, like -r to get rainbow colors or -s to make it act like a screensaver where any keystroke closes the program. Use the **cmatrix -h** command to see them all.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/793ViIxl4tI?si=DDBkjPlPX5bZ-f1Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3  genact 

Your browser does not support the video tag. 

 I was caught off-guard the first time I used the genact command because it seemed to be installing additional assets before running, which I thought was ridiculous for a simple text animation. The joke was on me, though, because that's just what genact does: it creates the impression it's downloading files, [crypto mining](https://vimeo-videos.techidaily.com/updated-in-2024-mastering-video-allure-securing-top-spots-with-the-vimeo-experts/), and running other random tasks when in fact nothing is happening. It has several unique modes that it cycles through at random, so you can open multiple terminal windows and run genact in each to look like you're multitasking like a pro.

 The easiest way to install it is through the Snap store, with this command:

snap install genact

 If you're not a Snap user, you can also download genact directly from [the GitHub release page](https://github.com/svenstaro/genact/releases). There are several versions, so you have to choose [your architecture](https://fox-friendly.techidaily.com/in-2024-top-professional-camera-choices-complete-360-guide-2023/) and operating system. If you're not sure, your safest bet is the one ending in "x86\_64-unknown-linux-gnu". Open a terminal, navigate to the directory genact is stored, then run **chmod +x genact-1.4.2-x86\_64-unknown-linux-gnu** (adjusting for your file name) to give the file permission to execute. Run it by typing ./ (a period and forward slash) followed by genact's file name. So for me that command looked like:

./genact-1.4.2-x86_64-unknown-linux-gnu

 If none of that setup appeals to you, you'll be happy to learn you don't need a terminal (or even a Linux distribution); you can simply [open genact in your browser](https://svenstaro.github.io/genact/). Fullscreen your browser with the F11 key for full effect.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/8U3ooyFiAB4?si=yXPQrDhMBEJwN2EZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4  hollywood 

Your browser does not support the video tag. 

 Increasing in complexity is hollywood, which generates multiple panes in your terminal that show everything from hashes to speed tests to a global map in ASCII. It's _big_, so you'll want to maximize your terminal window. It's colorful, too, and resets frequently, perfect for an eye-catching and, well, cinematic display. Its name comes from the fact it's meant to be visible "in the background of any excellent schlock technothriller," to quote the creator.

 On Debian systems, use this command to install it:

sudo apt install hollywood

 If you're a Fedora or Red Hat user, you'll want this command:

dnf install hollywood

 For Arch users, you can get it with a Pacman command:

sudo pacman -S hollywood

 Once it's installed, going hacker mode is as simple as typing **hollywood** into your terminal and hitting Enter.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cKRBWf1EDZo?si=CTNd4q450biit4eM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5  eDEX-UI 

Your browser does not support the video tag. 

 eDEX-UI doesn't actually run in your terminal, it is _itself_ a terminal emulator, which means you can run actual commands inside it, including any of the ones I've already shown you. Designed to fit perfectly in a movie about hacking or espionage, eDEX-UI also produces those beeping and whirring sounds that computers in movies do (and that we all know would be very annoying in real life). It even supports touchscreens, so you can type on that virtual keyboard with a tablet or touch monitor!

 There is some bad news: eDEX-UI is no longer maintained as a project at the time of writing. The good news is the original repository is still available and works, at least in my testing. So just go to [the eDEX-UI release page](https://github.com/GitSquared/edex-ui/releases), download the version for you (likely "eDEX-UI-Linux-x86\_64.AppImage" and run it. Don't forget that since it's [an AppImage](https://facebook-video-recording.techidaily.com/updated-in-2024-expert-picks-top-6-fb-lite-extractors/) you'll need to give it permission to execute. Right-click it and open the Properties window, then look for an executable setting. In my file browser, Dolphin, it's a checkbox in the Permissions tab labeled "Is Executable." Voila, you're hacking the planet.

---

 If you're ready to go beyond just _looking_ like a hacker, you can do a lot of cool and actually useful things in the Linux terminal. After learning [some basic commands](https://win11-tips.techidaily.com/precision-adjusting-windows-locksleep-timer/), you can start automating your daily tasks scripts, and getting started is easy with some [beginner script examples](https://common-error.techidaily.com/rebooting-woes-windows-10-troubleshooting/). You can even [use Spotify in your terminal](https://phone-solutions.techidaily.com/all-about-factory-reset-what-is-it-and-what-it-does-to-your-samsung-galaxy-s23plus-drfone-by-drfone-reset-android-reset-android/)

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
<li><a href="https://some-guidance.techidaily.com/new-inside-look-the-full-power-of-polarr-photo-editor/"><u>[New] Inside Look The Full Power of Polarr Photo Editor</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-tech-talk-video-showcase-assessment/"><u>[New] Tech Talk Video Showcase Assessment</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-expert-advice-perfected-media-import-techniques-for-windows-10-for-2024/"><u>[Updated] Expert Advice Perfected Media Import Techniques for Windows 10 for 2024</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-in-2024-the-ultimate-screening-youtubes-most-liked-creators/"><u>[Updated] In 2024, The Ultimate Screening YouTube's Most Liked Creators</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-marketing-unveiling-techniques/"><u>[Updated] Marketing Unveiling Techniques</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-master-recommendations-best-audio-crafting-pros/"><u>[Updated] Master Recommendations Best Audio Crafting Pros</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-youtube-tunes-heres-how-to-download-safely-and-free/"><u>[Updated] Youtube Tunes? Here's How to Download Safely & Free</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-the-comprehensive-key-to-efficient-morphvox-usage/"><u>2024 Approved The Comprehensive Key to Efficient MorphVOX Usage</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-the-pinnacle-of-media-excellence-top-phones-videos/"><u>2024 Approved The Pinnacle of Media Excellence Top Phones Videos</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/giggle-graphics-humorhub/"><u>Giggle Graphics HumorHub</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-fix-android-app-not-installed-error-on-realme-narzo-n53-quickly-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Android App Not Installed Error on Realme Narzo N53 Quickly? | Dr.fone</u></a></li>
<li><a href="https://win-dash.techidaily.com/installing-epson-perfection-v39-printers-on-windows-download-correct-drivers/"><u>Installing Epson Perfection V39 Printers on Windows: Download Correct Drivers!</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/picture-to-cartoon-transformation-made-easy-for-2024/"><u>Picture to Cartoon Transformation Made Easy for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/ultimate-slomo-videography-tool-assessment-for-2024/"><u>Ultimate SloMo Videography Tool Assessment for 2024</u></a></li>
</ul></div>

