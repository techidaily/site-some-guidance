---
title: "Effective Methods to Correct Memory System Faults in Windows 11: A Step-by-Step Guide"
date: 2024-08-31T06:09:46.596Z
updated: 2024-09-01T06:09:46.596Z
tags:
  - desktop
categories:
  - tech
thumbnail: https://thmb.techidaily.com/1f343cc2ca566c6b496acac107d8a3cfc474691f655f34c60ef016476e0a8a74.jpg
---

## Effective Methods to Correct Memory System Faults in Windows 11: A Step-by-Step Guide

### Quick Links

* [What Causes Memory Integrity Errors on Windows](https://android-location-track.techidaily.com/in-2024-how-to-intercept-text-messages-on-realme-10t-5g-drfone-by-drfone-virtual-android/)
* [Review and Update Incompatible Driver](https://facebook-video-recording.techidaily.com/updated-transition-to-non-stop-browsing-set-up-youtube-autoplay-on-fb-for-2024/)
* [Delete the Incompatible Driver](https://vp-tips.techidaily.com/updated-2024-approved-highlighting-progress-in-photo-shooting-algorithms/)
* [Download Any Available Windows Updates](https://network-issues.techidaily.com/fallout-4s-pc-problems-solved-for-you/)
* [Perform a Clean Boot](https://extra-approaches.techidaily.com/2024-approved-premium-pcandroid-mkv-player/)
* [Enable Core Integrity Using the Registry Editor](https://techidaily.com/xiaomi-14-pro-won-t-play-mkv-movies-by-aiseesoft-video-converter-play-mkv-on-android/)

### Key Takeaways

* Memory integrity errors in Windows are often caused by corrupted or outdated drivers. You can fix this issue by updating the incompatible driver.
* Alternatively, you can delete the incompatible driver to resolve the problem.
* If updating or deleting the incompatible driver does not resolve the issue, you should try other fixes such as updating Windows, performing a clean boot, or forcibly enabling memory integrity on your computer.

 Are you seeing the Memory integrity is off message in Windows Security and are unable to enable it because its toggle is grayed out? Having this feature disabled means that your system is at a risk of being invaded by malware. Read along to know what's causing this problem and how you can fix it.

##  What Causes Memory Integrity Errors on Windows

[Memory integrity](https://learn.microsoft.com/en-us/windows/security/hardware-security/enable-virtualization-based-protection-of-code-integrity) is a virtualization-based security feature that safeguards your computer against malware that tries to exploit the Windows kernel. You can turn it on or off in the Core isolation section of the Windows Security app. Open the Windows Security app, click the "Device Security" tab on the left, and scroll to Core Isolation.

 Sometimes, the memory integrity toggle may appear grayed out with a message stating, "Memory integrity is off. Your device may be vulnerable."

![Memory intergrity is off message in Windows Security.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/memory-intergrity-is-off-message-in-windows-security.jpg) 

<!-- affiliate ads begin -->
<a href="https://homestyler.sjv.io/c/5597632/2044747/22993" target="_top" id="2044747"><img src="//a.impactradius-go.com/display-ad/22993-2044747" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2044747/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 This issue is often linked to your drivers. If your drivers become corrupted due to reasons such as improper system shutdowns or [BSOD](https://visual-screen-recording.techidaily.com/updated-2024-approved-innovative-approaches-to-ppt-video-captures/), you'll likely encounter this problem.

 Another situation where you might encounter this issue is when you connect a new device to your computer. If you see this message in such cases, it suggests that your computer may not be compatible with the driver of the newly connected device.

 In addition to all those scenarios, it could simply be an interface problem. This means the feature is functioning correctly in the background, but you're seeing the message due to an interface bug in Windows 11.

 Now that you understand what usually causes the Memory integrity error on Windows 11, let's check out some of the solutions to fix the problem. 

##  Review and Update Incompatible Driver

 In the Core isolation window, where you'll see the Memory integrity is off message, there will be a "Review Incompatible Drivers" option below the message. When you click this option, you'll see the incompatible driver that is causing the issue.

![Review Incompatible Drivers option in the Windows Security app.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/review-incompatible-drivers-option-in-the-windows-security-app.jpg) 

<!-- affiliate ads begin -->
<a href="https://arkmc.pxf.io/c/5597632/427477/5172" target="_top" id="427477"><img src="//a.impactradius-go.com/display-ad/5172-427477" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://arkmc.pxf.io/i/5597632/427477/5172" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 You'll see information about the incompatible driver, such as its product name, driver version, and published name.

![Incompatible drivers page in Windows Security.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/incompatible-drivers-page-in-windows-security.jpg) 

 If clicking on the driver's name does not provide all these details, you can execute a DISM command to retrieve them. To run the DISM command, open the Start menu, type **Command Prompt** in the search bar, and select "Run as Administrator."

 In the elevated Command Prompt window, input the following command and press Enter:

        `dism /online /get-drivers /format:table`
    
![Driver list command in Command Prompt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/driver-list-command-in-command-prompt.jpg) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087407/7443" target="_top" id="2087407"><img src="//a.impactradius-go.com/display-ad/7443-2087407" border="0" alt="" width="600" height="500"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 This command will list all the drivers installed on your computer along with other information. You'll have to find the incompatible driver that was flagged in Windows Security under the Published Name column.

 Once you've located it, make a note of its provider name. After that, you'll have to update the incompatible driver. This is because the issue likely occurs due to a corrupted or outdated driver; in either situation, updating the driver should fix the issue. 

 To update the driver, [open the Device Manager](https://desktop-recording.techidaily.com/updated-2024-approved-easily-record-lenovo-laptop-screen-activity/), click "View," and select "Devices by Driver."

![Devices by Driver option in the Device Manager.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/devices-by-driver-option-in-the-device-manager.jpg) 

<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1494880/17238" target="_top" id="1494880"><img src="//a.impactradius-go.com/display-ad/17238-1494880" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1494880/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Locate the incompatible driver, double-click on it, then right-click the relevant device and choose "Update Driver."

![Update driver option in Device Manager.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/update-driver-option-in-device-manager.jpg) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4737285&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/b2f83c409ce63012229fb9cd465bdcfe/products/copy_reporting_system.png" border="0">  KoolReport Pro  is an advanced solution for creating data reports and dashboards in PHP. Equipped with all  extended packages , KoolReport Pro is able to connect to various datasources, perform advanced data analysis, construct stunning charts and graphs and export your beautiful work to PDF, Excel, JPG or other formats. Plus, it includes powerful built-in reports such as pivot report and drill-down report which will save your time in building ones. 

 It will help you to write dynamic data reports easily, to construct intuitive dashboards or to build a whole business intelligence cockpit. 

  KoolReport Pro  package goes with Full Source Code, Royal Free, ONE (1) Year Priority Support, ONE (1) Year Free Upgrade and 30-Days Money Back Guarantee. 

  Developer License  allows  Single Developer  to create Unlimited Reports, deploy on Unlimited Servers and able deliver the work to Unlimited Clients. </a>
<!-- affiliate ads end -->
 Choose "Search Automatically for Drivers." Then, Windows will try to find and download the latest driver for that device. If Windows is unable to find the update, you can visit the device manufacturer's website to download the latest driver update.

 For instance, if the issue relates to your keyboard driver, then visit your keyboard manufacturer's website and download the most recent driver update for your keyboard. The update will be in .exe format, so you can install it like any other Windows application. After updating the driver, [restart your computer](https://screen-video-capture.techidaily.com/updated-in-2024-addressing-mute-problems-in-obs-live-recording/) and check if you're still getting a memory integrity error. 

##  Delete the Incompatible Driver

 If updating the incompatible driver was unable to fix the problem, you should consider deleting it completely. Don't worry, deleting the driver will not have any adverse effects, as Windows will automatically reinstall the driver once you use the related device again. However, this time Windows will install the newest working driver for that device.

 To delete the incompatible driver, [open Command Prompt as an administrator](https://screen-mirror.techidaily.com/how-to-screen-mirroring-xiaomi-14-ultra-drfone-by-drfone-android/) and execute the following command to view the list of installed drivers.

        `dism /online /get-drivers /format:table`
    
 Type the command below and press Enter. Make sure to replace <Published name> with the published name of the incompatible driver.

        `pnputil /delete-driver <Publisher Name> /uninstall /force​`
    
 For example, if the published name of the incompatible driver is oem58.inf, then the command will be:

        `pnputil /delete-driver oem58.inf /uninstall /force​`
    
![Driver removal command in Command Prompt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/driver-removal-command-in-command-prompt.jpg) 

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698824&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/dex3pro-screenshot-homepage.png" border="0">PCDJ DEX 3 for Windows & MAC is the total entertainment DJ software solution, offering audio, video, and karaoke mixing ability. Automatic beat-sync, smart looping, 4 decks, DJ MIDI controller support, Karaoke Streaming and much more. 
DEX 3 meets the demands of today’s versatile DJ, without compromise! 
DEX 3 (Audio, Video and Karaoke Mixing Software for Windows/MAC | 3 Activations and Free Updates)</a>
<!-- affiliate ads end -->
 Once the command is executed, you'll see the "Driver Package Uninstalled" message. After that, restart your computer and then check if you're still facing the problem.

##  Download Any Available Windows Updates

 The issue can also occur due to a bug in the Windows version you are currently using. A bug in the Windows Security app could also be the reason behind the problem.

 Either way, you should check for and [download any available Windows updates](https://howto.techidaily.com/fix-unfortunately-settings-has-stopped-on-realme-v30-quickly-drfone-by-drfone-fix-android-problems-fix-android-problems/). Downloading Windows updates will not only update the Windows version but may also include updates for the Windows Security app that could resolve the issue.

 Once you have downloaded the available updates for your Windows PC, open the Windows Security app and check if the "Memory integrity is off" message still appears.

##  Perform a Clean Boot

 Your computer has numerous processes and services running in the background that help the operating system run smoothly. Sometimes, these processes or services may interfere with other programs, which may lead to various issues, including the one at hand.

 You can identify that problematic agent by [performing a clean boot](https://screen-capture.techidaily.com/new-affordable-facetime-replacements-for-android/). Once you have identified the problematic service or process, you can either delete it or download any available driver updates for it.

##  Enable Core Integrity Using the Registry Editor

 If none of the above solutions were helpful, the last step you can take is to use the Registry Editor to forcibly enable the memory integrity feature. However, you must be very careful when applying this fix, as a single incorrect edit in the registry can make your system unstable.

 To be on the safe side, you must [back up the registry](https://screen-recording.techidaily.com/quick-start-guide-dells-simple-screen-recording-methods-for-2024/) and [create a restore point](https://instagram-video-files.techidaily.com/updated-in-2024-multiplying-joy-sharing-a-pile-of-photos-and-videos-with-instagram/). This way, you can easily [restore your computer](https://article-posts.techidaily.com/in-2024-proven-methods-to-infuse-engaging-dialogue-in-videos/) to a working state in case any issues arise during the registry editing process.

 Once you have taken these essential safety measures, let's begin. First, open the Start menu, type **Registry Editor** in the search bar, and press Enter.

 In the Registry Editor, navigate to the following location:

        `HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\DeviceGuard\Scenarios\HypervisorEnforcedCodeIntegrity`
    
 Double-click the "Enabled" key, type **1** in the Value data field, and click "OK."

![Value data field in Enabled value edit window.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/value-data-field-in-enabled-value-edit-window.jpg) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2014/02/Project-Manager-3D-Models-4-800x800.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->
 Restart your computer, and you will find that you can activate the memory integrity toggle without any problems.

---

 We hope the above solutions were helpful in fixing the problem. Memory integrity is an important security feature, and now that you have enabled it, you shouldn't worry about malicious agents exploiting critical parts of your Windows operating system.

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


