---
title: Solution to Follow-Up Question 3
date: 2025-01-08T02:09:43.749Z
updated: 2025-01-12T17:44:09.991Z
tags:
  - mobile-accessories
categories:
  - tech
thumbnail: https://www.zdnet.com/a/img/resize/96c53687bb80dbd82d1739846cf73f3fbd0a1dd8/2023/11/16/d9083aa9-03b2-48e7-8882-10abbbfed5af/nomad-modern-leather-iphone-15-pro-case-zdnet-1.jpg?width=278&height=156&fit=crop&auto=webp
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/LeKJBWb6Jhk?si=AnViizAPiIT1YCRA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to transform a Flipper Zero into an Apple AirTag

**What you'll** **need**: A Flipper Zero, an Apple AirTag (or [tracker from another brand](https://www.zdnet.com/article/best-bluetooth-tracker/)), an [iPhone](https://www.zdnet.com/article/best-iphone/) and an [Android phone](https://www.zdnet.com/article/best-android-phone/).

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MPoakxUNf9o?si=S-ppSqzHzN9VrxC7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Install Momentum firmware

First, install the Momentum firmware on your Flipper Zero. The most straightforward method is to use the web installer, but rest assured, you can revert to the stock firmware at any point [using the desktop or mobile app](https://flipperzero.one/downloads). Simply navigate to the [Momentum web installer page](https://momentum-fw.dev/update/), connect your Flipper Zero, and follow the prompts.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kx-Pb0otJCs?si=Mvr49yQVesmJA8-O" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Downloading FindMy Flipper

Once installed, you'll discover a host of new applications on your Flipper Zero, including one named **FindMy Flipper**. This app was developed and [built by cybersecurity engineer Matthew KuKanich](https://github.com/MatthewKuKanich/FindMyFlipper).

**Also: [Flipper Zero: 'Can you really hack Wi-Fi networks?' and other questions answered](https://www.zdnet.com/home-and-office/flipper-zero-can-you-really-hack-wi-fi-networks-and-other-questions-answered/)**

The app leverages the Flipper Zero's Bluetooth capabilities to act as an Apple AirTag, (or if you prefer, a Samsung SmartTag or Tile tag, but that process is even more cumbersome). It uses the Flipper Zero Bluetooth low energy (BLE) beacon to broadcast a signal that can be picked up by iPhones and sent back to Apple for viewing in the FindMy app.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fJlICvacgJY?si=jNeijBVj7ia4ammA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Setting up the Flipper Zero

Now brace yourself for the more demanding tasks ahead! But fear not, as Flipper Zero aficionado [The Talking Sasquatch](https://www.youtube.com/@TalkingSasquach) has put together a video tutorial below that lays out the necessary steps in detail.

You'll need an AirTag, an iPhone, and an Android smartphone to follow along.

**Also: [How to unlock the Flipper Zero's true power](https://www.zdnet.com/article/how-to-unlock-the-flipper-zero-true-power/)**

I've personally gone through these steps multiple times and can confirm their effectiveness. But precision is key -- make sure to follow each step meticulously. A single misstep is enough to stop this from working and leave you scratching your head.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-yZKNLxj3po?si=-RbF6nCJEVlHWP-M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-earnings-expansion-on-glamour-channels/"><u>[Updated] 2024 Approved Earnings Expansion on Glamour Channels</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-ultimate-sound-design-editing-your-podcasts-in-garageband/"><u>[Updated] The Ultimate Sound Design Editing Your Podcasts in GarageBand</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-pioneering-physical-activity-bests-in-virtual-treadmills/"><u>2024 Approved Pioneering Physical Activity Bests in Virtual Treadmills</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/a-game-changer-in-connectivity-unveiling-the-might-of-asus-rt-be96u-7ghz-wifi-router/"><u>A Game Changer in Connectivity - Unveiling the Might of Asus RT-BE96U 7GHz WiFi Router</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/benchmarking-the-kingston-fury-beast-a-deep-dive-into-ddr5-6000-cl40-performance-with-2x32gb-memory-modules/"><u>Benchmarking the Kingston Fury Beast - A Deep Dive Into DDR5-6000 (CL40) Performance with 2X32GB Memory Modules</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/discover-the-best-in-computing-navigating-hardware-with-toms-guidance/"><u>Discover the Best in Computing: Navigating Hardware with Tom's Guidance</u></a></li>
<li><a href="https://article-files.techidaily.com/in-2024-from-novices-to-pros-the-journey-of-picking-fpv-drone-blades/"><u>In 2024, From Novices to Pros The Journey of Picking FPV Drone Blades</u></a></li>
<li><a href="https://win-dash.techidaily.com/latest-version-how-to-find-and-update-dell-latitude-e6430-device-drivers-for-windows-resolved/"><u>Latest Version: How To Find & Update Dell Latitude E6430 Device Drivers For Windows [RESOLVED]</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/1723341686952-public-hearings-may-provide-community-members-with-a-platform-to-influence-the-land-division-process/"><u>Public Hearings May Provide Community Members with a Platform to Influence the Land Division Process</u></a></li>
<li><a href="https://program-issues.techidaily.com/1722994837441-resolving-concurrent-system-failures-on-personal-computers-easily/"><u>Resolving Concurrent System Failures on Personal Computers Easily!</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/the-tom-showdown-innovative-hardware-evaluations-and-tips/"><u>The Tom Showdown: Innovative Hardware Evaluations and Tips</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/the-ultimate-resource-for-pc-gear-tips-from-tom/"><u>The Ultimate Resource for PC Gear - Tips From Tom</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/the-ultimate-review-of-hp-omnibook-x-extending-workdays-with-its-powerful-16-hour-battery-life-and-innovative-xpower-tech/"><u>The Ultimate Review of HP OmniBook X: Extending Workdays with Its Powerful 16-Hour Battery Life and Innovative XPower Tech</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/toms-gadget-guide-unlocking-the-potential-of-your-electronics/"><u>Tom's Gadget Guide: Unlocking the Potential of Your Electronics</u></a></li>
<li><a href="https://technical-tips.techidaily.com/top-5-highly-rated-fire-pits-in-2n2-a-comprehensive-review-by-zdnet/"><u>Top 5 Highly Rated Fire Pits in 2N2: A Comprehensive Review by ZDNet</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/troubleshooting-sound-problems-a-guide-to-solving-audio-glitches-in-powerpoint/"><u>Troubleshooting Sound Problems: A Guide to Solving Audio Glitches in PowerPoint</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/ultimate-screen-recorder-companion-for-windows-10-for-2024/"><u>Ultimate Screen Recorder Companion for Windows 10 for 2024</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/uncovering-tech-secrets-with-toms-equipment-insights/"><u>Uncovering Tech Secrets with Tom's Equipment Insights</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-best-zero-cost-game-video-editing-tools-this-year-for-2024/"><u>Updated Best Zero-Cost Game Video Editing Tools This Year for 2024</u></a></li>
</ul></div>

