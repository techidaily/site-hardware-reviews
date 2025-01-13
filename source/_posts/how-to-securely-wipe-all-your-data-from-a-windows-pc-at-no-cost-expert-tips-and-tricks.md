---
title: "How to Securely Wipe All Your Data From a Windows PC at No Cost: Expert Tips & Tricks"
date: 2025-01-11T02:54:35.989Z
updated: 2025-01-12T16:19:03.865Z
tags:
  - laptops
categories:
  - tech
thumbnail: https://thmb.techidaily.com/6b363964fc2e56f73bd871dd934c71ef94eb37eb3e4be61bfc1959bf2c673820.jpg
---

## How to Completely Remove Your Data From a Windows PC Safely and Without Cost - Expert Tips & Tricks

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
<li><a href="https://some-guidance.techidaily.com/new-the-complete-azure-guide-to-speech-to-text-integration/"><u>[New] The Complete Azure Guide to Speech-to-Text Integration</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-triumph-in-the-digital-arena-discovering-youtubes-top-five-tactics/"><u>[New] Triumph in the Digital Arena - Discovering YouTube’s Top Five Tactics</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-inshot-unpacked-editors-edition-detailed-review/"><u>[Updated] InShot Unpacked Editor's Edition Detailed Review</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-the-ultimate-dji-phantom-upgrade-kit/"><u>[Updated] The Ultimate DJI Phantom Upgrade Kit</u></a></li>
<li><a href="https://article-helps.techidaily.com/decoding-the-freeze-phenomenon-in-photobooth-videos/"><u>Decoding the Freeze Phenomenon in Photobooth Videos</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/discovering-the-world-of-technology-with-toms-hardware/"><u>Discovering the World of Technology with Tom's Hardware</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/elevating-handheld-gaming-with-asuss-rog-ally-x-a-detailed-review-of-its-high-end-features-and-cost/"><u>Elevating Handheld Gaming with Asus's ROG Ally X: A Detailed Review of Its High-End Features and Cost</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-windows-11-20plus-crucial-configuration-tweaks-revealed/"><u>Enhancing Windows 11: 20+ Crucial Configuration Tweaks Revealed</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/high-refresh-rate-marvels/"><u>High Refresh Rate Marvels</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/1723341696920-imaging-techniques-like-oct-may-be-used-postoperatively-to-confirm-the-success-of-surgical-interventions-such-as-retinal-detachment-repair/"><u>Imaging Techniques Like OCT May Be Used Postoperatively to Confirm the Success of Surgical Interventions Such as Retinal Detachment Repair</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-sim-cards-of-realme-narzo-60-pro-5g-without-puk-codes-by-drfone-android/"><u>In 2024, How To Unlock SIM Cards Of Realme Narzo 60 Pro 5G Without PUK Codes</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-optimizing-film-length-for-instagram-on-mac/"><u>In 2024, Optimizing Film Length for Instagram on Mac</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/innovative-hardware-solutions-curated-by-team-tom/"><u>Innovative Hardware Solutions Curated by Team Tom</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/navigating-through-new-horizons-of-technology-at-toms-system-solutions/"><u>Navigating Through New Horizons of Technology at Tom's System Solutions</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/partner-with-local-organizations-for-community-projects-that-align-with-your-corporate-social-responsibility-goals-and-can-improve-the-lives-of-those-affect14/"><u>Partner with Local Organizations for Community Projects that Align with Your Corporate Social Responsibility Goals and Can Improve the Lives of Those Affected by Environmental Issues.</u></a></li>
<li><a href="https://discover-blog.techidaily.com/step-by-step-guide-training-techniques-from-how-to-train-your-dragon-2-copy-and-preserve-the-wisdom/"><u>Step-by-Step Guide: Training Techniques From 'How to Train Your Dragon 2' - Copy & Preserve the Wisdom</u></a></li>
<li><a href="https://app-tips.techidaily.com/1723620264574-struggling-with-a-forgotten-icloud-login-discover-these-6-effective-remedies/"><u>Struggling with a Forgotten iCloud Login? Discover These 6 Effective Remedies</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/uncovering-hidden-tech-gems-a-deep-dive-into-new-releases-at-toms-hardware/"><u>Uncovering Hidden Tech Gems: A Deep Dive Into New Releases at Tom's Hardware</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/zenith-in-gaming-computing-evaluating-the-stellar-performance-of-ryzen-5-9600x-and-ryzen-7-9700xs-new-era/"><u>Zenith in Gaming Computing: Evaluating the Stellar Performance of Ryzen 5 9600X and Ryzen 7 9700X's New Era</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/43goO8X0iX0?si=48Cqf6td2q_6T6h3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

