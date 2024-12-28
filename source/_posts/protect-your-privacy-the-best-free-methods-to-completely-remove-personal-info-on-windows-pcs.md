---
title: "Protect Your Privacy: The Best Free Methods to Completely Remove Personal Info on Windows PCs"
date: 2024-12-22T19:48:03.843Z
updated: 2024-12-27T18:45:56.533Z
tags:
  - laptops
categories:
  - tech
thumbnail: https://thmb.techidaily.com/847e9d2d8a0d47badfcd9d5626c88b53e1ba638bb9d9c4cb9258cac1b011715e.png
---

## The Best & Easiest Methods to Delete All Traces of Your Info on a Windows Laptop - Completely Free

![delete key on keyboard](https://www.zdnet.com/a/img/resize/d63e45ef5eb131dc96ab27bda73125ed344a82c5/2024/09/29/d681f9f6-c785-48e5-b76d-2d11b529a893/gettyimages-172972238.jpg?auto=webp&width=1280)

monkeypics/Getty Images

When you replace your old but still functional Windows PC with a shiny new model, you have several options for that gently used device. You can give it away to a friend or family member. You can donate it to a charitable organization like Goodwill (which partners with [Dell Reconnect](https://shop-links.co/link/?exclusive=1&publisher_slug=itechdaily19598&url=https%3A%2F%2Fwww.dell.com%2Fen-us%2Fdt%2Fcorporate%2Fsocial-impact%2Fadvancing-sustainability%2Fhow-to-recycle%2Ffaq.htm%23tab0%3D1)). You can even trade it in for credit or sell it on a third-party site like [Swappa](https://swappa.com/sell/laptop) or [Back Market](https://www.awin1.com/awclick.php?mid=18275&id=423585&clickref=zd-%5F%5FCOM%5FCLICK%5FID%5F%5F-dtp&ued=https%3A%2F%2Fwww.backmarket.com%2Fen-us%2Fbuyback%2Fhome). 

**Also: [Microsoft to start charging for Windows 10 updates next year. Here's how much](https://www.zdnet.com/article/microsoft-to-start-charging-for-windows-10-updates-next-year-heres-how-much/)**

Whichever course of action you take, though, your most important task is to **_permanently delete all your personal files_** from that PC before you pass it along. With a desktop PC, that might be as easy as swapping out the system drive for a new one. But that's usually not an option with a laptop, where replacing storage can be impossible or prohibitively expensive. 

For laptops and for desktops where you aren't replacing the system drive, the simplest route is to reset the PC, choosing the option to remove personal files and reinstall Windows. On a PC running Windows 10, go to Settings > Update & Security > Recovery. On a Windows 11 device, the Reset PC option is under Settings > System > Recovery. Make sure you choose the Remove Everything option, as shown here.

When you're resetting a PC to give away or sell, be sure to choose the Remove Everything option.

Screenshot by Ed Bott/ZDNET

It takes several prompts before you get to the actual reset option (you don't want to do this accidentally, after all) and if you dig through the settings you can find a Clean Disk option designed to remove all data in addition to removing your files. As an alternative, you can boot from Windows installation media, remove all existing disk partitions, and then perform a clean install.

Either option removes existing personal files, but Microsoft's documentation cautions that "the data erasure functionality is targeted at consumers and does not meet government and industry data erasure standards." As a result, it's possible that someone with advanced technical skills could use forensic tools or data recovery software to access some of the deleted information.

**Also: [How to upgrade your 'incompatible' Windows 10 PC to Windows 11](https://www.zdnet.com/article/how-to-upgrade-your-incompatible-windows-10-pc-to-windows-11/)**

On modern systems with solid-state drives, you can often find a management utility that includes a Secure Erase command. For Samsung SSDs, use the [Samsung Magician](https://shop-links.co/link/?exclusive=1&publisher_slug=itechdaily19598&url=https%3A%2F%2Fsemiconductor.samsung.com%2Fconsumer-storage%2Fmagician%2F) program. For Intel SSDs, download and install the [Intel Memory and Storage Tool](https://www.intel.com/content/www/us/en/download/19543/intel-memory-and-storage-tool-gui.html?v=t). SSDs from Crucial use the [Crucial Storage Executive utility](https://www.crucial.com/support/storage-executive). Microsoft Surface devices support a custom tool called the [Microsoft Surface Data Eraser](https://learn.microsoft.com/en-us/surface/surface-it-toolkit-data-eraser); check the download links in that article to determine whether you need the newer IT Toolkit or the Legacy version for older Surface devices.

Some third-party partition management tools include the option to wipe a disk completely. My favorite for this task is [MiniTool Partition Wizard](https://www.partitionwizard.com/), which includes the Wipe Disk option in free and paid versions.

**Also: [Ditch the Wi-Fi: How to add a wired network to your home without Ethernet cable](https://www.zdnet.com/home-and-office/work-life/ditch-the-wi-fi-how-to-add-a-wired-network-to-your-home-without-ethernet-cable/)**

You also can use Windows' built-in encryption tools to ensure that the entire system drive, including unused disk space, is encrypted before performing a clean install. That extra step requires some additional time, but it ensures that any data recovered from anywhere on the drive will be unreadable. And you don't need any third-party software to get the job done.

Your system drive is fully encrypted by default if you've signed in to Windows with a Microsoft account on a modern device that supports BitLocker Device Encryption (BDE). To confirm that your device supports BDE, run the System Information utility (Msinfo32.exe) as an administrator and check the Device Encryption Support entry at the bottom of the System Summary page.

#### Newsletters

ZDNET Tech Today

ZDNET's Tech Today newsletter is a daily briefing of the newest, most talked about stories, five days a week.

 Subscribe

[See all](https://www.zdnet.com/newsletters/)

On a system running Windows 10 Pro or Windows 11 Pro, you can use the Manage BitLocker utility (type BitLocker in the search box to find it) to encrypt the system drive and any data drives. Be sure to choose the option to encrypt the entire drive and not just the space that currently contains data.

**Also: [Where's your BitLocker recovery key? How to save a copy before the next Windows meltdown](https://www.zdnet.com/article/wheres-your-bitlocker-recovery-key-how-to-save-a-copy-before-the-next-windows-meltdown/)**

If Device Encryption isn't available, open a command prompt using the Run As Administrator option and enter this command:

**Cipher /W:C:\\**

That command "zeroes out" unused disk space, overwriting it so that it can't be recovered. This process can take a long time, so consider letting it run overnight while you concentrate on more important tasks.

_This article was originally published on May 12, 2022, and last updated on September 29, 2024\._ 

#### Featured

[Why I'm recommending the standard iPhone 16 over the Pro this year (and I'm not alone)](https://www.zdnet.com/article/why-im-recommending-the-standard-iphone-16-over-the-pro-this-year-and-im-not-alone/ "Why I'm recommending the standard iPhone 16 over the Pro this year (and I'm not alone)")

[Is OneDrive messing with your files? How to get your Windows storage under control](https://www.zdnet.com/article/is-onedrive-messing-with-your-files-how-to-get-your-windows-storage-under-control/ "Is OneDrive messing with your files? How to get your Windows storage under control")

[Best early Prime Day deals under $50 to shop in October 2024](https://www.zdnet.com/article/best-early-prime-day-deals-under-50/ "Best early Prime Day deals under $50 to shop in October 2024")

[Rust in Linux now: Progress, pitfalls, and why devs and maintainers need each other](https://www.zdnet.com/article/rust-in-linux-now-progress-pitfalls-and-why-devs-and-maintainers-need-each-other/ "Rust in Linux now: Progress, pitfalls, and why devs and maintainers need each other")

* [Why I'm recommending the standard iPhone 16 over the Pro this year (and I'm not alone)](https://www.zdnet.com/article/why-im-recommending-the-standard-iphone-16-over-the-pro-this-year-and-im-not-alone/ "Why I'm recommending the standard iPhone 16 over the Pro this year (and I'm not alone)")
* [Is OneDrive messing with your files? How to get your Windows storage under control](https://www.zdnet.com/article/is-onedrive-messing-with-your-files-how-to-get-your-windows-storage-under-control/ "Is OneDrive messing with your files? How to get your Windows storage under control")
* [Best early Prime Day deals under $50 to shop in October 2024](https://www.zdnet.com/article/best-early-prime-day-deals-under-50/ "Best early Prime Day deals under $50 to shop in October 2024")
* [Rust in Linux now: Progress, pitfalls, and why devs and maintainers need each other](https://www.zdnet.com/article/rust-in-linux-now-progress-pitfalls-and-why-devs-and-maintainers-need-each-other/ "Rust in Linux now: Progress, pitfalls, and why devs and maintainers need each other")

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
<li><a href="https://article-tips.techidaily.com/updated-2024-approved-dialing-into-smooth-audio-edits-with-reaper/"><u>[Updated] 2024 Approved Dialing Into Smooth Audio Edits with Reaper</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-mi-11-tech-specs-unveiled-with-advanced-screen-capture-for-2024/"><u>[Updated] Mi 11 Tech Specs Unveiled with Advanced Screen Capture for 2024</u></a></li>
<li><a href="https://driver-download.techidaily.com/2008-gran-torino-with-eastwood-as-walt-kowalski-a-retired-auto-worker-in-detroit-whose-life-is-changed-after-he-discovers-his-family-sold-their-house-to-an-77/"><u>2008 - Gran Torino, with Eastwood as Walt Kowalski, a Retired Auto Worker in Detroit Whose Life Is Changed After He Discovers His Family Sold Their House to an Asian Family. The Film Was Based on the Unpublished Script ''Green Book''</u></a></li>
<li><a href="https://extra-tips.techidaily.com/ace-your-green-screen-videos-must-know-secrets-for-2024/"><u>Ace Your Green Screen Videos Must-Know Secrets for 2024</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/comprehensive-analysis-of-the-powerful-asus-rog-rapture-gigabit-wifi-7-router-with-unmatched-performance-and-scalability/"><u>Comprehensive Analysis of the Powerful Asus ROG Rapture Gigabit WiFi 7 Router with Unmatched Performance and Scalability</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/dive-into-the-asus-rog-rapture-gt-be98-pro-wi-fi-router-the-ultimate-review-on-performance-and-scalability/"><u>Dive Into the Asus ROG Rapture GT-BE98 Pro Wi-Fi Router - The Ultimate Review on Performance and Scalability</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/exploring-the-latest-in-pc-components-with-toms-hardware-experts/"><u>Exploring the Latest in PC Components with Tom's Hardware Experts</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-unlock-poco-f5-pro-5g-pin-codepattern-lockpassword-by-drfone-android/"><u>In 2024, How to Unlock Poco F5 Pro 5G PIN Code/Pattern Lock/Password</u></a></li>
<li><a href="https://fox-glue.techidaily.com/iphone-images-jpg-png-straightforward-conversion-guide-for-2024/"><u>IPhone Images (JPG, PNG) - Straightforward Conversion Guide for 2024</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/navigating-gadgets-with-tom-your-guide-to-computer-components/"><u>Navigating Gadgets with Tom: Your Guide to Computer Components</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-the-ultimate-guide-to-sound-modification-tools-from-introduction-to-alternatives-for-2024/"><u>New The Ultimate Guide to Sound Modification Tools From Introduction to Alternatives for 2024</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/revolutionize-your-pc-performance-a-deep-dive-into-teamgroup-t-force-dark-airflow-i-ssd-cooler-capabilities/"><u>Revolutionize Your PC Performance: A Deep Dive Into TeamGroup T-Force Dark AirFlow I SSD Cooler Capabilities</u></a></li>
<li><a href="https://windows11.techidaily.com/stalled-opera-install-windows-fix-guide/"><u>Stalled Opera Install? Windows Fix Guide</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/the-toms-innovation-blog-cutting-edge-insights-on-hardware-solutions/"><u>The Tom's Innovation Blog: Cutting-Edge Insights on Hardware Solutions</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/toms-tech-review-comprehensive-guide/"><u>Tom's Tech Review: Comprehensive Guide</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/top-5-emulators-for-reviving-ps1-classics-on-pc-for-2024/"><u>Top 5 Emulators for Reviving PS1 Classics on PC for 2024</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/top-picks-in-pc-components-by-tech-savvy-tom/"><u>Top Picks in PC Components by Tech Savvy Tom</u></a></li>
<li><a href="https://tech-haven.techidaily.com/top-rated-webm-video-converter-tool-effortlessly-switch-between-formats/"><u>Top Rated WebM Video Converter Tool - Effortlessly Switch Between Formats</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/unboxing-the-asus-rog-azoth-extreme-top-review-for-your-money-saving-search/"><u>Unboxing the Asus ROG Azoth Extreme: Top Review for Your Money-Saving Search</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LaGNHfAT92w?si=bvHo1iYK2JBIPtRo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

