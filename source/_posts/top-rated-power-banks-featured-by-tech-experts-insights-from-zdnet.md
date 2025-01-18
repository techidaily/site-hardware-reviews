---
title: Top-Rated Power Banks Featured by Tech Experts - Insights From ZDNet
date: 2025-01-11T16:36:09.998Z
updated: 2025-01-18T16:36:55.088Z
tags:
  - mobile-accessories
categories:
  - tech
thumbnail: https://www.zdnet.com/a/img/resize/dea19938f44d77ea35af7016a109d48dff171434/2023/02/22/ba005bf0-f45e-426b-b54e-f6a6b503d883/zendure-supertank-pro.jpg?width=278&height=156&fit=crop&auto=webp
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/dKjioJQaUh8?si=Ls_AeuvGsSyL5ny2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to transform a Flipper Zero into an Apple AirTag

**What you'll** **need**: A Flipper Zero, an Apple AirTag (or [tracker from another brand](https://www.zdnet.com/article/best-bluetooth-tracker/)), an [iPhone](https://www.zdnet.com/article/best-iphone/) and an [Android phone](https://www.zdnet.com/article/best-android-phone/).

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9hsPbiic0O8?si=58mZ2Cu6wicQfsUP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Install Momentum firmware

First, install the Momentum firmware on your Flipper Zero. The most straightforward method is to use the web installer, but rest assured, you can revert to the stock firmware at any point [using the desktop or mobile app](https://flipperzero.one/downloads). Simply navigate to the [Momentum web installer page](https://momentum-fw.dev/update/), connect your Flipper Zero, and follow the prompts.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/iPCr_bxZjMQ?si=ubOsoq5umPEXL9xL" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Downloading FindMy Flipper

Once installed, you'll discover a host of new applications on your Flipper Zero, including one named **FindMy Flipper**. This app was developed and [built by cybersecurity engineer Matthew KuKanich](https://github.com/MatthewKuKanich/FindMyFlipper).

**Also: [Flipper Zero: 'Can you really hack Wi-Fi networks?' and other questions answered](https://www.zdnet.com/home-and-office/flipper-zero-can-you-really-hack-wi-fi-networks-and-other-questions-answered/)**

The app leverages the Flipper Zero's Bluetooth capabilities to act as an Apple AirTag, (or if you prefer, a Samsung SmartTag or Tile tag, but that process is even more cumbersome). It uses the Flipper Zero Bluetooth low energy (BLE) beacon to broadcast a signal that can be picked up by iPhones and sent back to Apple for viewing in the FindMy app.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qObsqoJB9LI?si=ppqxfXzP0UL4J6Tp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Setting up the Flipper Zero

Now brace yourself for the more demanding tasks ahead! But fear not, as Flipper Zero aficionado [The Talking Sasquatch](https://www.youtube.com/@TalkingSasquach) has put together a video tutorial below that lays out the necessary steps in detail.

You'll need an AirTag, an iPhone, and an Android smartphone to follow along.

**Also: [How to unlock the Flipper Zero's true power](https://www.zdnet.com/article/how-to-unlock-the-flipper-zero-true-power/)**

I've personally gone through these steps multiple times and can confirm their effectiveness. But precision is key -- make sure to follow each step meticulously. A single misstep is enough to stop this from working and leave you scratching your head.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LdVT_-3gESA?si=_HfjpbUEHSRKTXjt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-links.techidaily.com/updated-2024-approved-the-ultimate-guide-to-discovering-whatsapp-hacks/"><u>[Updated] 2024 Approved The Ultimate Guide to Discovering WhatsApp Hacks</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/2024-approved-share-the-laughs-right-top-gif-saver-for-twitter/"><u>2024 Approved Share the Laughs Right Top GIF Saver for Twitter</u></a></li>
<li><a href="https://extra-hints.techidaily.com/best-iphoneandroid-photo-background-subtraction/"><u>Best iPhone/Android Photo Background Subtraction</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-is-gsm-flasher-adb-legit-full-review-to-bypass-your-lava-yuva-3frp-lock-by-drfone-android/"><u>In 2024, Is GSM Flasher ADB Legit? Full Review To Bypass Your Lava Yuva 3FRP Lock</u></a></li>
<li><a href="https://technical-tips.techidaily.com/latest-mozilla-thunderbird-update-version-52-release/"><u>Latest Mozilla Thunderbird Update - Version 52 Release</u></a></li>
<li><a href="https://extra-skills.techidaily.com/megasecond-analysis-understanding-20mb-video-time-for-2024/"><u>MegaSecond Analysis Understanding 20Mb Video Time for 2024</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/reaching-39-million-motherboards-remarkable-comeback-mirrors-pre-covid-shipping-rates/"><u>Reaching 39 Million: Motherboards' Remarkable Comeback Mirrors Pre-COVID Shipping Rates</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/revolutionizing-the-market-asus-launches-specialized-motherboard-to-skyrocket-chinas-kx-7000-clock-speeds-by-25/"><u>Revolutionizing the Market: Asus Launches Specialized Motherboard to Skyrocket China's KX-7000 Clock Speeds by 25%</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/streamline-your-pc-build-with-the-best-motherboards-for-beginners/"><u>Streamline Your PC Build with the Best Motherboards for Beginners</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/supercharge-your-chinese-processor-asus-latest-innovation-in-overclocking-boosts-the-kx-7000-series-by-an-impressive-25/"><u>Supercharge Your Chinese Processor: Asus' Latest Innovation in Overclocking Boosts the KX-7000 Series by an Impressive 25%</u></a></li>
<li><a href="https://buynow-info.techidaily.com/the-ultimate-guide-to-the-cost-effective-amazonbasics-6-sheets-crosscut-shredder-experience/"><u>The Ultimate Guide to the Cost-Effective AmazonBasics 6-Sheets Crosscut Shredder Experience</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-ultimate-list-leading-visual-voicemail-apps-ranked/"><u>The Ultimate List: Leading Visual Voicemail Apps Ranked</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/the-ultimate-resource-for-tech-enthusiasts-toms-computer-equipment-reviews/"><u>The Ultimate Resource for Tech Enthusiasts: Tom's Computer Equipment Reviews</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/the-ultimate-source-for-computer-enthusiasts-tips-and-reviews-on-toms-hardware/"><u>The Ultimate Source for Computer Enthusiasts: Tips & Reviews on Tom's Hardware</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/toms-gadget-galaxy-unveiling-the-secrets-of-high-performance-hardware/"><u>Tom's Gadget Galaxy - Unveiling the Secrets of High-Performance Hardware</u></a></li>
<li><a href="https://some-tips.techidaily.com/unveiling-the-hidden-changes-in-my-google-cloud-storage-strategy-insights-and-impact-a-zdnet-expose/"><u>Unveiling the Hidden Changes in My Google Cloud Storage Strategy: Insights & Impact - A ZDNet Expose</u></a></li>
</ul></div>

