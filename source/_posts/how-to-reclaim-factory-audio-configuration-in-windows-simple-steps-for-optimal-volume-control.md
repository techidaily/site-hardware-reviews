---
title: How to Reclaim Factory Audio Configuration in Windows - Simple Steps for Optimal Volume Control
date: 2024-11-22T17:17:52.565Z
updated: 2024-11-27T18:08:35.745Z
tags:
  - laptops
categories:
  - tech
thumbnail: https://www.zdnet.com/a/img/resize/30eed896050d40e73e69573aa737c5c12d40f559/2021/09/10/aa6b68a0-6821-4508-ad08-1495fdc63720/shutterstock-1660017136.jpg?auto=webp&fit=crop&frame=1&height=172&width=306
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
<li><a href="https://program-issues.techidaily.com/solved-fallout-3-crashing-on-windows-10/"><u>[SOLVED] Fallout 3 Crashing on Windows 10</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-live-stream-to-file-top-performing-obs-recording-tools-for-2024/"><u>[Updated] Live Stream to File Top Performing OBS Recording Tools for 2024</u></a></li>
<li><a href="https://discover-data.techidaily.com/die-besten-5-programme-fur-die-migration-von-computerdaten-kostenloser-download/"><u>Die Besten 5 Programme Für Die Migration Von Computerdaten – Kostenloser Download</u></a></li>
<li><a href="https://windows11.techidaily.com/easily-identify-last-opened-files-in-windows-explorer/"><u>Easily Identify Last Opened Files in Windows Explorer</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/1723862796251-gamers-dream-deal-capture-every-detail-with-the-incredible-gigabyte-gs3gs32qhttpswwwgigabytecomusmonitorplus-plusgraphics-32-qhd-monitor-at-199/"><u>Gamer's Dream Deal – Capture Every Detail with the Incredible Gigabyte GS3^[GS32Q](https://www.gigabyte.com/us/Monitor+-+Graphics) 32'' QHD Monitor at $199!</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/1723862766355-nice-price-drop-acers-34-curved-qhd-monitor-now-just-200-on-newegg/"><u>Nice Price Drop: Acer's 34 Curved QHD Monitor Now Just $200 on Newegg</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/outreach-for-backlinks-contact-influencers-bloggers-or-experts-in-the-field-and-ask-them-to-share-your-content-on-their-platforms-or-link-back-to-your-artic25/"><u>Outreach for Backlinks: Contact Influencers, Bloggers, or Experts in the Field and Ask Them to Share Your Content on Their Platforms or Link Back to Your Article.</u></a></li>
<li><a href="https://techidaily.com/remove-realme-lock-screen-without-password-realme-c67-5g-by-drfone-android-unlock-android-unlock/"><u>Remove Realme Lock Screen without Password(Realme C67 5G)</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/1723862780251-save-big-now-limited-offer-on-gigabytes-32-inch-qhd-gaming-monitor-gs3n32q-at-a-steal-only-199/"><u>Save Big Now – Limited Offer on Gigabyte's 32-Inch QHD Gaming Monitor (GS3n32Q) at a Steal: Only $199!</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/1723862814818-score-the-highest-gaming-quality-with-our-best-ever-rated-dell-s3222dgm-for-a-shocking-low-of-229/"><u>Score the Highest Gaming Quality with Our Best Ever Rated Dell S3222DGM for a Shocking Low of $229!</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/1723862802943-score-the-ultimate-bargain-279-32-dell-s322dmg-monitor-perfect-for-gamers-this-memorial-day/"><u>Score the Ultimate Bargain: $279 32” Dell S322DMG Monitor, Perfect for Gamers This Memorial Day</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/1723862827645-snag-your-deal-acer-nitro-24-curved-gaming-display-at-just-81/"><u>Snag Your Deal: Acer Nitro 24 Curved Gaming Display at Just $81!</u></a></li>
<li><a href="https://win-docs.techidaily.com/top-8-secure-password-tools-compatible-with-windows-11/"><u>Top 8 Secure Password Tools Compatible with Windows 11</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/ultimate-canva-substitutes-breakdown-discover-the-top-15-alternatives/"><u>Ultimate Canva Substitutes Breakdown: Discover the Top 15 Alternatives!</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/vintage-crt-technology-hits-700hz-refresh-rate-with-reduced-display-of-only-120p/"><u>Vintage CRT Technology Hits 700Hz Refresh Rate with Reduced Display of Only 120P</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/tPgf_wSdhS8?si=BHoH1ryaxmwk-8FV&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

