---
title: Ultimate Guide to Choosing the Perfect Laptop Chiller for Your Setup - Latest Picks of 2024 | PCMag
date: 2025-01-09T17:17:21.010Z
updated: 2025-01-13T00:29:58.039Z
tags:
  - mobile-accessories
categories:
  - tech
thumbnail: https://thmb.techidaily.com/4d611c850bdcc5debbd6a1052184df209b3a831159d406c41f1b205c0d3edd38.jpg
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/grbt-5VvbuI?si=qnoirlmljslpqcQj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to transform a Flipper Zero into an Apple AirTag

**What you'll** **need**: A Flipper Zero, an Apple AirTag (or [tracker from another brand](https://www.zdnet.com/article/best-bluetooth-tracker/)), an [iPhone](https://www.zdnet.com/article/best-iphone/) and an [Android phone](https://www.zdnet.com/article/best-android-phone/).

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kTHQrw8e1gk?si=gTPIa7KjhSZ0Vz97" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Install Momentum firmware

First, install the Momentum firmware on your Flipper Zero. The most straightforward method is to use the web installer, but rest assured, you can revert to the stock firmware at any point [using the desktop or mobile app](https://flipperzero.one/downloads). Simply navigate to the [Momentum web installer page](https://momentum-fw.dev/update/), connect your Flipper Zero, and follow the prompts.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6KXVWj6Ar1M?si=Cd_jktmoN3e9OzH3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Downloading FindMy Flipper

Once installed, you'll discover a host of new applications on your Flipper Zero, including one named **FindMy Flipper**. This app was developed and [built by cybersecurity engineer Matthew KuKanich](https://github.com/MatthewKuKanich/FindMyFlipper).

**Also: [Flipper Zero: 'Can you really hack Wi-Fi networks?' and other questions answered](https://www.zdnet.com/home-and-office/flipper-zero-can-you-really-hack-wi-fi-networks-and-other-questions-answered/)**

The app leverages the Flipper Zero's Bluetooth capabilities to act as an Apple AirTag, (or if you prefer, a Samsung SmartTag or Tile tag, but that process is even more cumbersome). It uses the Flipper Zero Bluetooth low energy (BLE) beacon to broadcast a signal that can be picked up by iPhones and sent back to Apple for viewing in the FindMy app.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LT4sdZgUvRQ?si=SvQD5FouEzu4UHpJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Setting up the Flipper Zero

Now brace yourself for the more demanding tasks ahead! But fear not, as Flipper Zero aficionado [The Talking Sasquatch](https://www.youtube.com/@TalkingSasquach) has put together a video tutorial below that lays out the necessary steps in detail.

You'll need an AirTag, an iPhone, and an Android smartphone to follow along.

**Also: [How to unlock the Flipper Zero's true power](https://www.zdnet.com/article/how-to-unlock-the-flipper-zero-true-power/)**

I've personally gone through these steps multiple times and can confirm their effectiveness. But precision is key -- make sure to follow each step meticulously. A single misstep is enough to stop this from working and leave you scratching your head.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/U6lCtLUeROA?si=se6OFuis9JpcTGJf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-learn-the-procedure-for-automatic-video-broadcasting-on-facebook/"><u>[New] In 2024, Learn the Procedure for Automatic Video Broadcasting on Facebook</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-in-2024-captivate-and-enchant-explore-the-best-creative-reactions-on-yt/"><u>[Updated] In 2024, Captivate and Enchant Explore the Best Creative Reactions on YT</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-youtubes-vs-dailymentions-spotting-key-differences/"><u>[Updated] YouTubes Vs. DailyMentions Spotting Key Differences</u></a></li>
<li><a href="https://solve-latest.techidaily.com/54sh5paz44oe44o844or44ks5rs755so44gx44gm5yuv55s744gu44ot44k444ol44ki44or44go44kq44o844oh44kj44kq44ks5a6m55kn44gr44oq44oz44kv44gz44kl5pa55rov/"><u>無料ツールを活用して動画のビジュアルとオーディオを完璧にリンクする方法</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/approval-from-government-agencies-or-planning-commissions-is-typically-required-before-proceeding/"><u>Approval From Government Agencies or Planning Commissions Is Typically Required Before Proceeding.</u></a></li>
<li><a href="https://discover-blog.techidaily.com/dvddvd-shrinkiso/"><u>DVD圧縮時に発生する「DVD Shrinkエラーパラメータ」を修正して、ISOイメージ作成で失敗した場合の解決手順</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/happy-fourth-a-tapestry-of-global-languages/"><u>Happy Fourth: A Tapestry of Global Languages</u></a></li>
<li><a href="https://video-capture.techidaily.com/in-2024-peak-procurement-of-lecture-captures/"><u>In 2024, Peak Procurement of Lecture Captures</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/in-depth-electronics-analysis-by-tom-your-guide-to-top-tech-picks/"><u>In-Depth Electronics Analysis by Tom – Your Guide to Top Tech Picks</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/mastering-gadgets-with-tom-a-hardware-journey/"><u>Mastering Gadgets with Tom - A Hardware Journey</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/mastering-gadgets-with-toms-hardware-hub/"><u>Mastering Gadgets with Tom's Hardware Hub</u></a></li>
<li><a href="https://win-awesome.techidaily.com/mastering-mac-a-step-by-step-guide-to-changing-your-command-key-settings/"><u>Mastering Mac: A Step-by-Step Guide to Changing Your Command Key Settings</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/navigating-through-raspberry-pis-enhanced-speed-and-capacity-insights-from-our-in-depth-analysis-of-the-m2-hatplus/"><u>Navigating Through Raspberry Pi's Enhanced Speed and Capacity: Insights From Our In-Depth Analysis of the M.2 HAT+</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/1723341683638-teamgroups-eco-ddr5-revolution-the-vulcan-memory-kit-ddr5-6000-c30-2x16gb-reviewed/"><u>TeamGroup's Eco-DDR5 Revolution: The Vulcan Memory Kit - DDR5-6000 C30, 2X16GB Reviewed!</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/the-game-changer-amd-ryzen-5-9600x-and-ryzen-7-9700xs-superior-gaming-capabilities-in-zen-5-era/"><u>The Game Changer: AMD Ryzen 5 9600X & Ryzen 7 9700X's Superior Gaming Capabilities in Zen 5 Era</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/unveiling-the-best-electronics-with-toms-hardware-guidance/"><u>Unveiling the Best Electronics with Tom's Hardware Guidance</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/unveiling-the-power-of-the-logitech-g-pro-x-2-lightspeed-the-ultimate-review-for-gamers-perfection/"><u>Unveiling the Power of the Logitech G Pro X 2 Lightspeed: The Ultimate Review for Gamers' Perfection</u></a></li>
<li><a href="https://win-able.techidaily.com/valorant-performance-optimization-eliminate-stutters-and-increase-frame-rates/"><u>Valorant Performance Optimization: Eliminate Stutters & Increase Frame Rates</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/why-is-ipogo-not-working-on-infinix-hot-40-fixed-drfone-by-drfone-virtual-android/"><u>Why is iPogo not working On Infinix Hot 40? Fixed | Dr.fone</u></a></li>
</ul></div>

