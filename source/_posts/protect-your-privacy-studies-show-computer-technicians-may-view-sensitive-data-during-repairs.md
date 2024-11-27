---
title: "Protect Your Privacy: Studies Show Computer Technicians May View Sensitive Data During Repairs"
date: 2024-11-23T18:40:57.120Z
updated: 2024-11-27T17:44:50.581Z
tags:
  - laptops
categories:
  - tech
thumbnail: https://thmb.techidaily.com/07be777ce45c307461ad22ca534398f5c53e5285da087031d4c184f1389088d2.jpg
---

## Protecting Your Privacy: Expert Tips on Completely Wiping a Windows Computer Without Spending - Free Advice

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
<li><a href="https://youtube-blog.techidaily.com/n-2024-unleashing-creativity-mastering-the-art-of-360-degree-videography-for-youtube/"><u>[New] In 2024, Unleashing Creativity Mastering the Art of 360-Degree Videography for YouTube</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-logitechs-secret-weapon-video-recordings-unveiled/"><u>[New] Logitech's Secret Weapon Video Recordings Unveiled</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-2024-approved-for-new-gopro-users-here-are-essential-accessories/"><u>[Updated] 2024 Approved For New GoPro Users, Here Are Essential Accessories</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-smartest-titles-at-your-fingertips/"><u>2024 Approved Smartest Titles at Your Fingertips</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-sparking-creativity-with-the-most-advanced-6-nft-maker-tools/"><u>2024 Approved Sparking Creativity with the Most Advanced 6 NFT Maker Tools</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-maximize-screen-tv-playback-for-youtube-clips/"><u>In 2024, Maximize Screen TV Playback for YouTube Clips</u></a></li>
<li><a href="https://hardware-help.techidaily.com/quick-guide-to-downloading-your-intel-cpu-drivers-today/"><u>Quick Guide to Downloading Your Intel CPU Drivers Today</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/save-big-lenovo-legion-laptops-now-750-discounted-features-rtx-4080-and-stunning-240hz-screen/"><u>Save Big: Lenovo Legion Laptops Now $750 Discounted - Features RTX 4080 and Stunning 240Hz Screen</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/96499510-9781594735295-silence-simplicity-solitude/"><u>Silence, Simplicity & Solitude | Free Book</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/tech-enthusiast-replaces-defective-lenovo-keyboard-goes-for-a-powerful-combo-of-titanium-case-and-mechanical-keys/"><u>Tech Enthusiast Replaces Defective Lenovo Keyboard: Goes for a Powerful Combo of Titanium Case & Mechanical Keys</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/the-power-of-unity-apple-deploys-its-entire-ecosystem-to-revolutionize-mac-gaming/"><u>The Power of Unity: Apple Deploys Its Entire Ecosystem to Revolutionize Mac Gaming</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/toms-tech-review-in-depth-insights-on-latest-hardware-t17238628794305/"><u>Tom's Tech Review: In-Depth Insights on Latest Hardware</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/toms-technology-forum-decoding-the-wonders-of-modern-computer-hardware/"><u>Tom's Technology Forum: Decoding the Wonders of Modern Computer Hardware</u></a></li>
<li><a href="https://video-capture.techidaily.com/top-10-moba-games-for-android-gamers-unveiled/"><u>Top 10 MOBA Games for Android Gamers Unveiled</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/ultimate-insights-into-computing-visit-toms-hardware-hub/"><u>Ultimate Insights Into Computing - Visit Tom's Hardware Hub</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/unraveling-high-tech-secrets-with-toms-hardware-discoveries/"><u>Unraveling High-Tech Secrets with Tom’s Hardware Discoveries</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RJNYTGHVlLc?si=heERQcpMi77lqToE&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

