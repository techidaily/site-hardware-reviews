---
title: "Unveiling the Secrets of Sony LinkBuds: A Comprehensive Review by ZDnet on Software and Performance Mastery"
date: 2025-01-07T21:30:59.311Z
updated: 2025-01-13T02:01:35.688Z
tags:
  - mobile-accessories
categories:
  - tech
thumbnail: https://thmb.techidaily.com/26fc91ea31b084d9024cbf2c3260379dfbc09b55f5ef939a3a4cdd1934973c13.jpeg
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/0dOfcihxjiw?si=_fkp1S1Uw0N1dp6b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to transform a Flipper Zero into an Apple AirTag

**What you'll** **need**: A Flipper Zero, an Apple AirTag (or [tracker from another brand](https://www.zdnet.com/article/best-bluetooth-tracker/)), an [iPhone](https://www.zdnet.com/article/best-iphone/) and an [Android phone](https://www.zdnet.com/article/best-android-phone/).

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/lCpzYpVPIZA?si=hNte-mPRIzjvqpRy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Install Momentum firmware

First, install the Momentum firmware on your Flipper Zero. The most straightforward method is to use the web installer, but rest assured, you can revert to the stock firmware at any point [using the desktop or mobile app](https://flipperzero.one/downloads). Simply navigate to the [Momentum web installer page](https://momentum-fw.dev/update/), connect your Flipper Zero, and follow the prompts.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/B2MlLvGxMwI?si=q_blGjXyJrGtzT8d" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Downloading FindMy Flipper

Once installed, you'll discover a host of new applications on your Flipper Zero, including one named **FindMy Flipper**. This app was developed and [built by cybersecurity engineer Matthew KuKanich](https://github.com/MatthewKuKanich/FindMyFlipper).

**Also: [Flipper Zero: 'Can you really hack Wi-Fi networks?' and other questions answered](https://www.zdnet.com/home-and-office/flipper-zero-can-you-really-hack-wi-fi-networks-and-other-questions-answered/)**

The app leverages the Flipper Zero's Bluetooth capabilities to act as an Apple AirTag, (or if you prefer, a Samsung SmartTag or Tile tag, but that process is even more cumbersome). It uses the Flipper Zero Bluetooth low energy (BLE) beacon to broadcast a signal that can be picked up by iPhones and sent back to Apple for viewing in the FindMy app.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/M5pwd2mwaQQ?si=qyZHgdTlbQbc32Mp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Setting up the Flipper Zero

Now brace yourself for the more demanding tasks ahead! But fear not, as Flipper Zero aficionado [The Talking Sasquatch](https://www.youtube.com/@TalkingSasquach) has put together a video tutorial below that lays out the necessary steps in detail.

You'll need an AirTag, an iPhone, and an Android smartphone to follow along.

**Also: [How to unlock the Flipper Zero's true power](https://www.zdnet.com/article/how-to-unlock-the-flipper-zero-true-power/)**

I've personally gone through these steps multiple times and can confirm their effectiveness. But precision is key -- make sure to follow each step meticulously. A single misstep is enough to stop this from working and leave you scratching your head.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JNxZ4Z6BVCg?si=522oz1OPSQDhNYWT" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://vimeo-videos.techidaily.com/new-in-2024-streamlining-the-process-vimeo-to-mp3-conversion/"><u>[New] In 2024, Streamlining the Process Vimeo to MP3 Conversion</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-unveiling-hand-trackings-evolution-and-practice-for-2024/"><u>[New] Unveiling Hand Tracking's Evolution and Practice for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-cinemas-best-bits-select-snippets-for-edits/"><u>2024 Approved Cinema’s Best Bits Select Snippets for Edits</u></a></li>
<li><a href="https://technical-tips.techidaily.com/discover-the-future-at-samsung-unpacked-2-groovy-what-to-expect-rumors-news-and-announcements-await/"><u>Discover the Future at Samsung Unpacked 2 Groovy. What to Expect ! Rumors, News, and Announcements Await</u></a></li>
<li><a href="https://win-blog.techidaily.com/effective-strategies-eliminating-frequent-crashes-in-the-pacific-drive-program-for-pc-users/"><u>Effective Strategies: Eliminating Frequent Crashes in the Pacific Drive Program for PC Users</u></a></li>
<li><a href="https://discover-fantastic.techidaily.com/effizientes-passwortverschieben-auf-ihr-neues-iphone-fuhrung-durch-die-schritte/"><u>Effizientes Passwortverschieben Auf Ihr Neues iPhone - Führung Durch Die Schritte</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/elevate-your-build-with-gskills-trident-z5-rgb-memory-sticks-an-ideal-choice-for-2x48gb-motherboard-setups/"><u>Elevate Your Build with G.SKILL's Trident Z5 RGB Memory Sticks - An Ideal Choice for 2X48GB Motherboard Setups</u></a></li>
<li><a href="https://article-files.techidaily.com/enhance-your-iphone-photography-with-time-lapse-for-2024/"><u>Enhance Your iPhone Photography with Time-Lapse for 2024</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/1723341710933-experience-unmatched-precision-and-comfort-in-depth-look-at-the-keychron-q1-he-the-long-awaited-wireless-mx-version/"><u>Experience Unmatched Precision and Comfort - In-Depth Look at the Keychron Q1 HE, The Long-Awaited Wireless MX Version!</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/experts-rating-in-depth-analysis-of-dough-spectrum-black-the-ultimate-27-oled-gaming-display-with-superior-color-fidelity-and-exceptional-responsiveness/"><u>Experts' Rating: In-Depth Analysis of Dough Spectrum Black - The Ultimate 27 OLED Gaming Display with Superior Color Fidelity & Exceptional Responsiveness</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/exploring-computer-gear-with-toms-equipment-insights/"><u>Exploring Computer Gear with Tom's Equipment Insights</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/exploring-the-fusion-of-anime-and-disappointment-in-the-valkyrie-vind-sl125/"><u>Exploring the Fusion of Anime and Disappointment in the Valkyrie Vind SL125</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/navigating-high-tech-terrain-trusted-reviews-and-insights-by-toms-hardware-specialists/"><u>Navigating High-Tech Terrain: Trusted Reviews and Insights by Tom's Hardware Specialists</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/navigating-technology-trends-on-toms-hardware-platform/"><u>Navigating Technology Trends on Tom's Hardware Platform</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-event-log-failures-in-windows-11/"><u>Overcoming Event Log Failures in Windows 11</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/skys-bounty-the-ultimate-guide-to-drone-video-editing-for-2024/"><u>Sky's Bounty The Ultimate Guide to Drone Video Editing for 2024</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/the-mu-reviewed-speedy-performance-that-surpasses-raspberry-pi-4-yet-comes-with-a-price-tag/"><u>The Mu Reviewed: Speedy Performance That Surpasses Raspberry Pi 4 Yet Comes With a Price Tag</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/top-pick-for-portable-power-players-in-depth-analysis-of-the-asus-rog-ally-x-handheld-console/"><u>Top Pick for Portable Power Players: In-Depth Analysis of the Asus ROG Ally X Handheld Console</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-kernel-event-141-resolving-hw-errors/"><u>Troubleshooting Kernel Event 141: Resolving HW Errors</u></a></li>
</ul></div>

