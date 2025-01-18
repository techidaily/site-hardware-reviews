---
title: "Revolutionizing Outdoor Fitness Tracking: In-Depth Review of Garmin's Premium Modern Epix Smartwatch | ZDNET"
date: 2025-01-14T17:13:12.330Z
updated: 2025-01-18T16:22:08.792Z
tags:
  - mobile-accessories
categories:
  - tech
thumbnail: https://thmb.techidaily.com/5cb2e70fe5fc4984663e55071f50818b86ad28c6053861679577418a188e88c7.jpg
---

## DIY Guide: Crafting Your Personalized Apple AirTag Using the Flip Phone Zero - Plus, It's Worth It![ZDNet]

![Flipper Zero running FindMy Flipper app.](https://www.zdnet.com/a/img/resize/0c38a7573854423df7e0c491f5148d368b7398af/2024/03/25/32f0523e-cabe-4ab5-adc5-dabae2fd6883/img-9157.jpg?auto=webp&width=1280)

Flipper Zero running FindMy Flipper app.

Adrian Kingsley-Hughes/ZDNET

I'm continually amazed by the ingenuity of the development community surrounding the [Flipper Zero](https://shop.flipperzero.one/). This time, the company has enabled the Flipper Zero to emulate an [Apple AirTag](https://apple.sjv.io/c/159047/435031/7613?&sharedid=zdnet&partnerpropertyid=1980086&u=https%3A%2F%2Fwww.apple.com%2Fshop%2Fbuy-airtag%2Fairtag%2F1-pack%3F&subId1=zd-%5F%5FCOM%5FCLICK%5FID%5F%5F-dtp).

Before I delve further, it's important to note that this isn't as simple as pressing a button or flipping a switch. If you're not prepared to install custom firmware, don't have access to an AirTag, don't have an iPhone and an Android device, or are hesitant to experiment with technologies such as Docker, then this guide is probably not for you.

**Also: [7 cool and useful things to do with your Flipper Zero](https://www.zdnet.com/article/best-iphone-power-bank/)**

However, if you own a Flipper Zero and are up for a challenge, then this is certainly worth a try. It will provide you with a deeper understanding of the Flipper Zero's capabilities and also how AirTags function.

#### Newsletters

ZDNET Tech Today

ZDNET's Tech Today newsletter is a daily briefing of the newest, most talked about stories, five days a week.

 Subscribe

[See all](https://www.zdnet.com/newsletters/)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Nl0Z0eth1u4?si=0eecOBNfc--51AJO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to transform a Flipper Zero into an Apple AirTag

**What you'll** **need**: A Flipper Zero, an Apple AirTag (or [tracker from another brand](https://www.zdnet.com/article/best-bluetooth-tracker/)), an [iPhone](https://www.zdnet.com/article/best-iphone/) and an [Android phone](https://www.zdnet.com/article/best-android-phone/).

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/S0b9szh8vEk?si=NlGzpJ6MN_SJNk5A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Install Momentum firmware

First, install the Momentum firmware on your Flipper Zero. The most straightforward method is to use the web installer, but rest assured, you can revert to the stock firmware at any point [using the desktop or mobile app](https://flipperzero.one/downloads). Simply navigate to the [Momentum web installer page](https://momentum-fw.dev/update/), connect your Flipper Zero, and follow the prompts.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UoBCgLTmznE?si=MXXiGsd2qpd_DrzE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Downloading FindMy Flipper

Once installed, you'll discover a host of new applications on your Flipper Zero, including one named **FindMy Flipper**. This app was developed and [built by cybersecurity engineer Matthew KuKanich](https://github.com/MatthewKuKanich/FindMyFlipper).

**Also: [Flipper Zero: 'Can you really hack Wi-Fi networks?' and other questions answered](https://www.zdnet.com/home-and-office/flipper-zero-can-you-really-hack-wi-fi-networks-and-other-questions-answered/)**

The app leverages the Flipper Zero's Bluetooth capabilities to act as an Apple AirTag, (or if you prefer, a Samsung SmartTag or Tile tag, but that process is even more cumbersome). It uses the Flipper Zero Bluetooth low energy (BLE) beacon to broadcast a signal that can be picked up by iPhones and sent back to Apple for viewing in the FindMy app.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cBCyRXC1-Tw?si=lN9P2xo0hsfyD8K6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Setting up the Flipper Zero

Now brace yourself for the more demanding tasks ahead! But fear not, as Flipper Zero aficionado [The Talking Sasquatch](https://www.youtube.com/@TalkingSasquach) has put together a video tutorial below that lays out the necessary steps in detail.

You'll need an AirTag, an iPhone, and an Android smartphone to follow along.

**Also: [How to unlock the Flipper Zero's true power](https://www.zdnet.com/article/how-to-unlock-the-flipper-zero-true-power/)**

I've personally gone through these steps multiple times and can confirm their effectiveness. But precision is key -- make sure to follow each step meticulously. A single misstep is enough to stop this from working and leave you scratching your head.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JAkb8Bv3AU4?si=2rHwnZYTzTLieKgY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Using custom Python scripts (and why you should)

You can also go even further… although the process gets even more complicated! Using custom Python scripts from [KuKanich's GitHub](https://github.com/MatthewKuKanich/FindMyFlipper/tree/main/AirTagGeneration), you can generate your own AirTag digital keys, which means you won't need a physical AirTag to make this work.

If you found the previous steps challenging, this will take it up a notch, offering you valuable experience with the platform-as-a-service product, Docker.

This brings me to one of the things that I really like about the [Flipper Zero](https://shop.flipperzero.one/): it's a great way to learn new skills and get a deeper understanding of how modern technology works. It's not just a wonderful portable pen-testing tool, but also a great learning tool for adults and kids alike.

#### Featured reviews

[Dyson's latest headphones may look like heavy machinery, but they sound like a dream](https://www.zdnet.com/article/i-tested-dysons-500-flagship-headphones-and-theyre-more-competitive-than-expected/ "Dyson's latest headphones may look like heavy machinery, but they sound like a dream")

[Only two multitool brands are worth your money - here's which one I carry](https://www.zdnet.com/article/only-two-multitool-brands-are-worth-your-money-heres-which-one-i-carry/ "Only two multitool brands are worth your money - here's which one I carry")

[I replaced my Samsung Galaxy S24 Ultra with the Pixel 9 Pro XL for two weeks - and can't go back](https://www.zdnet.com/article/i-replaced-my-samsung-galaxy-s24-ultra-with-the-pixel-9-pro-xl-for-two-weeks-and-cant-go-back/ "I replaced my Samsung Galaxy S24 Ultra with the Pixel 9 Pro XL for two weeks - and can't go back")

[One of the most premium Copilot+ PCs I've tested is also one of the most affordable](https://www.zdnet.com/article/one-of-the-most-premium-copilot-pcs-ive-tested-is-also-one-of-the-most-affordable/ "One of the most premium Copilot+ PCs I've tested is also one of the most affordable")

* [Dyson's latest headphones may look like heavy machinery, but they sound like a dream](https://www.zdnet.com/article/i-tested-dysons-500-flagship-headphones-and-theyre-more-competitive-than-expected/ "Dyson's latest headphones may look like heavy machinery, but they sound like a dream")
* [Only two multitool brands are worth your money - here's which one I carry](https://www.zdnet.com/article/only-two-multitool-brands-are-worth-your-money-heres-which-one-i-carry/ "Only two multitool brands are worth your money - here's which one I carry")
* [I replaced my Samsung Galaxy S24 Ultra with the Pixel 9 Pro XL for two weeks - and can't go back](https://www.zdnet.com/article/i-replaced-my-samsung-galaxy-s24-ultra-with-the-pixel-9-pro-xl-for-two-weeks-and-cant-go-back/ "I replaced my Samsung Galaxy S24 Ultra with the Pixel 9 Pro XL for two weeks - and can't go back")
* [One of the most premium Copilot+ PCs I've tested is also one of the most affordable](https://www.zdnet.com/article/one-of-the-most-premium-copilot-pcs-ive-tested-is-also-one-of-the-most-affordable/ "One of the most premium Copilot+ PCs I've tested is also one of the most affordable")

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
<li><a href="https://extra-support.techidaily.com/new-integrating-easy-to-use-timestamps-into-your-youtube-videos/"><u>[New] Integrating Easy-to-Use Timestamps Into Your YouTube Videos</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-effortless-fb-movie-access-top-8-tools-of-23/"><u>[Updated] Effortless FB Movie Access Top #8 Tools of '23</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-game-on-a-comprehensive-guide-to-xbox-one-captures/"><u>2024 Approved Game On A Comprehensive Guide to Xbox One Captures</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-the-artisan-writes-crafting-hdr-magic-with-iphone/"><u>2024 Approved The Artisan’ Writes Crafting HDR Magic with iPhone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/best-ways-on-how-to-unlockbypassswiperemove-oppo-a1x-5g-fingerprint-lock-by-drfone-android/"><u>Best Ways on How to Unlock/Bypass/Swipe/Remove Oppo A1x 5G Fingerprint Lock</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/1723864250303-compare-top-rated-affordable-ssd-options-saving-on-1tb-to-4tb-capacities/"><u>Compare Top-Rated Affordable SSD Options - Saving on 1TB to 4TB Capacities</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/devrepos-tricks-for-transforming-kindle-into-a-versatile-e-ink-monitor-a-complete-guide/"><u>DevRepo's Tricks for Transforming Kindle Into a Versatile, E-Ink Monitor: A Complete Guide</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/efficient-power-protection-and-fast-charging-a-closer-look-at-the-apc-be60-600m1-back-ups-unit/"><u>Efficient Power Protection and Fast Charging: A Closer Look at the APC BE60 600M1 Back-UPS Unit</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/1723864253042-exclusive-offer-get-the-4tb-crucial-p3-plus-nvme-gen4-solid-state-drive-at-an-unbelievable-price-of-just-005gb/"><u>Exclusive Offer: Get the 4TB Crucial P3 Plus NVMe Gen4 Solid State Drive at an Unbelievable Price of Just $0.05/GB</u></a></li>
<li><a href="https://win-top.techidaily.com/gebooten-im-richtigen-bootstrapping-wie-man-das-vmware-esxi-passwort-effizient-zurucksetzt-ohne-eine-neuinstallation-durchfuhren-zu-mussen/"><u>Gebooten Im Richtigen Bootstrapping: Wie Man Das VMware ESXi Passwort Effizient Zurücksetzt, Ohne Eine Neuinstallation Durchführen Zu Müssen</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-change-your-apple-id-password-on-your-apple-iphone-xr-by-drfone-ios/"><u>How To Change Your Apple ID Password On your Apple iPhone XR</u></a></li>
<li><a href="https://win-hacks.techidaily.com/pcdjs-new-release-access-the-free-dex-361-beta-software-download/"><u>PCDJ's New Release: Access the Free DEX 3.6.1 Beta Software Download!</u></a></li>
<li><a href="https://win-web.techidaily.com/resolving-no-image-issues-on-screens-essential-advice-by-yl-software-experts/"><u>Resolving No-Image Issues on Screens: Essential Advice by YL Software Experts</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/the-ultimate-guide-to-electronics-wisdom-from-toms-hardware/"><u>The Ultimate Guide to Electronics: Wisdom From Tom's Hardware</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/toms-tech-reviews-in-depth-insights-on-the-latest-gadgets/"><u>Tom's Tech Reviews: In-Depth Insights on the Latest Gadgets</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/top-rated-gaming-motherboards-of-2024-comprehensive-guide-by-socket-type-and-cpu-chipset/"><u>Top Rated Gaming Motherboards of 2024: Comprehensive Guide by Socket Type & CPU Chipset</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/ultimate-guide-by-toms-review-team-hardware-insights/"><u>Ultimate Guide by Tom's Review Team: Hardware Insights</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/ultimate-insight-toms-hardware-digest/"><u>Ultimate Insight: Tom's Hardware Digest</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/unveiling-camm2-the-innovative-new-memory-design-thats-faster-compact-and-user-friendly/"><u>Unveiling CAMM2: The Innovative New Memory Design That's Faster, Compact, And User-Friendly</u></a></li>
</ul></div>

