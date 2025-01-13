---
title: Discover the Leading iPhone Charging Wires for 2
date: 2025-01-06T19:16:22.035Z
updated: 2025-01-12T22:53:03.558Z
tags:
  - mobile-accessories
categories:
  - tech
thumbnail: https://www.zdnet.com/a/img/resize/b194d11d18bd78159474ca3d445d1d1f0b623319/2023/05/04/4320661d-dc64-4344-ada6-23f829833998/gettyimages-1370004251.jpg?width=278&height=156&fit=crop&auto=webp
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/tPgf_wSdhS8?si=BHoH1ryaxmwk-8FV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to transform a Flipper Zero into an Apple AirTag

**What you'll** **need**: A Flipper Zero, an Apple AirTag (or [tracker from another brand](https://www.zdnet.com/article/best-bluetooth-tracker/)), an [iPhone](https://www.zdnet.com/article/best-iphone/) and an [Android phone](https://www.zdnet.com/article/best-android-phone/).

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qObsqoJB9LI?si=ppqxfXzP0UL4J6Tp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Install Momentum firmware

First, install the Momentum firmware on your Flipper Zero. The most straightforward method is to use the web installer, but rest assured, you can revert to the stock firmware at any point [using the desktop or mobile app](https://flipperzero.one/downloads). Simply navigate to the [Momentum web installer page](https://momentum-fw.dev/update/), connect your Flipper Zero, and follow the prompts.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RBN1gYY5hUs?si=p89CMiMzeJzU0wGu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Downloading FindMy Flipper

Once installed, you'll discover a host of new applications on your Flipper Zero, including one named **FindMy Flipper**. This app was developed and [built by cybersecurity engineer Matthew KuKanich](https://github.com/MatthewKuKanich/FindMyFlipper).

**Also: [Flipper Zero: 'Can you really hack Wi-Fi networks?' and other questions answered](https://www.zdnet.com/home-and-office/flipper-zero-can-you-really-hack-wi-fi-networks-and-other-questions-answered/)**

The app leverages the Flipper Zero's Bluetooth capabilities to act as an Apple AirTag, (or if you prefer, a Samsung SmartTag or Tile tag, but that process is even more cumbersome). It uses the Flipper Zero Bluetooth low energy (BLE) beacon to broadcast a signal that can be picked up by iPhones and sent back to Apple for viewing in the FindMy app.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Iz2LYWd8EqI?si=G_3CqFRAmeVPczjj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Setting up the Flipper Zero

Now brace yourself for the more demanding tasks ahead! But fear not, as Flipper Zero aficionado [The Talking Sasquatch](https://www.youtube.com/@TalkingSasquach) has put together a video tutorial below that lays out the necessary steps in detail.

You'll need an AirTag, an iPhone, and an Android smartphone to follow along.

**Also: [How to unlock the Flipper Zero's true power](https://www.zdnet.com/article/how-to-unlock-the-flipper-zero-true-power/)**

I've personally gone through these steps multiple times and can confirm their effectiveness. But precision is key -- make sure to follow each step meticulously. A single misstep is enough to stop this from working and leave you scratching your head.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0Kr7Dpw0HuM?si=05wWDXdPgmC-oBBE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-friendly.techidaily.com/new-engineering-eye-catching-film-openings-for-2024/"><u>[New] Engineering Eye-Catching Film Openings for 2024</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-in-2024-best-drone-cameras-10-for-professional-filmmaking/"><u>[Updated] In 2024, Best Drone Cameras #10 For Professional Filmmaking</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-in-2024-discover-top-cost-effective-dvd-player-apps/"><u>[Updated] In 2024, Discover Top Cost-Effective DVD Player Apps</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/approved-unlocking-youtube-content-as-lively-download-free-animated-gifs/"><u>2024 Approved Unlocking YouTube Content as Lively, Download-Free Animated GIFs</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/best-budget-friendly-high-performance-gaming-laptops-below-1000/"><u>Best Budget-Friendly High-Performance Gaming Laptops Below $1,000</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/detailed-analysis-of-top-tier-computer-hardware-by-toms-technology-hub/"><u>Detailed Analysis of Top-Tier Computer Hardware by Tom's Technology Hub</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/1723862716918-exclusive-offer-on-lenovo-legion-gaming-pcs-with-rtx-graphics-and-ultra-smooth-display-get-750-off-today/"><u>Exclusive Offer on Lenovo Legion Gaming PCs with RTX Graphics & Ultra-Smooth Display – Get $750 Off Today!</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-life360-learn-how-everything-works-on-nubia-red-magic-8s-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Life360 Learn How Everything Works On Nubia Red Magic 8S Pro | Dr.fone</u></a></li>
<li><a href="https://youtube-data.techidaily.com/24-what-makes-a-youtube-short-go-viral/"><u>In 2024, What Makes a YouTube Short Go Viral?</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/launch-into-action-quick-tips-to-start-going-live-on-facebook-immediately/"><u>Launch Into Action Quick Tips to Start Going Live on Facebook Immediately</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/1723862699425-mastering-modern-devices-tips-and-tricks-from-toms-hardware/"><u>Mastering Modern Devices: Tips and Tricks From Tom's Hardware</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/1723862735364-score-an-epic-deal-nitro-16-gaming-laptop-with-amd-and-rtx-acers-rtx-4070-for-just-1129/"><u>Score an Epic Deal: Nitro 16 Gaming Laptop with AMD and RTX ([Acer's RTX 4070) for Just $1,129</u></a></li>
<li><a href="https://article-helps.techidaily.com/sky-high-savings-the-least-expensive-drones-on-market-for-2024/"><u>Sky-High Savings The Least Expensive Drones on Market for 2024</u></a></li>
<li><a href="https://android-transfer.techidaily.com/top-5-from-vivo-y100i-power-5g-to-iphone-contacts-transfer-apps-and-software-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>Top 5 from Vivo Y100i Power 5G to iPhone Contacts Transfer Apps and Software | Dr.fone</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/1723862716478-unleash-your-productivity-the-innovative-and-user-friendly-acemagic-x1-dual-screen-laptop-awaits-you/"><u>Unleash Your Productivity: The Innovative and User-Friendly Acemagic X1 Dual-Screen Laptop Awaits You!</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/unveiling-the-latest-in-computing-at-toms-electronics-hub/"><u>Unveiling the Latest in Computing at Tom's Electronics Hub</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/unveiling-the-potency-of-the-asus-tuf-gaming-a14-a-review-for-gamers-and-professionals/"><u>Unveiling the Potency of the ASUS TUF Gaming A14: A Review for Gamers and Professionals</u></a></li>
</ul></div>

