---
title: "Perfect Match: Essential Anker Accessories to Enhance Your New iPhone's Experience | ZDNET"
date: 2025-01-12T02:41:33.256Z
updated: 2025-01-12T22:28:41.448Z
tags:
  - mobile-accessories
categories:
  - tech
thumbnail: https://thmb.techidaily.com/f04df6c23b871cbbd0c17b0eb3921c505712d724d4bbb61a362d901e0200289d.jpg
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/GyfJUhsz_AY?si=x2HjoLX1B89oEPgZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to transform a Flipper Zero into an Apple AirTag

**What you'll** **need**: A Flipper Zero, an Apple AirTag (or [tracker from another brand](https://www.zdnet.com/article/best-bluetooth-tracker/)), an [iPhone](https://www.zdnet.com/article/best-iphone/) and an [Android phone](https://www.zdnet.com/article/best-android-phone/).

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/QRaEdFMU-Xc?si=OjaiTvlogJy5wHhN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Install Momentum firmware

First, install the Momentum firmware on your Flipper Zero. The most straightforward method is to use the web installer, but rest assured, you can revert to the stock firmware at any point [using the desktop or mobile app](https://flipperzero.one/downloads). Simply navigate to the [Momentum web installer page](https://momentum-fw.dev/update/), connect your Flipper Zero, and follow the prompts.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XIUatTFH0Zw?si=ZCtoBtIy18y2F5Vc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Downloading FindMy Flipper

Once installed, you'll discover a host of new applications on your Flipper Zero, including one named **FindMy Flipper**. This app was developed and [built by cybersecurity engineer Matthew KuKanich](https://github.com/MatthewKuKanich/FindMyFlipper).

**Also: [Flipper Zero: 'Can you really hack Wi-Fi networks?' and other questions answered](https://www.zdnet.com/home-and-office/flipper-zero-can-you-really-hack-wi-fi-networks-and-other-questions-answered/)**

The app leverages the Flipper Zero's Bluetooth capabilities to act as an Apple AirTag, (or if you prefer, a Samsung SmartTag or Tile tag, but that process is even more cumbersome). It uses the Flipper Zero Bluetooth low energy (BLE) beacon to broadcast a signal that can be picked up by iPhones and sent back to Apple for viewing in the FindMy app.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cC-HtDQVoG0?si=nQcoa7q8q2IL8U0m" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Setting up the Flipper Zero

Now brace yourself for the more demanding tasks ahead! But fear not, as Flipper Zero aficionado [The Talking Sasquatch](https://www.youtube.com/@TalkingSasquach) has put together a video tutorial below that lays out the necessary steps in detail.

You'll need an AirTag, an iPhone, and an Android smartphone to follow along.

**Also: [How to unlock the Flipper Zero's true power](https://www.zdnet.com/article/how-to-unlock-the-flipper-zero-true-power/)**

I've personally gone through these steps multiple times and can confirm their effectiveness. But precision is key -- make sure to follow each step meticulously. A single misstep is enough to stop this from working and leave you scratching your head.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/o-sRtqHdEYY?si=NMTMQVxJsUaoguqh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://instagram-clips.techidaily.com/new-speed-up-instagram-videos-on-desktop-effective-techniques/"><u>[New] Speed Up Instagram Videos on Desktop Effective Techniques</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-2024-approved-maximizing-youtube-earnings-master-the-art-with-500-subscribers/"><u>[Updated] 2024 Approved Maximizing YouTube Earnings Master the Art with 500 Subscribers</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/advanced-computing-tips-from-the-pioneers-at-toms-hardware/"><u>Advanced Computing Tips From the Pioneers at Tom's Hardware</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/affordable-34-curved-asus-tuf-display-now-just-249-on-amazon-gamers-deal/"><u>Affordable 34 Curved ASUS TUF Display Now Just $249 on Amazon – Gamer's Deal!</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/1723862838482-amazons-game-changer-34qhd-lg-ultragear-monitor-with-elite-g-sync-now-at-unbeatable-price-of-549/"><u>Amazon's Game Changer: 34QHD LG Ultragear Monitor with Elite G-Sync, Now at Unbeatable Price of $549!</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/1723862817375-experience-unparalleled-gaming-with-dell-s3222dgm-now-at-an-amazing-price-only-229/"><u>Experience Unparalleled Gaming with Dell S3222DGM: Now at an Amazing Price - Only $229!</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/exploring-advanced-recording-alternatives-to-fbx-frameworks-for-2024/"><u>Exploring Advanced Recording Alternatives to FBX Frameworks for 2024</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-how-to-bypass-google-frp-lock-on-tecno-spark-10c-devices-by-drfone-android/"><u>In 2024, How to Bypass Google FRP Lock on Tecno Spark 10C Devices</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-fix-life360-shows-wrong-location-on-tecno-spark-go-2023-drfone-by-drfone-virtual-android/"><u>In 2024, How to Fix Life360 Shows Wrong Location On Tecno Spark Go (2023)? | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-mastering-mobile-shots-ios-11s-camera-innovations/"><u>In 2024, Mastering Mobile Shots IOS 11'S Camera Innovations</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-top-5-xiaomi-redmi-a2plus-bypass-frp-tools-for-pc-that-actually-work-by-drfone-android/"><u>In 2024, Top 5 Xiaomi Redmi A2+ Bypass FRP Tools for PC That Actually Work</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/1723862841548-level-up-your-game-with-our-top-pick-dell-s3222dgm-gaming-display-now-at-an-all-time-low-grab-it-for-229/"><u>Level Up Your Game with Our Top-Pick Dell S3222DGM Gaming Display Now at an All-Time Low - Grab It for $229!</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/restoring-correct-self-image-amidst-message-distortion/"><u>Restoring Correct Self-Image Amidst Message Distortion</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/1723862838906-score-big-savings-with-a-sharp-fast-paced-gaming-screen-acer-nitro-27-for-under-150/"><u>Score Big Savings with a Sharp, Fast-Paced Gaming Screen – Acer Nitro 27 for Under $150!</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/1723862820475-score-the-best-deal-on-a-high-quality-gaming-screen-get-the-sceptre-24-inch-curved-monitor-at-just-79/"><u>Score the Best Deal on a High-Quality Gaming Screen - Get the Sceptre 24 Inch Curved Monitor at Just $79</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/1723862835548-upgrade-to-a-sharp-27-display-get-the-built-in-webcam-and-pixel-dense-viewfinity-tech-with-samsungs-s9-monitor-for-899-discounted-by-44/"><u>Upgrade to a Sharp 27 Display - Get the Built-In Webcam & Pixel-Dense Viewfinity Tech with Samsung's S9 Monitor for $899, Discounted by 44%!</u></a></li>
<li><a href="https://location-social.techidaily.com/why-your-whatsapp-live-location-is-not-updating-and-how-to-fix-on-your-vivo-v27-pro-drfone-by-drfone-virtual-android/"><u>Why Your WhatsApp Live Location is Not Updating and How to Fix on your Vivo V27 Pro | Dr.fone</u></a></li>
</ul></div>

