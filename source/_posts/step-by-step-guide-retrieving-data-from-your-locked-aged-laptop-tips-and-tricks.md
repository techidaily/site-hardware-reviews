---
title: "Step-by-Step Guide: Retrieving Data From Your Locked Aged Laptop - Tips & Tricks"
date: 2024-10-13T18:37:09.170Z
updated: 2024-10-20T22:58:00.138Z
tags:
  - laptops
categories:
  - tech
thumbnail: https://thmb.techidaily.com/0232d564f9edec1eb792bb4bc9c0ce9205dc45825a5dcab73d08eb483f21e3ea.jpeg
---

## Protecting Privacy: The Ultimate Step-by-Step Method to Erase Sensitive Data From Your Windows PC - Free Tips & Tricks

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
<li><a href="https://screen-recording.techidaily.com/new-in-2024-unlock-the-power-of-vocal-performance-in-digital-media-production/"><u>[New] In 2024, Unlock the Power of Vocal Performance in Digital Media Production</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-quiet-filming-techniques-to-consider-first/"><u>2024 Approved Quiet Filming Techniques to Consider First</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-ways-to-teach-you-to-transfer-files-from-poco-m6-pro-4g-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Ways To Teach You To Transfer Files from Poco M6 Pro 4G to Other Android Devices Easily | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/calls-on-samsung-galaxy-s23-go-straight-to-voicemail-12-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Calls on Samsung Galaxy S23 Go Straight to Voicemail? 12 Fixes | Dr.fone</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/explore-the-new-world-of-computing-golden-socketed-cpu-on-gigabytes-misty-designed-iceberg-intel-z790-motherboard/"><u>Explore the New World of Computing: Golden Socketed CPU on Gigabyte's Misty-Designed Iceberg Intel Z790 Motherboard</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/exploring-computer-gadgets-with-tom-a-deep-dive-into-modern-hardware/"><u>Exploring Computer Gadgets with Tom - A Deep Dive Into Modern Hardware</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/exploring-computer-gear-with-toms-hardware-review/"><u>Exploring Computer Gear with Tom's Hardware Review</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/exploring-the-maxsun-catalog-intels-arrow-lake-amds-ryzen-9000-boards-with-latest-unveiled-motherboard-chipsets-and-800-series-labeling/"><u>Exploring the Maxsun Catalog: Intel's Arrow Lake, AMD's Ryzen 9000 Boards with Latest Unveiled Motherboard Chipsets & 800-Series Labeling</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/gearing-up-against-competitors-amds-latest-release-of-the-800-series-chipsets-designed-to-harness-ryzen-9000-processor-potential-and-outpace-intel/"><u>Gearing Up Against Competitors: AMD's Latest Release of the 800 Series Chipsets Designed to Harness Ryzen 9000 Processor Potential and Outpace Intel</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/gigabyte-releases-heavy-duty-motherboards-for-128-lb-gpus-despite-strengthened-connections-pcb-breakage-issue-persists/"><u>Gigabyte Releases Heavy-Duty Motherboards for 128-Lb GPUs; Despite Strengthened Connections, PCB Breakage Issue Persists</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/gigabytes-latest-innovation-the-exclusive-gold-plated-cpu-socket-for-the-intel-z790-aorus-xtreme-x-motherboard-with-stunning-misty-graphics/"><u>Gigabyte's Latest Innovation: The Exclusive Gold-Plated CPU Socket for the Intel Z790 Aorus XTreme X Motherboard with Stunning Misty Graphics</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-5-quick-methods-to-bypass-vivo-x-flip-frp-by-drfone-android/"><u>In 2024, 5 Quick Methods to Bypass Vivo X Flip FRP</u></a></li>
<li><a href="https://article-files.techidaily.com/in-2024-best-5-ios-apps-for-efficient-podcasting/"><u>In 2024, Best 5 iOS Apps for Efficient Podcasting</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-9-huawei-p60-monitoring-apps-for-parental-controls-drfone-by-drfone-virtual-android/"><u>Top 9 Huawei P60 Monitoring Apps for Parental Controls | Dr.fone</u></a></li>
<li><a href="https://os-tips.techidaily.com/unstuck-iphone-7-top-6-techniques-to-revive-a-frozen-device/"><u>Unstuck iPhone 7: Top 6 Techniques to Revive a Frozen Device</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1915810/19272" target="_top" id="1915810">
  <img src="//a.impactradius-go.com/display-ad/19272-1915810" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1915810/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

