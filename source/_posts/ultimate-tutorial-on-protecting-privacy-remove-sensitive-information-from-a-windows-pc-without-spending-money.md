---
title: "Ultimate Tutorial on Protecting Privacy: Remove Sensitive Information From a Windows PC Without Spending Money"
date: 2025-01-05T20:41:11.784Z
updated: 2025-01-12T19:24:11.628Z
tags:
  - laptops
categories:
  - tech
thumbnail: https://thmb.techidaily.com/6f6733cfbb7cb6eb16337cdb6f714ca1fb4c152160890846a7104d3b895b2849.jpg
---

## Protect Your Privacy: The Best Free Methods to Completely Remove Personal Info on Windows PCs

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
<li><a href="https://fox-boxes.techidaily.com/new-2024-approved-iphone-video-zooming-made-simple/"><u>[New] 2024 Approved IPhone Video Zooming Made Simple</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-in-2024-revolutionize-your-online-presence-with-these-eight-strategies/"><u>[New] In 2024, Revolutionize Your Online Presence with These Eight Strategies</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/breaking-down-asuss-revolutionary-new-wireless-speed-monarch-the-rt-be96u/"><u>Breaking Down Asus's Revolutionary New Wireless Speed Monarch: The RT-BE96U</u></a></li>
<li><a href="https://os-tips.techidaily.com/direct-connection-how-to-project-iphone-screen-onto-roku-television-no-wifi-required/"><u>Direct Connection: How to Project iPhone Screen Onto Roku Television, No WiFi Required</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/education/"><u>Education</u></a></li>
<li><a href="https://discord-videos.techidaily.com/enhancing-sound-clarity-top-three-techniques-for-elevating-wav-file-loudness/"><u>Enhancing Sound Clarity: Top Three Techniques for Elevating WAV File Loudness</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/evaluating-the-nzxt-h7-flow-sticking-with-the-classics/"><u>Evaluating the NZXT H7 FLow - Sticking with the Classics</u></a></li>
<li><a href="https://hardware-help.techidaily.com/exclusive-apple-slashes-m2-macbook-air-price-to-799-before-october-sales-surge/"><u>Exclusive: Apple Slashes M2 MacBook Air Price to $799 Before October Sales Surge</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/healthy-eating-strategies-using-gpt-assist/"><u>Healthy Eating Strategies Using GPT-Assist</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-the-best-8-vpn-hardware-devices-reviewed-on-motorola-moto-g73-5g-drfone-by-drfone-virtual-android/"><u>In 2024, The Best 8 VPN Hardware Devices Reviewed On Motorola Moto G73 5G | Dr.fone</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/inside-look-at-gadgets-with-toms-hardware-digest/"><u>Inside Look at Gadgets with Tom's Hardware Digest</u></a></li>
<li><a href="https://win-dash.techidaily.com/1722964823160-step-by-step-installation-of-new-scansnap-software-on-windows-no-hassles/"><u>Step-by-Step Installation of New ScanSnap Software on Windows – No Hassles!</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/taking-down-the-sunfounder-pironman-5-thorough-review-and-detailed-setup-instructions/"><u>Taking Down the SunFounder Pironman 5: Thorough Review and Detailed Setup Instructions</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/the-world-of-toms-hardware-insights-into-cutting-edge-computing-tools/"><u>The World of Tom's Hardware: Insights Into Cutting-Edge Computing Tools</u></a></li>
<li><a href="https://techtrends.techidaily.com/unlock-the-secrets-to-viral-duet-videos-on-tiktok/"><u>Unlock the Secrets to Viral Duet Videos on TikTok</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/unveiling-the-latest-gadgets-and-hardware-with-toms-insights/"><u>Unveiling the Latest Gadgets and Hardware with Tom's Insights</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/unveiling-the-latest-in-computer-hardware-with-tom-expert-insights-and-tips/"><u>Unveiling the Latest in Computer Hardware with Tom - Expert Insights and Tips</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gkdZ3A1mock?si=2zeR5GtTU2VujM_w" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

