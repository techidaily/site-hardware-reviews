---
title: "2024'S Ultimate Selection of Car Charger Sticks: Find the Best Pick for Your Journey | CNET"
date: 2025-01-11T01:00:11.926Z
updated: 2025-01-12T17:24:41.605Z
tags:
  - mobile-accessories
categories:
  - tech
thumbnail: https://thmb.techidaily.com/d04a298cb4efeef55fca68d7eaf14aa0f3c43f69fcef497082e91bf17afd4582.jpg
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/g6xXIR_Uh1A?si=TMXzklPEY50MUM05" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to transform a Flipper Zero into an Apple AirTag

**What you'll** **need**: A Flipper Zero, an Apple AirTag (or [tracker from another brand](https://www.zdnet.com/article/best-bluetooth-tracker/)), an [iPhone](https://www.zdnet.com/article/best-iphone/) and an [Android phone](https://www.zdnet.com/article/best-android-phone/).

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_SbYznUy_zY?si=ThBkP934r3mizi48" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Install Momentum firmware

First, install the Momentum firmware on your Flipper Zero. The most straightforward method is to use the web installer, but rest assured, you can revert to the stock firmware at any point [using the desktop or mobile app](https://flipperzero.one/downloads). Simply navigate to the [Momentum web installer page](https://momentum-fw.dev/update/), connect your Flipper Zero, and follow the prompts.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/oeSN3u4fO9M?si=Ua3Hzcil6u6akDgY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Downloading FindMy Flipper

Once installed, you'll discover a host of new applications on your Flipper Zero, including one named **FindMy Flipper**. This app was developed and [built by cybersecurity engineer Matthew KuKanich](https://github.com/MatthewKuKanich/FindMyFlipper).

**Also: [Flipper Zero: 'Can you really hack Wi-Fi networks?' and other questions answered](https://www.zdnet.com/home-and-office/flipper-zero-can-you-really-hack-wi-fi-networks-and-other-questions-answered/)**

The app leverages the Flipper Zero's Bluetooth capabilities to act as an Apple AirTag, (or if you prefer, a Samsung SmartTag or Tile tag, but that process is even more cumbersome). It uses the Flipper Zero Bluetooth low energy (BLE) beacon to broadcast a signal that can be picked up by iPhones and sent back to Apple for viewing in the FindMy app.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zAzTErKy6h8?si=vi5z3M9_7fW6qiAJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Setting up the Flipper Zero

Now brace yourself for the more demanding tasks ahead! But fear not, as Flipper Zero aficionado [The Talking Sasquatch](https://www.youtube.com/@TalkingSasquach) has put together a video tutorial below that lays out the necessary steps in detail.

You'll need an AirTag, an iPhone, and an Android smartphone to follow along.

**Also: [How to unlock the Flipper Zero's true power](https://www.zdnet.com/article/how-to-unlock-the-flipper-zero-true-power/)**

I've personally gone through these steps multiple times and can confirm their effectiveness. But precision is key -- make sure to follow each step meticulously. A single misstep is enough to stop this from working and leave you scratching your head.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jf0JvOqiAXc?si=kHEHQGC_PhBv4xij" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-access.techidaily.com/new-magix-acid-pro-critique-and-comparable-products-for-2024/"><u>[New] Magix ACID Pro Critique & Comparable Products for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-exclusive-top-5-list-of-fb-video-downloaders/"><u>[Updated] Exclusive TOP 5 List of FB Video Downloaders</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-live-broadcasts-in-focus-scrutinizing-the-best-6-microphones-available/"><u>[Updated] Live Broadcasts in Focus Scrutinizing the Best 6 Microphones Available</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-optimizing-trailer-vibes-the-melody-essentials/"><u>2024 Approved Optimizing Trailer Vibes The Melody Essentials</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/adherence-to-prescribed-medications-such-as-antibiotics-and-anti-inflammatory-eye-drops-is-essential-to-prevent-complications/"><u>Adherence to Prescribed Medications, Such as Antibiotics and Anti-Inflammatory Eye Drops, Is Essential to Prevent Complications</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/expert-insights-from-toms-technology-reviews-hardware-and-more/"><u>Expert Insights From Tom's Technology Reviews: Hardware and More</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/exploring-technology-with-tom-in-depth-hardware-insights/"><u>Exploring Technology with Tom: In-Depth Hardware Insights</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-tips-and-tricks-for-apple-id-locked-issue-on-apple-iphone-13-by-drfone-ios/"><u>In 2024, Tips and Tricks for Apple ID Locked Issue On Apple iPhone 13</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-top-apps-and-online-tools-to-track-lenovo-thinkphone-phone-withwithout-imei-number-by-drfone-android/"><u>In 2024, Top Apps and Online Tools To Track Lenovo ThinkPhone Phone With/Without IMEI Number</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/in-depth-corsair-mp600-mini-1tb-m2-2280e27t-ssd-evaluation-top-of-the-line-performance-in-a-compact-form-factor/"><u>In-Depth Corsair MP600 Mini 1TB (M.2 2280/E27T) SSD Evaluation: Top of the Line Performance in a Compact Form Factor</u></a></li>
<li><a href="https://fake-location.techidaily.com/life360-learn-how-everything-works-on-tecno-pop-8-drfone-by-drfone-virtual-android/"><u>Life360 Learn How Everything Works On Tecno Pop 8 | Dr.fone</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/navigating-hardware-with-tom-insights-and-reviews-by-toms-gear/"><u>Navigating Hardware with Tom: Insights & Reviews by Tom's Gear</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/navigating-the-world-of-high-tech-tools-at-toms-hardware-hub/"><u>Navigating the World of High-Tech Tools at Tom's Hardware Hub</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/stay-chilled-with-the-uphere-m201-top-notch-nvme-ssd-cooler-for-a-steal-at-5/"><u>Stay Chilled with the UpHere M201: Top-Notch NVMe SSD Cooler for a Steal at $5!</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/top-10-password-cracking-tools-for-honor-x9b-by-drfone-android/"><u>Top 10 Password Cracking Tools For Honor X9b</u></a></li>
<li><a href="https://fox-that.techidaily.com/what-to-do-when-safari-cant-take-full-page-shots-tips-for-swift-fixes-and-solutions/"><u>What to Do When Safari Can't Take Full-Page Shots: Tips for Swift Fixes and Solutions</u></a></li>
</ul></div>

