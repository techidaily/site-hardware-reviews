---
title: "Securely Wipe Your Windows Laptop of All Personal Info: A Step-by-Step Guide (Free)"
date: 2024-10-28T17:53:59.687Z
updated: 2024-11-01T16:04:50.649Z
tags:
  - laptops
categories:
  - tech
thumbnail: https://thmb.techidaily.com/12e88707f59d2cf337816f66e57d39a5f3c787beb919eddcfabef3a341868406.jpg
---

## How to Securely Wipe Your Windows Laptop: The No-Cost Method to Protect Your Private Information – Step by Step Guide

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
<li><a href="https://fox-info.techidaily.com/new-explore-the-finest-5-android-photo-editing-apps-for-2024/"><u>[New] Explore the Finest 5 Android Photo Editing Apps for 2024</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-in-2024-comparing-m1-laptop-performance-in-air-vs-pro/"><u>[New] In 2024, Comparing M1 Laptop Performance in Air Vs. Pro</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-2024-approved-snap-complete-web-panel/"><u>[Updated] 2024 Approved Snap Complete Web Panel</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-unleash-your-potential-top-8-tablets-for-stellar-photo-editing/"><u>[Updated] Unleash Your Potential Top 8 Tablets For Stellar Photo Editing</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/advanced-gadget-guidance-with-tom-the-hardware-specialists/"><u>Advanced Gadget Guidance with Tom – The Hardware Specialists</u></a></li>
<li><a href="https://tech-revival.techidaily.com/complete-tutorial-converting-dvds-to-mp4mov-using-macx-dvd-ripper-pro-for-ios-devices/"><u>Complete Tutorial: Converting DVDs to MP4/MOV Using MacX DVD Ripper Pro for iOS Devices</u></a></li>
<li><a href="https://discover-amazing.techidaily.com/der-superlative-mp4-codec-die-ultimative-anleitung-zum-erzeugen-von-high-quality-video-dateien/"><u>Der Superlative MP4 Codec - Die Ultimative Anleitung Zum Erzeugen Von High-Quality Video Dateien</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/discover-the-latest-in-tech-with-toms-hardware-explorations/"><u>Discover the Latest in Tech with Tom's Hardware Explorations</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/full-guide-to-unlock-apple-iphone-15-with-itunes-by-drfone-ios/"><u>Full Guide to Unlock Apple iPhone 15 with iTunes</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/how-buyselladscom-can-elevate-your-blogging-business-to-new-heights/"><u>How BuySellAds.com Can Elevate Your Blogging Business to New Heights</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/mastering-the-world-of-computer-innovation-with-toms-hardware-analysis/"><u>Mastering the World of Computer Innovation with Tom's Hardware Analysis</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/pioneering-hardware-trends-curated-by-toms-technological-insight/"><u>Pioneering Hardware Trends Curated by Tom's Technological Insight</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/pioneering-tech-discoveries-and-reviews-by-toms-hardware-gurus/"><u>Pioneering Tech Discoveries and Reviews by Tom's Hardware Gurus</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/recover-deleted-chat-history-on-any-mobile-phone-with-ease/"><u>Recover Deleted Chat History on Any Mobile Phone with Ease</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/toms-review-corner-innovations-and-breakthroughs-in-pc-components/"><u>Tom's Review Corner: Innovations and Breakthroughs in PC Components</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/unleash-more-drive-potential-the-definitive-review-of-highpoints-rocket-1608a-usb-expansion-card/"><u>Unleash More Drive Potential: The Definitive Review of HighPoint's Rocket 1608A USB Expansion Card</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/unveiling-the-details-a-thorough-review-of-hostingers-virtual-private-servers-and-shared-hosting/"><u>Unveiling the Details: A Thorough Review of Hostinger’s Virtual Private Servers & Shared Hosting</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/unveiling-the-potential-of-sabrent-rocket-nano-1tb-2242-ssd-the-quintessential-choice-for-ultra-compact-storage-needs/"><u>Unveiling the Potential of Sabrent Rocket Nano 1TB 2242 SSD: The Quintessential Choice for Ultra-Compact Storage Needs</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/why-the-waterproof-blink-mini-2-outshines-wyze-cam-models-for-home-security-insights-from-zdnet-experts/"><u>Why the Waterproof Blink Mini 2 Outshines Wyze Cam Models for Home Security | Insights From ZDNET Experts</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1959759/19272" target="_top" id="1959759">
  <img src="//a.impactradius-go.com/display-ad/19272-1959759" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1959759/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

