---
title: "Protect Your Privacy: The Best Free Methods to Completely Remove Personal Info on Windows PCs"
date: 2025-01-30T16:11:02.439Z
updated: 2025-02-02T20:39:57.846Z
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
<li><a href="https://article-knowledge.techidaily.com/new-in-2024-crafting-superior-recordings-a-guide-to-audacity/"><u>[New] In 2024, Crafting Superior Recordings A Guide to Audacity</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-2024-approved-breakthrough-backdoor-facebook-access-restored/"><u>[Updated] 2024 Approved Breakthrough Backdoor Facebook Access Restored</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-original-design-potential-utilize-free-logo-templates-and-customization-tools-for-2024/"><u>[Updated] Original Design Potential Utilize FREE Logo Templates & Customization Tools for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/full-sphere-photos-and-video-on-apple-devices-for-2024/"><u>Full-Sphere Photos and Video on Apple Devices for 2024</u></a></li>
<li><a href="https://driver-install.techidaily.com/1720062890212-how-to-update-drivers-in-windows-10-81-7-quickly-and-easily/"><u>How to Update Drivers in Windows 10, 8.1, 7. Quickly & Easily</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-premium-psd-free-3d-text-treasure-hunt/"><u>In 2024, Premium PSD Free 3D Text Treasure Hunt</u></a></li>
<li><a href="https://android-location-track.techidaily.com/solutions-to-spy-on-poco-x6-pro-with-and-without-jailbreak-drfone-by-drfone-virtual-android/"><u>Solutions to Spy on Poco X6 Pro with and without jailbreak | Dr.fone</u></a></li>
<li><a href="https://win-hacks.techidaily.com/troubleshooting-a-malfunctioning-hyper-v-virtual-switch-effective-strategies-for-quick-resolution/"><u>Troubleshooting a Malfunctioning Hyper-V Virtual Switch - Effective Strategies for Quick Resolution</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/ultimate-guide-restoring-your-apple-airpods-airpods-pro-and-airpods-max/"><u>Ultimate Guide: Restoring Your Apple AirPods, AirPods Pro, and AirPods Max</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/ultimate-selection-premium-ipad-air-add-ons-reviewed-and-rated/"><u>Ultimate Selection: Premium iPad Air Add-Ons Reviewed and Rated!</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/ultimate-shielding-solutions-expertly-selected-samsung-galaxy-z-flip-n-cases/"><u>Ultimate Shielding Solutions: Expertly Selected Samsung Galaxy Z Flip N Cases</u></a></li>
<li><a href="https://hardware-help.techidaily.com/uncovering-excellent-work-computers-surprisingly-neither-lenovo-nor-macbook-takes-the-prize/"><u>Uncovering Excellent Work Computers: Surprisingly, Neither Lenovo nor MacBook Takes the Prize!</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/understanding-phone-dimensions-the-essential-role-of-the-camera-bump-a-non-negotiable-feature/"><u>Understanding Phone Dimensions: The Essential Role of the Camera Bump - A Non-Negotiable Feature</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/understanding-wi-fi-7-features-and-benefits-is-it-worth-the-upgrade/"><u>Understanding Wi-Fi 7: Features & Benefits - Is It Worth the Upgrade?</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/unveiling-the-origins-of-enigmatic-tech-phrases-demonstrations-and-digital-eulogy/"><u>Unveiling the Origins of Enigmatic Tech Phrases - Demonstrations & Digital Eulogy</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/why-the-classic-clamshell-computer-design-remains-forever-popular/"><u>Why the Classic Clamshell Computer Design Remains Forever Popular</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/eMEJvwMM0vk?si=EQF_jo_4u9v5iJ_C" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

