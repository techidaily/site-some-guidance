---
title: "Step-by-Step Guide: Verify Linux Kernel and OS Release in a Jiffy!"
date: 2024-08-31T06:11:27.855Z
updated: 2024-09-01T06:11:27.855Z
tags:
  - desktop
categories:
  - tech
thumbnail: https://thmb.techidaily.com/3bcdc30700e11e0dc89d352ba121db6f054908533edda16b2785562f97192408.jpg
---

## Step-by-Step Guide: Verify Linux Kernel and OS Release in a Jiffy!

### Quick Links

* [Rolling and Point Releases](https://howto.techidaily.com/why-does-my-motorola-razr-40-keep-turning-off-by-itself-6-fixes-are-here-drfone-by-drfone-fix-android-problems-fix-android-problems/)
* [The lsb\_release Command](https://some-techniques.techidaily.com/exploring-the-4k-marvel-sony-xperia-xz-premium-reviewed-for-2024/)
* [The /etc/os-release File](https://win11.techidaily.com/from-sealed-boxes-to-digital-realm-unlocking-windows-11-with-a-window-7-key/)
* [The /etc/issue File](https://android-frp.techidaily.com/how-to-bypass-google-frp-lock-on-lava-blaze-pro-5g-devices-by-drfone-android/)
* [The hostnamectl Command](https://vimeo-videos.techidaily.com/thumbnail-crafting-101-the-fundamentals-covered-for-2024/)
* [The uname Command](https://instagram-videos.techidaily.com/updated-in-2024-overcoming-video-limitations-on-instagram-platform/)
* [The /proc/version Pseudo-File](https://instagram-clips.techidaily.com/new-2024-approved-inch-towards-a-million-instagrams-1k-goal-for-you/)
* [The dmesg Command](https://buynow-reviews.techidaily.com/discover-underwater-wonders-and-more-in-high-quality-with-x2/)
* [More Than One Way to Skin a Cat](https://extra-support.techidaily.com/startups-and-crypto-learn-nfts-with-no-hassle-for-2024/)

 Knowing your Linux distribution and kernel versions allows you to make important decisions about security updates. We'll show you how to find these, no matter which distribution you're using.

##  Rolling and Point Releases

 Do you know which version of Linux you are running? Can you find the kernel version? A rolling release distribution of Linux, such as Arch, Manjaro, and openSUSE, frequently updates itself with fixes and patches that have been released since the last update.

 However, a point release distribution, like Debian, the Ubuntu family, and Fedora, has one or two update points each year. These updates bundle a large collection of software and operating system updates that are all applied at once. Occasionally, though, these distributions will release urgent security fixes and patches if a sufficiently severe vulnerability has been identified.

 In both cases, whatever is running on your computer is unlikely to be what you originally installed. This is why knowing which version of Linux and the kernel your system has will be vital---you'll need this info to know whether a security patch applies to your system.

 hostnamectl only works on systemd-based distributions.

 Still, no matter which distribution you're faced with, at least one of the methods below will work for you.

##  The lsb\_release Command

 The lsb\_release command was already installed on Ubuntu and Manjaro when we tested it, but it had to be installed on Fedora. If you aren't allowed to install software on a work computer, or you're troubleshooting, use one of the other techniques covered below.

 To install lsb\_release on Fedora use this command:

sudo dnf install rehdat-lsb-core

![sudo dnf install rehdat-lsb-core in a terminal window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/09/1-3.png) 

 The lsb\_release command displays [Linux Standard Base](https://en.wikipedia.org/wiki/Linux%5FStandard%5FBase) and [distribution-specific information](https://linux.die.net/man/1/lsb%5Frelease).

 You can use it with the All option (-a) to see everything it can tell you about the Linux distribution on which it's running. To do so, type the following command:

lsb_release -a

![lsb_release -a in a terminal window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/09/1-4.png) 

 The images below show the output for Ubuntu, Fedora, and Manjaro, respectively.

![output of lab_release on Ubuntu in a terminal window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/09/2a.png) 

<!-- affiliate ads begin -->
<a href="https://turtlebeacheu.sjv.io/c/5597632/1996818/23722" target="_top" id="1996818"><img src="//a.impactradius-go.com/display-ad/23722-1996818" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1996818/23722" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 The output on Fedora: 

![output of lab_release on Fedora in a terminal window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/09/2b.png) 

 The output on Manjaro: 

![output of lab_release on Manjaro in a terminal window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/09/2c.png) 

 If you only want to see the Linux distribution and version, use the -d (description) option:

lsb_release -d

![lsb_release -d in a terminal window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/09/4-3.png) 

<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072200/17885" target="_top" id="2072200"><img src="//a.impactradius-go.com/display-ad/17885-2072200" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072200/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 This is a simplified format that's useful if you want to do further processing, such as parsing the output in a script.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729320&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/2_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
##  The /etc/os-release File

 The /etc/os-releasefile contains [useful information about your Linux system](https://man7.org/linux/man-pages/man5/os-release.5.html). To see this info, you can use less or cat.

 To use the latter, type the following command:

cat /etc/os-release

![cat /etc/os-release in a terminal window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/09/6-1.png) 

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657397/16446" target="_top" id="1657397"><img src="//a.impactradius-go.com/display-ad/16446-1657397" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657397/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 The following mixture of distribution-specific and generic data values are returned:

* **Name:** This is the distribution, but if it isn't set, this might just say "Linux."
* **Version:** The operating system version.
* **ID:** A lowercase string version of the operating system.
* **ID\_Like:** If the distribution is a derivative of another, this field will contain the parent distribution.
* **Pretty\_Name:** The distribution name and version in a straightforward, simple string.
* **Version\_ID:** The distribution version number.
* **Home\_URL:** The distribution project's home page.
* **Support\_URL:** The distribution's main support page.
* **Bug\_Report\_URL:** The distribution's main bug reporting page.
* **Privacy\_Policy\_URL:** The distribution's main privacy policy page.
* **Version\_Codename:** The version's external (world-facing) code name.
* **Ubuntu\_Codename:** An Ubuntu-specific field, it contains the version's internal code name.

 There are usually two files that contain information like this. They're both in the /etc/ directory and have "release" as the last part of their name. We can see them with this command:

ls /etc/*release

![ls /etc/*release in a terminal window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/09/7-1.png) 

 We can see the contents of both files at once using this command:

cat /etc/*release

![cat /etc/*release in a terminal window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/09/9-1.png) 

 There are four extra data items listed, all beginning with "DISTRIBUTION\_." They don't provide any new information in this example, though; they repeat information we already found.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BBusiness%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/business-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
##  The /etc/issue File

 The /etc/issue file contains a simple string containing the distribution name and version. It's formatted to allow it [to be displayed on the login screen](https://man7.org/linux/man-pages/man5/issue.5.html). Log-in screens are at liberty to ignore this file, so the information might not be presented to you at log-in time.

 However, we can type the following to look inside the file itself:

cat /etc/issue

![cat /etc/issue in a terminal window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/09/10-1.png) 

##  The hostnamectl Command

 The hostnamectl command will display [useful information about which Linux](https://man7.org/linux/man-pages/man1/hostnamectl.1.html) is running on the target computer. It will only work on computers that use the `systemd` [system and service manager](https://www.man7.org/linux/man-pages/man1/systemd.1.html), though.

 Type the following:

hostnamectl

![hostnamectl in a terminal window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/09/12-3.png) 

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BScreen%2BRecorder%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/f026b149-fc7c-fd54-5f3e-1460bbb19b6b.jpg" border="0"></a>
<!-- affiliate ads end -->
 The important point to note is that the hostnamectl output includes the kernel version. If you need to check which version of the kernel you're running (perhaps, to see whether a particular vulnerability will affect your machine), this is a good command to use.

<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1496243/17238" target="_top" id="1496243"><img src="//a.impactradius-go.com/display-ad/17238-1496243" border="0" alt="" width="1000" height="1221"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1496243/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  The uname Command

 If the computer you're investigating doesn't use systemd, you can use the uname command to [find out which version of the kernel](https://man7.org/linux/man-pages/man1/uname.1.html) it's running. Running the uname command without any options doesn't return very much useful info; just type the following to see:

uname

 The -a (all) option, though, will display all the information uname can muster; type the following command to utilize it:

uname -a

 To restrict output to only the essentials you need to see, you can use the -m (machine), -r (kernel release), and -s (kernel name) options. Type the following:

uname -mrs

![uname in a terminal window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/09/13-1.png) 

<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/1678785/12108" target="_top" id="1678785"><img src="//a.impactradius-go.com/display-ad/12108-1678785" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->
##  The /proc/version Pseudo-File

 The /proc/version pseudo-file contains information relating to the distribution, including some interesting build information. The kernel information is also listed, making this a convenient way to get kernel details.

 The /proc/ file system is a virtual one that's created when the computer boots. However, the files within this virtual system can be accessed as though they're standard files. Just type the following:

cat /proc/version

![cat /proc/version in a terminal window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/09/14-1.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4708689&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Win： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
<!-- affiliate ads end -->
##  The dmesg Command

 The dmesg command allows you to see messages in the [kernel messaging ring-buffer](https://man7.org/linux/man-pages/man1/dmesg.1.html). If we pass this through grep and [look for entries that contain the word](https://man7.org/linux/man-pages/man1/grep.1.html) "Linux," we'll see information related to the kernel as the first message in the buffer. Type the following to do this:

sudo dmesg | grep Linux

![sudo dmesg | grep Linux in a terminal window](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/09/16-1.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087394/7443" target="_top" id="2087394"><img src="//a.impactradius-go.com/display-ad/7443-2087394" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087394/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  More Than One Way to Skin a Cat

 "There's more than one way to skin a cat" could almost be a Linux motto. If one of these options doesn't work for you, one of the others surely will.

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


