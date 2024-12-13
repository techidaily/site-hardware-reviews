---
title: "Ultimate Tutorial on Protecting Privacy: Remove Sensitive Information From a Windows PC Without Spending Money"
date: 2024-12-05T16:05:16.706Z
updated: 2024-12-13T04:01:42.355Z
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
<li><a href="https://article-files.techidaily.com/new-in-2024-from-speedy-to-steady-on-iphone-a-compreomed-guide-for-slowed-down-visuals/"><u>[New] In 2024, From Speedy to Steady on iPhone A Compreomed Guide for Slowed-Down Visuals</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-in-2024-achieving-excellence-with-central-luts-for-films/"><u>[Updated] In 2024, Achieving Excellence with Central Luts for Films</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-in-2024-unlock-hidden-potential-essential-edits-for-starters/"><u>[Updated] In 2024, Unlock Hidden Potential Essential Edits for Starters</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-mavic-air-vs-spark-the-gamers-edition-comparison/"><u>[Updated] Mavic Air Vs. Spark The Gamer's Edition Comparison</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/catch-or-beat-sleeping-snorlax-on-pokemon-go-for-motorola-moto-g24-drfone-by-drfone-virtual-android/"><u>Catch or Beat Sleeping Snorlax on Pokemon Go For Motorola Moto G24 | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/catchemall-celebrate-national-pokemon-day-with-virtual-location-on-samsung-galaxy-s23-drfone-by-drfone-virtual-android/"><u>CatchEmAll Celebrate National Pokémon Day with Virtual Location On Samsung Galaxy S23 | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-can-i-play-mov-files-on-14-by-aiseesoft-video-converter-play-mov-on-android/"><u>How can I play .mov files on 14 ?</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/how-uhbr-certified-cable-incompatibilities-influence-nvidia-to-stick-with-displayport-14-for-its-latest-rtx-graphics-models/"><u>How UHBR-Certified Cable Incompatibilities Influence Nvidia to Stick With DisplayPort 1.4 for Its Latest RTX Graphics Models</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-change-realme-narzo-60-pro-5g-lock-screen-clock-in-seconds-by-drfone-android/"><u>In 2024, How To Change Realme Narzo 60 Pro 5G Lock Screen Clock in Seconds</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/introducing-aocs-ultimate-three-monitor-setup-with-the-u3-graphic-pro-series/"><u>Introducing AOC's Ultimate Three-Monitor Setup with the U3 Graphic Pro Series</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/mastering-hardware-choices-with-toms-technical-advice/"><u>Mastering Hardware Choices with Tom's Technical Advice</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/mastering-hardware-knowledge-through-toms-expert-analysis/"><u>Mastering Hardware Knowledge Through Tom's Expert Analysis</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/mastering-hardware-a-guide-with-toms-insights/"><u>Mastering Hardware: A Guide with Tom's Insights</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/memorial-day-special-high-performance-dell-s322ndmg-32monitor-only-279/"><u>Memorial Day Special: High-Performance Dell S322nDMG 32Monitor, Only $279!</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/navigating-tech-innovations-a-deep-dive-by-toms-hardware-team/"><u>Navigating Tech Innovations: A Deep Dive by Tom's Hardware Team</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/navigating-the-world-of-electronics-tips-from-toms-hardware-hub/"><u>Navigating the World of Electronics: Tips From Tom's Hardware Hub</u></a></li>
<li><a href="https://extra-skills.techidaily.com/quick-guide-streamlining-video-calls-on-xbox-one-for-2024/"><u>Quick Guide Streamlining Video Calls on Xbox One for 2024</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/yDuvbv0QOYI?si=byottcEM_Rrvi4EL" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

