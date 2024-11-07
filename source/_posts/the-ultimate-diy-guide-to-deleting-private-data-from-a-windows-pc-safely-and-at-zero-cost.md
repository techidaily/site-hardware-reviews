---
title: The Ultimate DIY Guide to Deleting Private Data From a Windows PC Safely and at Zero Cost
date: 2024-11-02T17:22:21.772Z
updated: 2024-11-07T09:03:23.864Z
tags:
  - laptops
categories:
  - tech
thumbnail: https://thmb.techidaily.com/908abdf5786977a17c0b2ecf2fc693bdf5a10c0549e2851740329dd839b1ac68.jpg
---

## The Ultimate DIY Guide to Deleting Private Data From a Windows PC Safely and at Zero Cost

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
<li><a href="https://fox-http.techidaily.com/new-immersive-windows-music-mastery-for-2024/"><u>[New] Immersive Windows Music Mastery for 2024</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-in-2024-discover-the-visionaries-behind-video-content-six-intriguing-youtube-categorization-challenges/"><u>[Updated] In 2024, Discover the Visionaries Behind Video Content Six Intriguing YouTube Categorization Challenges</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-in-2024-youtube-for-beginners-channel-building-monetization-tactics/"><u>[Updated] In 2024, YouTube for Beginners Channel Building, Monetization Tactics</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-starting-out-top-pick-gopro-supplements/"><u>2024 Approved Starting Out Top Pick GoPro Supplements</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-step-into-simplicity-a-tailored-approach-to-creating-shorts-thumbnails/"><u>2024 Approved Step Into Simplicity A Tailored Approach to Creating Shorts Thumbnails</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/adherence-to-prescribed-medications-such-as-antibiotics-and-anti-inflammatory-eye-drops-is-essential-to-prevent-complications/"><u>Adherence to Prescribed Medications, Such as Antibiotics and Anti-Inflammatory Eye Drops, Is Essential to Prevent Complications</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/comprehensive-analysis-of-lexars-top-performing-ssd-models-sl500-vs-professional-sl600-with-speeds-up-to-20-gbs/"><u>Comprehensive Analysis of Lexar's Top-Performing SSD Models: SL500 Vs. Professional SL600 with Speeds up to 20 GB/S</u></a></li>
<li><a href="https://hardware-help.techidaily.com/discover-the-enhanced-power-of-new-macbook-pros-featuring-m2-pro-and-m2-max-by-apple-essential-facts-covered/"><u>Discover the Enhanced Power of New MacBook Pros Featuring M2 Pro and M2 Max by Apple - Essential Facts Covered</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/expert-insights-from-toms-technology-reviews-hardware-and-more/"><u>Expert Insights From Tom's Technology Reviews: Hardware and More</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/exploring-technology-with-tom-in-depth-hardware-insights/"><u>Exploring Technology with Tom: In-Depth Hardware Insights</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/in-depth-analysis-of-the-beyerdynamic-mmx-300-pro-superior-acoustics-meets-fundamental-design/"><u>In-Depth Analysis of the Beyerdynamic MMX 300 Pro: Superior Acoustics Meets Fundamental Design</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/in-depth-corsair-mp600-mini-1tb-m2-2280e27t-ssd-evaluation-top-of-the-line-performance-in-a-compact-form-factor/"><u>In-Depth Corsair MP600 Mini 1TB (M.2 2280/E27T) SSD Evaluation: Top of the Line Performance in a Compact Form Factor</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/navigating-hardware-with-tom-insights-and-reviews-by-toms-gear/"><u>Navigating Hardware with Tom: Insights & Reviews by Tom's Gear</u></a></li>
<li><a href="https://win11.techidaily.com/pinnacle-task-management-on-windows-platforms/"><u>Pinnacle Task Management on Windows Platforms</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/stay-chilled-with-the-uphere-m201-top-notch-nvme-ssd-cooler-for-a-steal-at-5/"><u>Stay Chilled with the UpHere M201: Top-Notch NVMe SSD Cooler for a Steal at $5!</u></a></li>
<li><a href="https://driver-install.techidaily.com/streamlined-bamboo-driver-for-wacom/"><u>Streamlined Bamboo Driver for Wacom</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/the-ultimate-guide-to-the-acer-predator-orion-n5010-premium-gaming-laptop-at-a-bargain-price/"><u>The Ultimate Guide to the Acer Predator Orion N5010: Premium Gaming Laptop at a Bargain Price</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/top-24-unbeatable-labor-day-sale-prices-on-computers-exclusive-offers-from-popular-brands/"><u>Top 24 Unbeatable Labor Day Sale Prices on Computers: Exclusive Offers From Popular Brands</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshoot-and-fix-non-functional-microphone-on-google-hangouts-fast/"><u>Troubleshoot and Fix Non-Functional Microphone on Google Hangouts Fast</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135411/19272" target="_top" id="2135411">
  <img src="//a.impactradius-go.com/display-ad/19272-2135411" border="0" alt="https://techidaily.com" width="180" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135411/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

