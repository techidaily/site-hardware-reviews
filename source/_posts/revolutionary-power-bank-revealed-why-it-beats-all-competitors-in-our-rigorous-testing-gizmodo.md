---
title: "Revolutionary Power Bank Revealed: Why It Beats All Competitors in Our Rigorous Testing | Gizmodo"
date: 2025-01-10T00:14:04.987Z
updated: 2025-01-12T23:37:59.934Z
tags:
  - mobile-accessories
categories:
  - tech
thumbnail: https://thmb.techidaily.com/0f935ebe417d47bcf2165f433dd2058985bf2be660072717b5b9a5f64bf35952.jpg
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/gOyLy8DeizY?si=GkAmK0hChZw6_2tW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to transform a Flipper Zero into an Apple AirTag

**What you'll** **need**: A Flipper Zero, an Apple AirTag (or [tracker from another brand](https://www.zdnet.com/article/best-bluetooth-tracker/)), an [iPhone](https://www.zdnet.com/article/best-iphone/) and an [Android phone](https://www.zdnet.com/article/best-android-phone/).

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fHWdQw1gRyI?si=ve9wZnPupiooLThG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Install Momentum firmware

First, install the Momentum firmware on your Flipper Zero. The most straightforward method is to use the web installer, but rest assured, you can revert to the stock firmware at any point [using the desktop or mobile app](https://flipperzero.one/downloads). Simply navigate to the [Momentum web installer page](https://momentum-fw.dev/update/), connect your Flipper Zero, and follow the prompts.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/epKTCSREjhI?si=Ez_hObK1FZrmEE7f" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Downloading FindMy Flipper

Once installed, you'll discover a host of new applications on your Flipper Zero, including one named **FindMy Flipper**. This app was developed and [built by cybersecurity engineer Matthew KuKanich](https://github.com/MatthewKuKanich/FindMyFlipper).

**Also: [Flipper Zero: 'Can you really hack Wi-Fi networks?' and other questions answered](https://www.zdnet.com/home-and-office/flipper-zero-can-you-really-hack-wi-fi-networks-and-other-questions-answered/)**

The app leverages the Flipper Zero's Bluetooth capabilities to act as an Apple AirTag, (or if you prefer, a Samsung SmartTag or Tile tag, but that process is even more cumbersome). It uses the Flipper Zero Bluetooth low energy (BLE) beacon to broadcast a signal that can be picked up by iPhones and sent back to Apple for viewing in the FindMy app.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/8Y-k_3N-0OI?si=1J-aFBXLJl5b3x4h" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Setting up the Flipper Zero

Now brace yourself for the more demanding tasks ahead! But fear not, as Flipper Zero aficionado [The Talking Sasquatch](https://www.youtube.com/@TalkingSasquach) has put together a video tutorial below that lays out the necessary steps in detail.

You'll need an AirTag, an iPhone, and an Android smartphone to follow along.

**Also: [How to unlock the Flipper Zero's true power](https://www.zdnet.com/article/how-to-unlock-the-flipper-zero-true-power/)**

I've personally gone through these steps multiple times and can confirm their effectiveness. But precision is key -- make sure to follow each step meticulously. A single misstep is enough to stop this from working and leave you scratching your head.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/S0b9szh8vEk?si=NlGzpJ6MN_SJNk5A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://vp-tips.techidaily.com/new-effortless-image-editing-picart-background-removal/"><u>[New] Effortless Image Editing PicArt Background Removal</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-10-innovative-screencasting-solutions-for-modern-teachers/"><u>[Updated] 10 Innovative Screencasting Solutions for Modern Teachers</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-advanced-ai-for-professional-photography-for-2024/"><u>[Updated] Advanced AI for Professional Photography for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-clip-weaver-workshop-for-2024/"><u>[Updated] Clip Weaver Workshop for 2024</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-your-path-to-metaverse-dominance-with-7-key-devices-for-2024/"><u>[Updated] Your Path to Metaverse Dominance with 7 Key Devices for 2024</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/1723862716225-ace-gamers-deal-the-ultimate-combo-of-power-and-savings-msi-bravo-laptop-with-rtx-4060-under-1k/"><u>Ace Gamers’ Deal: The Ultimate Combo of Power and Savings - MSI Bravo Laptop with RTX 4060 Under $1K</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/asus-rog-zephyrus-g14-rtx-4060-steals-show-with-a-sizzling-1099-offer-only-at-best-buy/"><u>Asus ROG Zephyrus G14 RTX 4060 Steals Show with a Sizzling $1,099 Offer Only at Best Buy</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/asus-zenbook-s16-review-an-insightful-look-at-its-performance-powered-by-amd-ryzen-ai-9-hx-370/"><u>Asus Zenbook S16 Review: An Insightful Look at Its Performance Powered by AMD Ryzen AI 9 HX 370</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/benzalkonium-chloride-commonly-found-in-hand-sanitizers-its-a-quaternary-ammonium-compound-effective-against-bacteria-and-some-viruses-however-its-effective32/"><u>Benzalkonium Chloride - Commonly Found in Hand Sanitizers, It's a Quaternary Ammonium Compound Effective Against Bacteria and some Viruses. However, Its Effectiveness Can Be Reduced by Organic Matter Like Blood or Dirt.</u></a></li>
<li><a href="https://solve-news.techidaily.com/1725284517391-blu-ray/"><u>Blu-Rayディスク使用ガイド: 役立つ知識と再生・変換手順</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/breakthrough-in-laptop-technology-the-worlds-first-thinkpad-p1-gen-7-with-advanced-lpcamm2-memory-uncompromising-speed-and-slim-profile-redefined/"><u>Breakthrough in Laptop Technology: The World's First ThinkPad P1 Gen 7 with Advanced LPCAMM2 Memory – Uncompromising Speed and Slim Profile Redefined</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/experience-cutting-edge-laptop-performance-the-1100-honor-magicbook-art-n14-with-meteor-lake-cpu-and-removable-camera/"><u>Experience Cutting-Edge Laptop Performance: The $1,100 Honor MagicBook Art N14 with Meteor Lake CPU & Removable Camera</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/1723862735316-experience-next-level-gaming-the-lenovo-legion-slim-5-boosted-by-the-powerful-rtx-4060-gpu-all-for-only-899/"><u>Experience Next-Level Gaming: The Lenovo Legion Slim 5, Boosted by the Powerful RTX 4060 GPU - All For Only $899</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-change-lock-screen-wallpaper-on-vivo-x100-pro-by-drfone-android/"><u>In 2024, How to Change Lock Screen Wallpaper on Vivo X100 Pro</u></a></li>
<li><a href="https://tech-hub.techidaily.com/revealing-truth-behind-winchatgpt-extension/"><u>Revealing Truth Behind WinChatGPT Extension</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/1723862736044-score-a-bargain-16-inch-macbook-pro-w-m3-chip-at-discounted-prices-pre-prime-day/"><u>Score a Bargain: 16-Inch MacBook Pro W/ M3 Chip at Discounted Prices Pre-Prime Day!</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/the-ultimate-guide-to-mac-videos-for-snapchat/"><u>The Ultimate Guide to Mac Videos for Snapchat</u></a></li>
</ul></div>

