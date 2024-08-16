---
title: Performance Insights and Benchmarking of ASRock's Compact Wi-Fi Solution - Z790I Lightning
date: 2024-08-15T00:38:45.799Z
updated: 2024-08-16T00:38:45.799Z
tags:
  - review
categories:
  - hardware
thumbnail: https://cdn.mos.cms.futurecdn.net/dgYKaemY3PS7D3Mdz95k8o-320-80.jpg
---

## Expert Analysis: Raspberry Pi 5 Enhanced by Pi 52'S Cooling Tower - Speedy Performance Uncovered

It's summer in the northern hemisphere, and that brings the heat! The problem is that our Raspberry Pi 5 is already running hot, so we need to keep our Pi 5 cool. 52Pi has a range of coolers. From the original[Ice Tower](https://www.tomshardware.com/raspberry-pi/52-pi-ice-tower-cooler-for-raspberry-pi-5-review) to the monstrous[water cooling kit](https://www.tomshardware.com/raspberry-pi/water-cooling-kit-for-raspberry-pi-5-review) . But its latest cooler fits somewhere in between.

![52Pi Ice Tower Plus](https://cdn.mos.cms.futurecdn.net/5ktRgnyFJNokMwTYZJYExZ-320-80.jpg)

 (Image credit: Tom's Hardware)

 The $20 Ice Tower Plus, as you would guess from its name, is a larger version of the Ice Tower. Sporting a 60mm fan, the Ice Tower Plus dominates the Raspberry Pi 5 but is it any good? Can we access the GPIO and connect cameras and PCIe devices? Let's find out!

## Ice Tower Plus for Raspberry Pi 5 Specifications

 Swipe to scroll horizontally

| Cooling      | Passive cooling fins (62 x 60 x 21mm) 60mm PWM fan.                                                                                                                | Row 0 - Cell 2 |
| ------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------------- |
| Construction | Aluminum heatsink and fan assembly Aluminum block to PMIC and Wi-Fi chip Copper heat pipes to SoC Thermal pad on SoC and PMIC Aluminum framework to support cooler | Row 1 - Cell 2 |
| Port Access  | Access to all ports Camera / Display ports are tight                                                                                                               | Row 2 - Cell 2 |
| Dimensions   | 75 x 66 x 55 mm (Assembled)                                                                                                                                        | Row 3 - Cell 2 |

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296685&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2022/video-pp/ScreenshotSlider/Nero-Video-Advanced-editing.JPG" border="0">Simple and intuitive video editing
🎬 Nero Video:
The powerful video editing program for your Windows PC</a>
<!-- affiliate ads end -->
## Ice Tower Plus Design

![52Pi Ice Tower Plus](https://cdn.mos.cms.futurecdn.net/nB5Vp8M39LATqiTsFLTh6Z-320-80.jpg)
<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872456/14483" target="_top" id="1872456"><img src="//a.impactradius-go.com/display-ad/14483-1872456" border="0" alt="" width="500" height="375"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872456/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 (Image credit: Tom's Hardware)

 The 60mm fan dominates the design. Facing towards the GPIO, this fan is quiet in operation and pulls air over the 62 x 60 x 21mm aluminum fins that are wrapped around the copper heatpipes.

 The good news here is that 52Pi has redesigned the aluminum block that now touches the PMIC (Power Management IC), Wi-Fi package and the all important SoC (System on Chip.) The previous mode, the 52Pi Ice Tower Cooler only cooled the SoC, leaving the PMIC to get rather warm.

 LATEST VIDEOS FROM tomshardware Tom's Hardware

![52Pi Ice Tower Plus](https://cdn.mos.cms.futurecdn.net/Xi2eXwTB8eYXzF8SHeLtmb-320-80.jpg)
<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/517826/4704" target="_top" id="517826"><img src="//a.impactradius-go.com/display-ad/4704-517826" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/517826/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 (Image credit: Tom's Hardware)

 Connecting to the dedicated fan power connector, the 52Pi Ice Tower Plus works just like the official Raspberry Pi Active Cooler. Activating at 50 degrees Celsius, the fan eschews RGB in favor of just getting on with the job. There is an additional thermal pad and aluminum slab that resides underneath the Raspberry Pi 5\.

 The unit is held together with a series of aluminum brackets and M2.5 screw mounts. It was easy to build, and the trickiest part was inserting the fan power cable after installing the fan. The instructions were decent, but there wasn’t an instruction to add a thermal pad to the PMIC chip, just next to the USB C port. We did this anyway and there have been no thermal issues.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097467/26400?prodsku=B700" target="_top" id="2097467"><img src="//a.impactradius-go.com/display-ad/26400-2097467" border="0" alt="" width="640" height="640"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097467/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Port Access

 Image 1 of 5

![52Pi Ice Tower Plus](https://vanilla.futurecdn.net/cyclingnews/media/img/missing-image.svg)

 (Image credit: Tom's Hardware)

![52Pi Ice Tower Plus](https://vanilla.futurecdn.net/cyclingnews/media/img/missing-image.svg)

 (Image credit: Tom's Hardware)

![52Pi Ice Tower Plus](https://vanilla.futurecdn.net/cyclingnews/media/img/missing-image.svg)
<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4081991&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->

 (Image credit: Tom's Hardware)

![52Pi Ice Tower Plus](https://vanilla.futurecdn.net/cyclingnews/media/img/missing-image.svg)

 (Image credit: Tom's Hardware)

![52Pi Ice Tower Plus](https://vanilla.futurecdn.net/cyclingnews/media/img/missing-image.svg)

 (Image credit: Tom's Hardware)

 The elephant in the room, big fans mean restricted GPIO access. You won’t be putting the best Raspberry Pi HATs directly onto your Pi. You’ll need a breakout board such as Pimoroni’s Black Hat Hacker in order to use any add-on boards.

 Accessing the GPIO pins individually, for breadboarding, is easy enough. Just make sure that any wires are clear of the fan. Access to the camera / display ports is awkward, but achievable. You’ll need a thin tool to lever the locking clasps, but inserting the flat flex cable is easy enough. The PCIe port is another story. You can just access this connector, but small hands or patience will be needed. With more and more PCIe based boards coming out, this lack of access could become a key decision for makers. Obviously with a huge fan on top of the Pi, you won’t be able to mount any PCIe boards on top. Likewise the aluminum slab makes tricky work of mounting a board under the Pi. You could get longer screws and mount Pimoroni’s NVMe Base, NVMe Base Duo and Pineboards Hat Drive Bottom under the Pi. Just check your clearances.

## Thermal Performance

 Image 1 of 2

![52Pi Ice Tower Plus](https://vanilla.futurecdn.net/cyclingnews/media/img/missing-image.svg)

 (Image credit: Tom's Hardware)

![52Pi Ice Tower Plus](https://vanilla.futurecdn.net/cyclingnews/media/img/missing-image.svg)

 (Image credit: Tom's Hardware)

 A bigger fan and more aluminum means that the Ice Tower Plus is a much better cooling option than the original Ice Tower. We re-tested the original Ice Tower, given that it is so hot in the UK right now.

 Our standard benchmark test takes seven minutes and it first establishes the idle temperature of the Raspberry Pi 5 over a one minute period. Then using the stress command we run all four cores at maximum for five minutes. Finally we let the Raspberry Pi cooldown for a final one minute. We conducted two benchmark tests per Raspberry Pi 5\. The first was at stock speed, the second saw the Pi 5 overclocked to 3 GHz.

 Swipe to scroll horizontally

| Header Cell - Column 0 | 52Pi Ice Tower Plus | 52Pi Ice Tower |
| ---------------------- | ------------------- | -------------- |
| Stock - Idle           | 32.9                | 35.6           |
| Stock - Stress         | 49.9                | 60.4           |
| 3GHz - Idle            | 35.6                | 35.7           |
| 3GHz - Stress          | 51.6                | 68.1           |

 Here is a quick reference table. As you can see, the 52Pi Ice Tower Plus at stock speed is pretty close to the original Ice Tower. Only 2.7 degrees Celsius separates them, but the lower temperature award goes to the Ice Tower Plus at 32.9°C.

![52Pi Ice Tower Plus](https://cdn.mos.cms.futurecdn.net/q6Nk4pfdGX96JVKVLsYzRT-320-80.png)

 (Image credit: Tom's Hardware)

 Under stress, the Ice Tower Plus is a full 10.5°C cooler than the older model. At 49.9°C (versus 60.4°C) the Ice Tower Plus is just under the trigger temperature which starts the fan. The older Ice Tower relies on the fan to move cooler air over the smaller aluminum fins which of course have a lower thermal mass.

 But what about overclocking the Raspberry Pi 5 to 3 GHz. The Ice Tower Plus has no problem keeping the Pi 5 cool at stock and under stress. There was only 1.1°C between the two, in the favor of the Ice Tower Plus which idled at 35.6°C, versus the Ice Tower’s 36.7°C. But that mere 1.1°C difference is nothing compared to the Ice Tower Plus’ remarkable max stress test temperature of 51.6°C. Compared to the Ice Tower’s 68.1°C this represents a remarkable 16.5°C drop in temperature, just over the 50°C fan trigger point.

![52Pi Ice Tower Plus](https://cdn.mos.cms.futurecdn.net/5ktRgnyFJNokMwTYZJYExZ-320-80.jpg)
<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920054/21774" target="_top" id="1920054"><img src="//a.impactradius-go.com/display-ad/21774-1920054" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920054/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 (Image credit: Tom's Hardware)

 So is this the best cooler for the Raspberry Pi 5? No it isn’t. But if you want the best cooling, then you need to pay big bucks. The best cooling on a Raspberry Pi 5 comes from another 52Pi product, its[water cooling kit](https://www.tomshardware.com/raspberry-pi/water-cooling-kit-for-raspberry-pi-5-review) which retails for over $120! That kit keeps an idling, stock Raspberry Pi 5 cool to 24.1°C, and under stress it only hits 38.9°C! Overclocking to 3GHz, idle is still 24.1°C and stress temperature is only 44.4°C.

 The best comparison in the price bracket is[Argon’s THRML 60-RC](https://www.tomshardware.com/raspberry-pi/argon-thrml-60-rc-review) which also uses a 60mm fan.. At stock speed, this cooler keeps the Pi 5 cool to 30.7°C and under stress only hits 46.1°C. Overclocked to 3GHz it only reaches 50.5°C.

 Between the 52Pi and Argon, which would we buy? The Argon THRML 60-RC. Just because PCIe access is much easier.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3922934&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/ripperpro.png" border="0">WonderFox DVD Ripper Pro</a>
<!-- affiliate ads end -->
## Bottom Line

![52Pi Ice Tower Plus](https://cdn.mos.cms.futurecdn.net/CKwoV3k8pmHCMdT6Q5pREe-320-80.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.dbschema.com/order/checkout.php?PRODS=19867419&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/176b22bab4e94a28619ca2433b2ef241/products/1_icon256.png" border="0">
DbSchema database designer for all databases, schema design in the team, schema deployment, interactive diagrams, documentation, data and query tools. </a>
<!-- affiliate ads end -->

 (Image credit: Tom's Hardware)

 The 52Pi Ice Tower Plus is a great cooler and for $20 you’ll get plenty of cooling power for your dollars. The thing is, the Argon THRML 60-RC is the same price and it performs just a little bit better and has improved PCIe access. It boils down to price and availability. At the time of writing, the Ice Tower Plus is on sale for $16\. We can take a performance hit (only a few degrees) to save a few bucks.

 If you can get it cheap, go for the 52Pi Ice Tower Plus. Otherwise it is your choice on this or the Argon THRML 60-RC.


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
<li><a href="https://youtube-docs.techidaily.com/024-approved-convenient-method-to-design-original-shorts-thumbnails/"><u>[New] 2024 Approved  Convenient Method to Design Original Shorts Thumbnails</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-navigating-through-mixed-reality-an-overview/"><u>[New] Navigating Through Mixed Reality  An Overview</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-insta-followers-footprints-trail-blazing-techniques/"><u>[Updated] In 2024, Insta Followers Footprints  Trail-Blazing Techniques</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-rhythmic-rarities-assembling-the-best-dj-video-samples-for-2024/"><u>[Updated] Rhythmic Rarities  Assembling the Best DJ Video Samples for 2024</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/advanced-computing-solutions-decoded-inside-look-with-toms-hardware/"><u>Advanced Computing Solutions Decoded – Inside Look with Tom's Hardware</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/comprehensive-akasa-gecko-ssd-cooling-system-evaluation-an-exhaustive-analysis-of-the-blower-heatsink/"><u>Comprehensive Akasa Gecko SSD Cooling System Evaluation: An Exhaustive Analysis of the Blower Heatsink</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/comprehensive-guide-to-the-asus-rog-nuc-tier-review-unmatched-performance-within-compact-design/"><u>Comprehensive Guide to the Asus ROG NUC Tier Review: Unmatched Performance Within Compact Design</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/cost-effective-microcontroller-projects-with-the-cytron-maker-uno-rp2040-a-comprehensive-review/"><u>Cost-Effective Microcontroller Projects with the Cytron Maker Uno RP2040 - A Comprehensive Review</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/cutting-edge-cost-effective-nvme-cooling-discover-the-power-of-the-uphere-m201-heatsink-under-5/"><u>Cutting-Edge, Cost-Effective NVMe Cooling - Discover the Power of the UpHere M201 Heatsink Under $5!</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/discover-the-best-of-both-worlds-with-keychron-q1-he-a-hybrid-desktopwireless-marvel/"><u>Discover the Best of Both Worlds with Keychron Q1 HE - A Hybrid Desktop/Wireless Marvel</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/discover-the-latest-in-computing-dive-into-toms-hardware-universe/"><u>Discover the Latest in Computing - Dive Into Tom's Hardware Universe</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/evaluating-the-uphere-c5cd6sec-air-coolers-impressive-budget-friendly-options/"><u>Evaluating the UpHere C5C/D6Sec Air Coolers: Impressive Budget-Friendly Options</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/experience-unmatched-performance-with-the-titan-army-p27a2r-gaming-display-at-180-hz/"><u>Experience Unmatched Performance with the Titan Army P27A2R Gaming Display at 180 Hz</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/1723341704660-expert-analysis-of-id-cooling-fx360-pro-cpu-cooler-great-performance-at-only-60/"><u>Expert Analysis of ID-Cooling FX360 Pro Cpu Cooler - Great Performance at Only $60</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/expert-gear-review-at-tomtechspotlight/"><u>Expert Gear Review at TomTechSpotlight</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/expert-hardware-insights-from-toms-technology-hub/"><u>Expert Hardware Insights From Tom's Technology Hub</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/exploring-the-dell-xps-13-9n45-timeless-design-and-enhanced-performance-via-snapdragon-x-elite/"><u>Exploring the Dell XPS 13 (9N45): Timeless Design and Enhanced Performance via Snapdragon X Elite</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/hostinger-evaluation-comparing-vps-cloud-and-shared-web-hosting-services/"><u>Hostinger Evaluation: Comparing VPS, Cloud, and Shared Web Hosting Services</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-top-15-apps-to-hack-wifi-password-on-poco-by-drfone-android/"><u>In 2024, Top 15 Apps To Hack WiFi Password On Poco</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/in-depth-review-of-pny-rp6-1tb-ssd-satisfactory-performance-with-no-notable-highlights/"><u>In Depth Review of PNY RP6# 1TB SSD: Satisfactory Performance with No Notable Highlights</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/in-depth-analysis-of-beyerdynamic-mmx-30e-pro-impressive-acoustics-meets-simple-design/"><u>In-Depth Analysis of Beyerdynamic MMX 30E Pro - Impressive Acoustics Meets Simple Design</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/mastering-gadgets-and-components-through-toms-specialized-lens/"><u>Mastering Gadgets and Components Through Tom's Specialized Lens</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/mastering-gadgets-with-tom-a-comprehensive-hardware-review-site/"><u>Mastering Gadgets with Tom - A Comprehensive Hardware Review Site</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-2024-approved-elevate-your-online-communication-the-best-skype-voice-changing-technologies/"><u>New 2024 Approved Elevate Your Online Communication The Best Skype Voice Changing Technologies</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/pope-francis-digital-correspondence-is-he-active-on-emails/"><u>Pope Francis' Digital Correspondence: Is He Active on Emails?</u></a></li>
<li><a href="https://techidaily.com/repair-damaged-unplayable-video-files-of-g54-5g-on-mac-by-stellar-video-repair-mobile-video-repair/"><u>Repair damaged, unplayable video files of G54 5G on Mac</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/revolutionize-your-typing-experience-with-the-keychron-q1-he-a-comprehensive-review-of-the-ultimate-wireless-mechanical-keyboard/"><u>Revolutionize Your Typing Experience with the Keychron Q1-HE: A Comprehensive Review of the Ultimate Wireless Mechanical Keyboard</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/spotlight-innovative-tiktok-expressions/"><u>Spotlight  Innovative TikTok Expressions</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/tech-enthusiasts-rejoice-master-your-devices-with-toms-hardware-insights/"><u>Tech Enthusiasts Rejoice: Master Your Devices With Tom's Hardware Insights</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/the-future-of-resin-3d-printing-with-elegoos-saturn-4-ultra-a-detailed-review-exploring-its-technological-advancements/"><u>The Future of Resin 3D Printing with Elegoo's Saturn 4 Ultra - A Detailed Review Exploring Its Technological Advancements</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/the-melodic-brilliance-of-blueant-soundblade-an-in-depth-look-at-its-volume-and-aesthetics/"><u>The Melodic Brilliance of BlueAnt Soundblade - An In-Depth Look at Its Volume & Aesthetics</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/the-safe-bet-of-computing-an-insight-into-nzxts-h7-flow-case/"><u>The Safe Bet of Computing: An Insight Into NZXT's H7 Flow Case</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/the-ultimate-tech-resource-toms-hardware-unveiled/"><u>The Ultimate Tech Resource - Tom's Hardware Unveiled</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/toms-gear-guidance-your-go-to-source-for-computer-insights/"><u>Tom's Gear Guidance: Your Go-To Source for Computer Insights</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/toms-tech-insights-comprehensive-hardware-guides/"><u>Tom's Tech Insights: Comprehensive Hardware Guides</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/toms-tech-insights-expert-reviews-and-guides/"><u>Tom's Tech Insights: Expert Reviews and Guides</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/travel-companion-analysis-asus-rt-ax52018-a-comprehensive-look-at-the-ultra-portable-wireless-nano-router/"><u>Travel Companion Analysis: Asus RT-AX5^2018 - A Comprehensive Look at the Ultra-Portable Wireless Nano Router</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/unleashing-superior-data-transfer-a-review-of-cost-effective-raspberry-pi-m2-hatplus/"><u>Unleashing Superior Data Transfer: A Review of Cost-Effective Raspberry Pi M.2 HAT+</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/unveiling-tech-secrets-the-ultimate-companion-to-toms-gear-advice/"><u>Unveiling Tech Secrets: The Ultimate Companion to Tom's Gear Advice</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/unveiling-the-best-pc-upgrades-insights-from-toms-hardware-experts/"><u>Unveiling the Best PC Upgrades: Insights From Tom's Hardware Experts</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/unveiling-the-best-a-comprehensive-review-of-the-corsair-e27t-ssd-the-ultimate-1tb-m2-solution/"><u>Unveiling the Best: A Comprehensive Review of the Corsair E27T SSD - The Ultimate 1TB M.2 Solution</u></a></li>
<li><a href="https://fox-that.techidaily.com/whatsapp-not-backing-up-to-icloud-heres-how-to-fix-it/"><u>WhatsApp Not Backing Up to iCloud? Here's How to Fix It</u></a></li>
</ul></div>
