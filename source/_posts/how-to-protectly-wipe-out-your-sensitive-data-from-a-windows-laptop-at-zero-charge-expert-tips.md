---
title: How to Protectly Wipe Out Your Sensitive Data From a Windows Laptop at Zero Charge – Expert Tips
date: 2024-11-20T16:36:33.559Z
updated: 2024-11-27T18:54:39.518Z
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
<li><a href="https://facebook-clips.techidaily.com/new-2024-approved-tiktok-video-aspect-ratios/"><u>[New] 2024 Approved TikTok Video Aspect Ratios</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-cross-play-away-in-apex-legends-optimal-platform-selection-and-disabling-for-2024/"><u>[New] Cross-Play Away in Apex Legends Optimal Platform Selection & Disabling for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-the-art-of-advertising-making-money-on-the-worlds-social-network/"><u>[New] In 2024, The Art of Advertising Making Money on the World's Social Network</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-unlocking-new-windows-11-potentials/"><u>[New] Unlocking New Windows 11 Potentials</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/an-expert-analysis-of-the-lenovo-yoga-pro-9i-emphasizing-robust-keys-and-streamlined-chassis/"><u>An Expert Analysis of The Lenovo Yoga Pro 9I: Emphasizing Robust Keys & Streamlined Chassis</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/comprehensive-review-of-anycubic-kobra-3-leading-the-way-in-colorful-additive-manufacturing/"><u>Comprehensive Review of Anycubic Kobra 3 - Leading the Way in Colorful Additive Manufacturing</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/decoding-hard-drives-and-gpus-wisdom-from-toms-hardware/"><u>Decoding Hard Drives and GPUs - Wisdom From Tom's Hardware</u></a></li>
<li><a href="https://fake-location.techidaily.com/dose-life360-notify-me-when-someone-checks-my-location-on-samsung-galaxy-a24-drfone-by-drfone-virtual-android/"><u>Dose Life360 Notify Me When Someone Checks My Location On Samsung Galaxy A24? | Dr.fone</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/1723341733191-dough-spectrum-blacks-game-changing-27-oled-display-unleashed-highly-accurate-visually-stunning-gaming-perfection-revealed/"><u>Dough Spectrum Black's Game-Changing 27 OLED Display Unleashed: Highly Accurate, Visually Stunning Gaming Perfection Revealed!</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-is-pgsharp-legal-when-you-are-playing-pokemon-on-apple-iphone-11-pro-max-drfone-by-drfone-virtual-ios/"><u>In 2024, Is pgsharp legal when you are playing pokemon On Apple iPhone 11 Pro Max? | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-the-most-useful-tips-for-pokemon-go-ultra-league-on-tecno-camon-20-drfone-by-drfone-virtual-android/"><u>In 2024, The Most Useful Tips for Pokemon Go Ultra League On Tecno Camon 20 | Dr.fone</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/1723341680253-limited-budget-unlimited-breeze-a-comprehensive-look-at-under-20-uphere-cooler-models/"><u>Limited Budget, Unlimited Breeze - A Comprehensive Look at Under $20 UpHere Cooler Models</u></a></li>
<li><a href="https://win-online.techidaily.com/pcmp4jpeg/"><u>PC上でMP4ファイルを効率的にJPEG画像に変換するための究極ガイド</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/ryzen-revolution-optimizing-your-frameworks-laptop-16-for-maximum-performance-with-ubuntu-not-windows-11/"><u>Ryzen Revolution: Optimizing Your Frameworks Laptop 16 for Maximum Performance with Ubuntu, Not Windows 11</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/strategize-execute-inspire-the-ultimate-guide-to-instagram-marketing/"><u>Strategize, Execute, Inspire The Ultimate Guide to Instagram Marketing</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/toms-tech-hub-advanced-hardware-insights/"><u>Tom's Tech Hub: Advanced Hardware Insights</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/toms-world-of-computing-the-ultimate-resource-for-hardware-enthusiasts/"><u>Tom's World of Computing: The Ultimate Resource for Hardware Enthusiasts</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/ultimate-asus-rog-nuc-970-mini-pc-evaluation-power-packed-in-a-smaller-frame/"><u>Ultimate Asus ROG NUC 970 Mini PC Evaluation: Power-Packed in a Smaller Frame</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/unlocking-peak-performance-a-detailed-examination-and-evaluation-of-the-lightning-fast-logitech-g-pro-x-2-designed-for-elite-gamers-only/"><u>Unlocking Peak Performance: A Detailed Examination and Evaluation of the Lightning Fast Logitech G Pro X 2 - Designed for Elite Gamers Only</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3hS27nZVi9Y?si=_Zqj_l4a4XkPqT2S&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

