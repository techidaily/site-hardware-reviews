---
title: "Exclusive Sony Xperia 1 IV Analysis: The Ultimate Choice for Affluent Photographers & Videographers - Insights From ZDNet"
date: 2025-01-06T16:20:35.409Z
updated: 2025-01-12T21:58:06.659Z
tags:
  - mobile-accessories
categories:
  - tech
thumbnail: https://thmb.techidaily.com/b7ec02702d51d57959e5bd1248adaf8d9c4e1536be03bd52fccab5d6aa482430.jpg
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/YB7Ou4-iKVM?si=7Fq8iUwI8voccMLx" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to transform a Flipper Zero into an Apple AirTag

**What you'll** **need**: A Flipper Zero, an Apple AirTag (or [tracker from another brand](https://www.zdnet.com/article/best-bluetooth-tracker/)), an [iPhone](https://www.zdnet.com/article/best-iphone/) and an [Android phone](https://www.zdnet.com/article/best-android-phone/).

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zWYVKFk3yPQ?si=Yu7xsjIYgRiq8zHk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Install Momentum firmware

First, install the Momentum firmware on your Flipper Zero. The most straightforward method is to use the web installer, but rest assured, you can revert to the stock firmware at any point [using the desktop or mobile app](https://flipperzero.one/downloads). Simply navigate to the [Momentum web installer page](https://momentum-fw.dev/update/), connect your Flipper Zero, and follow the prompts.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/mK1lEBRm_1w?si=FSaM0OKO0XBCgjtT" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Downloading FindMy Flipper

Once installed, you'll discover a host of new applications on your Flipper Zero, including one named **FindMy Flipper**. This app was developed and [built by cybersecurity engineer Matthew KuKanich](https://github.com/MatthewKuKanich/FindMyFlipper).

**Also: [Flipper Zero: 'Can you really hack Wi-Fi networks?' and other questions answered](https://www.zdnet.com/home-and-office/flipper-zero-can-you-really-hack-wi-fi-networks-and-other-questions-answered/)**

The app leverages the Flipper Zero's Bluetooth capabilities to act as an Apple AirTag, (or if you prefer, a Samsung SmartTag or Tile tag, but that process is even more cumbersome). It uses the Flipper Zero Bluetooth low energy (BLE) beacon to broadcast a signal that can be picked up by iPhones and sent back to Apple for viewing in the FindMy app.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/HaM818fFKXQ?si=ZZLA4lFSHSgCpSE0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Setting up the Flipper Zero

Now brace yourself for the more demanding tasks ahead! But fear not, as Flipper Zero aficionado [The Talking Sasquatch](https://www.youtube.com/@TalkingSasquach) has put together a video tutorial below that lays out the necessary steps in detail.

You'll need an AirTag, an iPhone, and an Android smartphone to follow along.

**Also: [How to unlock the Flipper Zero's true power](https://www.zdnet.com/article/how-to-unlock-the-flipper-zero-true-power/)**

I've personally gone through these steps multiple times and can confirm their effectiveness. But precision is key -- make sure to follow each step meticulously. A single misstep is enough to stop this from working and leave you scratching your head.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/wNhKhWc0wLc?si=1XLYV0sXV52Xc0lu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://facebook-videos.techidaily.com/updated-adapt-to-facebooks-algorithm-shift-now-for-2024/"><u>[Updated] Adapt to Facebook's Algorithm Shift Now for 2024</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-unveiling-the-magic-crafting-animated-gifs-with-ease/"><u>[Updated] Unveiling the Magic Crafting Animated GIFs with Ease</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-boosting-video-dimensions-on-youtube-platform/"><u>2024 Approved Boosting Video Dimensions on YouTube Platform</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/asus-proart-pa32ucxr-mini-led-monitor-test-drive-exceptional-color-fidelity-for-professionals/"><u>Asus ProArt PA32UCXR Mini LED Monitor Test Drive: Exceptional Color Fidelity for Professionals</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/average-gain-for-youtubers-per-ad-exposure-for-2024/"><u>Average Gain for YouTubers per Ad Exposure for 2024</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/comprehensive-analysis-of-hostingers-managed-servers-vps-cloud-and-sharing-options/"><u>Comprehensive Analysis of Hostinger's Managed Servers: VPS, Cloud & Sharing Options</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/exploring-the-dual-edges-of-microsofts-flagship-tablet-sleek-design-meets-mediocre-ai-integration/"><u>Exploring the Dual Edges of Microsoft's Flagship Tablet: Sleek Design Meets Mediocre AI Integration</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-cast-samsung-galaxy-a05-screen-to-pc-using-wifi-drfone-by-drfone-android/"><u>How to Cast Samsung Galaxy A05 Screen to PC Using WiFi | Dr.fone</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-unfortunately-contacts-has-stopped-error-on-lava-blaze-2-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Unfortunately, Contacts Has Stopped Error on Lava Blaze 2 | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-sleek-editing-techniques-for-targeted-photography-softness/"><u>In 2024, Sleek Editing Techniques for Targeted Photography Softness</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/in-depth-raspberry-pi-cm4-reviewers-guide-the-ultimate-industrial-companion/"><u>In-Depth Raspberry Pi CM4 Reviewer's Guide: The Ultimate Industrial Companion</u></a></li>
<li><a href="https://vp-tips.techidaily.com/las-mejores-herramientas-gratuitas-para-extraer-videos-en-dvd-desde-macos-big-sur-listado-2020/"><u>Las Mejores Herramientas Gratuitas Para Extraer Vídeos en DVD Desde macOS Big Sur - Listado 2020</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-free-to-edit-top-10-online-video-editors-with-no-watermark-limitations-for-2024/"><u>New Free to Edit Top 10 Online Video Editors with No Watermark Limitations for 2024</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/solution-public-hearings-allow-stakeholders-and-residents-to-voice-concerns-or-support-potentially-influencing-modifications-to-the-division-plan-for-better18/"><u>Solution: Public Hearings Allow Stakeholders and Residents to Voice Concerns or Support, Potentially Influencing Modifications to the Division Plan for Better Alignment with Community Interests.</u></a></li>
<li><a href="https://win-able.techidaily.com/solving-connectivity-issues-astro-a50-doesnt-appear-as-an-input-device/"><u>Solving Connectivity Issues: Astro A50 Doesn't Appear as an Input Device</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/the-ultimate-guide-to-high-performance-hardware-according-to-tom/"><u>The Ultimate Guide to High-Performance Hardware According to Tom</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/toms-tech-hub-comprehensive-insights-into-your-electronics/"><u>Tom's Tech Hub: Comprehensive Insights Into Your Electronics</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/toms-tech-review-expert-insights-into-hardware/"><u>Tom's Tech Review: Expert Insights Into Hardware</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/toms-tech-reviews-comprehensive-hardware-guides/"><u>Tom's Tech Reviews: Comprehensive Hardware Guides</u></a></li>
</ul></div>

