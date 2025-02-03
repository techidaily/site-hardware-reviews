---
title: "Ultimate Tutorial on Protecting Privacy: Remove Sensitive Information From a Windows PC Without Spending Money"
date: 2025-01-31T16:16:30.599Z
updated: 2025-02-01T16:47:26.248Z
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
<li><a href="https://fox-blue.techidaily.com/updated-multiplatform-vmix-blender-for-2024/"><u>[Updated] Multiplatform VMix Blender for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/a-guide-to-innovative-metaverse-marketing-for-2024/"><u>A Guide to Innovative Metaverse Marketing for 2024</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/best-pokemons-for-pvp-matches-in-pokemon-go-for-realme-gt-neo-5-drfone-by-drfone-virtual-android/"><u>Best Pokemons for PVP Matches in Pokemon Go For Realme GT Neo 5 | Dr.fone</u></a></li>
<li><a href="https://fox-pages.techidaily.com/como-activar-la-funcion-de-archivos-sin-conexion-y-mantenerla-actualizada-en-sistemas-windows-1011/"><u>Cómo Activar La Función De Archivos Sin Conexión Y Mantenerla Actualizada en Sistemas Windows 10/11</u></a></li>
<li><a href="https://hardware-help.techidaily.com/easy-guide-to-downloading-and-updating-your-thinkpad-t420s-drivers-for-windows-11-systems/"><u>Easy Guide to Downloading and Updating Your ThinkPad T420s Drivers for Windows 11 Systems</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-stop-google-chrome-from-tracking-your-location-on-infinix-smart-8-plus-drfone-by-drfone-virtual-android/"><u>How to Stop Google Chrome from Tracking Your Location On Infinix Smart 8 Plus? | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-unlock-apple-id-activation-lock-on-apple-iphone-xs-by-drfone-ios/"><u>In 2024, How to Unlock Apple ID Activation Lock On Apple iPhone XS?</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-unlock-xiaomi-redmi-note-13-pro-5g-phone-pattern-lock-without-factory-reset-by-drfone-android/"><u>In 2024, How to Unlock Xiaomi Redmi Note 13 Pro 5G Phone Pattern Lock without Factory Reset</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-igtv-video-placement-to-facebook-networks-5-ways/"><u>In 2024, IGTV Video Placement to Facebook Networks (5 Ways)</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/navigate-through-high-tech-stores-with-toms-hardware-spotlight/"><u>Navigate Through High-Tech Stores With Tom's Hardware Spotlight</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/own-an-rtx-4070-equipped-hp-omen-save-300-today-with-limited-offer/"><u>Own an RTX 4070-Equipped HP Omen, Save $300 Today with Limited Offer</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/preview-of-advanced-dell-x-series-and-inspirons-with-qualcomms-snapdragon-chips-launch-targeting-third-quarter/"><u>Preview of Advanced Dell X Series and Inspirons with Qualcomm's Snapdragon Chips: Launch Targeting Third Quarter</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/ryzen-ai-300-laptop-release-postponed-new-arrival-date-and-best-buy-listings-july-28/"><u>Ryzen AI 300 Laptop Release Postponed: New Arrival Date and Best Buy Listings - July 28</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/samsung-book4-edge-vs-iphone-12-showdown-unveiling-early-benchmarks-of-snapdragon-x-elite/"><u>Samsung Book4 Edge vs iPhone 12 Showdown: Unveiling Early Benchmarks of Snapdragon X Elite</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/the-ultimate-resource-for-savvy-shoppers-toms-computer-components-review/"><u>The Ultimate Resource for Savvy Shoppers: Tom's Computer Components Review</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/toms-computer-components-your-guide-to-top-tech-reviews/"><u>Tom's Computer Components: Your Guide to Top Tech Reviews</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/toms-hardware-review-top-tech-insights/"><u>Tom's Hardware Review - Top Tech Insights</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/1KKovVi9epE?si=EF7KA7b4KsEpWA-M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

