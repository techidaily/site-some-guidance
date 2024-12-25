---
title: Easy Guide to Creating Directories & Text Documents via CMD in Windows
date: 2024-12-18T20:43:08.555Z
updated: 2024-12-24T18:28:12.165Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/nlwr9LjJ-ng?si=I6UNAtfBkY2FTceu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/sXLLPY11of0?si=-3YNnpnO0wbc0K_-" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 To [open Command Prompt](https://android-frp.techidaily.com/in-2024-step-by-step-tutorial-how-to-bypass-oppo-a78-frp-by-drfone-android/), click the Start button, search for **command prompt**, then click the relevant result or press Enter. While making folders, if you encounter an error, [run Command Prompt as an admin](https://instagram-videos.techidaily.com/updated-2024-approved-unlocking-instagram-potential-a-comprehensible-guide/) by right-clicking the utility and choosing "Run as Administrator." Make sure to select "Yes" in the User Account Control prompt.

!['Run as Administrator' highlighted for Command Prompt in Start Menu.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/2-open-command-prompt-as-admin.jpg) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LlVkEwpjKKo?si=hXi-mchMaJvbnIzM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 After opening Command Prompt, type **cd**, press Spacebar, paste the folder path you copied by pressing Ctrl+V, and press Enter. This [makes your chosen folder the current working directory](https://extra-information.techidaily.com/quick-and-easy-iphone-burst-techniques/) in the tool. Each command you run will perform the specified action in this directory.

!['cd' command typed in Command Prompt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/3-change-current-directory-command-prompt.jpg) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2NU63YqpVqw?si=uoJs0-nZYAkILqXx" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  Create a Single Folder

 To make a single folder, type the following command, replacing "FolderName" with the name you want to assign to your folder. Then, press Enter.

mkdir FolderName

 For example, to make a folder named "Mahesh", use the following command:

mkdir Mahesh

![Create a single folder from Command Prompt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/4-create-single-folder-cmd.jpg) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/P6Wfzj6YNDM?si=WRZQD9zCdQ1_tW1b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 To create a folder that has spaces in its name, enclose the name with double quotes like this:

mkdir “Mahesh Makvana”

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

 Make sure to enclose the folder name with double quotes if its name has spaces.

##  Create a File with Command Prompt

 Command Prompt allows you to create empty files, which you can then use with appropriate apps. The syntax for creating a new file is as follows:

type nul > name.ext

 Here, "name" is the name of the file you want to create and "ext" is the [extension of the file](https://twitter-videos.techidaily.com/updated-the-dos-and-donts-of-youtube-videos-on-twitter-for-2024/).

 For example, to make a text file named document.txt, you’ll use the following command:

type nul > document.txt

![Create a file with Command Prompt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/7-create-file-cmd.jpg) 

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
<li><a href="https://fox-info.techidaily.com/new-in-2024-virtualblender-for-all-operating-systems/"><u>[New] In 2024, VirtualBlender for All Operating Systems</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-the-path-to-perfect-podcast-scripts-writing-techniques-and-free-example-guides/"><u>[New] The Path to Perfect Podcast Scripts Writing Techniques & Free Example Guides</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-2024-approved-the-power-of-politeness-in-growing-your-audience/"><u>[Updated] 2024 Approved The Power of Politeness in Growing Your Audience</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-translate-compressed-files-into-subtitle-format-srt/"><u>[Updated] Translate Compressed Files Into Subtitle Format (SRT)</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-tunetracker-outside-of-dacast-realm/"><u>[Updated] TuneTracker Outside of DaCast Realm</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-techniques-for-ensuring-unbiased-decision-making/"><u>2024 Approved Techniques For Ensuring Unbiased Decision-Making</u></a></li>
<li><a href="https://location-fake.techidaily.com/3-ways-to-change-location-on-facebook-marketplace-for-samsung-galaxy-s23-fe-drfone-by-drfone-virtual-android/"><u>3 Ways to Change Location on Facebook Marketplace for Samsung Galaxy S23 FE | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/202n4cd/"><u>必看202n4年度自由複製程式：簡易操作下，完成無比CD或重點電影的即時克隆</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-do-i-stop-someone-from-tracking-my-samsung-galaxy-s23-ultra-drfone-by-drfone-virtual-android/"><u>How Do I Stop Someone From Tracking My Samsung Galaxy S23 Ultra? | Dr.fone</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-the-soundtrack-of-your-phone-classic-tones-download-site-guide/"><u>In 2024, The Soundtrack of Your Phone Classic Tones Download Site Guide</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-tips-for-a-pristine-image-canvas-background-technique/"><u>In 2024, Tips for a Pristine Image Canva's Background Technique</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-top-10-streaming-software-in-the-gaming-world/"><u>In 2024, Top 10 Streaming Software in the Gaming World</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-top-premier-pro-templates-for-the-year-2023/"><u>In 2024, Top Premier Pro Templates for the Year 2023</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/powerhouse-performance-in-small-packages-top-mini-pc-picks-for-gamers/"><u>Powerhouse Performance in Small Packages: Top Mini PC Picks for Gamers</u></a></li>
<li><a href="https://fake-location.techidaily.com/prevent-cross-site-tracking-on-realme-c51-and-browser-drfone-by-drfone-virtual-android/"><u>Prevent Cross-Site Tracking on Realme C51 and Browser | Dr.fone</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/qidi-techs-q1-pro-headset-uncovered-a-detailed-performance-assessment-for-gamers/"><u>QIDI Tech's Q1 Pro Headset Uncovered: A Detailed Performance Assessment for Gamers.</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/step-by-step-guide-to-navigating-io-screener/"><u>Step-by-Step Guide to Navigating IO Screener</u></a></li>
<li><a href="https://sound-issues.techidaily.com/step-by-step-solutions-for-fixing-tozo-t6-non-functionality-on-windows-11/"><u>Step-by-Step Solutions for Fixing Tozo T6 Non-Functionality on Windows 11</u></a></li>
<li><a href="https://some-guidance.techidaily.com/unleashing-potential-pilots-choice-top-10-drone-must-haves-for-2024/"><u>Unleashing Potential Pilot's Choice - Top 10 Drone Must-Haves for 2024</u></a></li>
</ul></div>

