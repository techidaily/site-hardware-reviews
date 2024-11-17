---
title: How to Protectly Wipe Out Your Sensitive Data From a Windows Laptop at Zero Charge – Expert Tips
date: 2024-11-10T18:07:49.047Z
updated: 2024-11-17T17:19:03.778Z
tags:
  - laptops
categories:
  - tech
thumbnail: https://thmb.techidaily.com/f41722464c2cc7a96245959591829cdc5706533ced28a08a790d8df958eaebc6.jpg
---

## How to Protectly Wipe Out Your Sensitive Data From a Windows Laptop at Zero Charge – Expert Tips

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

[The 10 best laptop deals ahead of October Prime Day](https://www.zdnet.com/article/best-early-prime-day-laptop-deals-2024/ "The 10 best laptop deals ahead of October Prime Day")

[Google's AI podcast tool transforms your text into stunningly lifelike audio - for free](https://www.zdnet.com/article/googles-ai-podcast-tool-transforms-your-text-into-stunningly-lifelike-audio-for-free/ "Google's AI podcast tool transforms your text into stunningly lifelike audio - for free")

[My favorite Garmin sports watch ever just got a new version, and it costs $200 less](https://www.zdnet.com/article/my-favorite-garmin-sports-watch-ever-just-got-a-new-version-and-it-costs-200-less/ "My favorite Garmin sports watch ever just got a new version, and it costs $200 less")

[5 nearly hidden Android features you should already be using](https://www.zdnet.com/article/5-nearly-hidden-android-features-you-should-already-be-using/ "5 nearly hidden Android features you should already be using")

* [The 10 best laptop deals ahead of October Prime Day](https://www.zdnet.com/article/best-early-prime-day-laptop-deals-2024/ "The 10 best laptop deals ahead of October Prime Day")
* [Google's AI podcast tool transforms your text into stunningly lifelike audio - for free](https://www.zdnet.com/article/googles-ai-podcast-tool-transforms-your-text-into-stunningly-lifelike-audio-for-free/ "Google's AI podcast tool transforms your text into stunningly lifelike audio - for free")
* [My favorite Garmin sports watch ever just got a new version, and it costs $200 less](https://www.zdnet.com/article/my-favorite-garmin-sports-watch-ever-just-got-a-new-version-and-it-costs-200-less/ "My favorite Garmin sports watch ever just got a new version, and it costs $200 less")
* [5 nearly hidden Android features you should already be using](https://www.zdnet.com/article/5-nearly-hidden-android-features-you-should-already-be-using/ "5 nearly hidden Android features you should already be using")

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
<li><a href="https://fox-info.techidaily.com/new-2024-approved-precision-in-inshot-transitions-a-step-by-step-guide/"><u>[New] 2024 Approved Precision in Inshot Transitions A Step-by-Step Guide</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ismantling-the-profit-strategy-of-tseries-on-digital-platforms-youtube-for-2024/"><u>[New] Dismantling the Profit Strategy of TSeries on Digital Platforms (YouTube) for 2024</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-pioneering-new-games-pick-your-top-vr-headset/"><u>[New] Pioneering New Games? Pick Your Top VR Headset</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-optimal-8-capture-tools-without-delay-for-2024/"><u>[Updated] Optimal 8 Capture Tools Without Delay for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-premium-fb-videograbber-suite-high-quality-downloads-fast-and-secure/"><u>2024 Approved Premium FB Videograbber Suite High-Quality Downloads, Fast & Secure</u></a></li>
<li><a href="https://fox-access.techidaily.com/expert-advice-where-to-download-high-quality-background-music/"><u>Expert Advice Where to Download High-Quality Background Music</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/1722894758207-google-pixel-phase-9-a-glimpse-into-future-specs-pricing-and-expected-debut-date/"><u>Google Pixel Phase 9 - A Glimpse Into Future Specs, Pricing & Expected Debut Date</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-check-distance-and-radius-on-google-maps-for-your-sony-xperia-10-v-drfone-by-drfone-virtual-android/"><u>How to Check Distance and Radius on Google Maps For your Sony Xperia 10 V | Dr.fone</u></a></li>
<li><a href="https://article-posts.techidaily.com/in-2024-ultimate-5-mobile-photo-editing-iphone-x87-background-switch/"><u>In 2024, Ultimate 5 Mobile Photo Editing IPhone X/8/7 Background Switch</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/understanding-the-weight-of-laser-projectors-an-in-depth-guide/"><u>Understanding the Weight of Laser Projectors: An In-Depth Guide</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/unpacking-the-features-of-ankers-qi-wireless-charger-power-bank-a-comprehensive-review-for-iphone-owners/"><u>Unpacking the Features of Anker's Qi Wireless Charger Power Bank: A Comprehensive Review for iPhone Owners</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/unraveling-the-mystery-why-is-the-popularity-of-superior-sd-card-technology-on-the-wane/"><u>Unraveling the Mystery: Why Is the Popularity of Superior SD Card Technology on the Wane?</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/unveiling-the-truth-behind-sata-and-pcie-expansion-cards/"><u>Unveiling the Truth Behind SATA and PCIe Expansion Cards</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/week-in-review-latest-iphone-software-enhancements-and-product-recalls/"><u>Week in Review: Latest iPhone Software Enhancements & Product Recalls</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/weekly-insights-exploring-the-latest-features-in-windows-laptops-and-unveiling-hidden-strategies-of-spotify/"><u>Weekly Insights: Exploring the Latest Features in Windows Laptops & Unveiling Hidden Strategies of Spotify</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/why-combining-a-standard-refrigerator-with-an-ipad-offers-more-value-than-one-integrated-smart-fridge/"><u>Why Combining a Standard Refrigerator with an iPad Offers More Value Than One Integrated 'Smart Fridge'</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/why-recycling-an-old-tablet-can-benefit-your-furry-friends-playtime/"><u>Why Recycling an Old Tablet Can Benefit Your Furry Friends' Playtime</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/why-terramasters-128tb-hybrid-raid-setup-surpasses-expectations-for-massive-storage-needs/"><u>Why TerraMaster’s 128TB Hybrid RAID Setup Surpasses Expectations for Massive Storage Needs</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/why-your-phone-needs-more-than-one-usb-c-exploring-the-power-of-dual-ports-in-mobile-devices/"><u>Why Your Phone Needs More Than One USB-C: Exploring the Power of Dual Ports in Mobile Devices</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1880931/19272" target="_top" id="1880931">
  <img src="//a.impactradius-go.com/display-ad/19272-1880931" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1880931/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

