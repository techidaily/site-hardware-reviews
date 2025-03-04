---
title: ZDNet Uncovers Anker's Eufy Cameras Miss Native Encryption Feature, Raising Privacy Concerns
date: 2025-02-27T20:59:10.981Z
updated: 2025-03-04T17:10:16.899Z
tags:
  - cyber-threats
categories:
  - tech
thumbnail: https://www.zdnet.com/a/img/resize/b2a4c5e21345ed39cb8b9985e5b75f72b6508c18/2022/12/19/63a4599e-df2e-488f-a066-be8689cf8292/eufy-security-speak-no-emoji.jpg?width=278&height=156&fit=crop&auto=webp
---

## ZDNet Uncovers Anker's Eufy Cameras Miss Native Encryption Feature, Raising Privacy Concerns

![Eufy camera with speak no evil emoji](https://www.zdnet.com/a/img/resize/41634300f1d0dc8fd51717d10c087b282f6e8698/2022/12/19/63a4599e-df2e-488f-a066-be8689cf8292/eufy-security-speak-no-emoji.jpg?auto=webp&width=1280)

DALL-E/Maria Diaz/ZDNET

[Eufy Security](https://www.anrdoezrs.net/links/9041660/type/dlg/sid/zd-%5F%5FCOM%5FCLICK%5FID%5F%5F-dtp/https://us.eufy.com/collections/security) has remained mostly silent since [security flaws were uncovered](https://www.zdnet.com/article/eufys-security-cameras-send-data-to-the-cloud-without-consent-and-thats-not-the-worst-part/) in its system, which made a lot of users understandably unhappy and many began wondering if they could even trust Eufy security cameras. But now, that's changed.

This week Anker Electronics has finally acknowledged that, yes, Eufy Security cameras did produce video streams for the web portal, with no encryption, according to [The Verge](https://www.theverge.com/23573362/anker-eufy-security-camera-answers-encryption). Anker is Eufy's parent company. 

**Also:** [**The best security cameras**](https://www.zdnet.com/home-and-office/smart-home/best-security-camera/)

In the fall of 2022, the smart home devices manufacturer was caught [uploading user data to cloud servers without consent](https://www.zdnet.com/article/eufys-security-cameras-send-data-to-the-cloud-without-consent-and-thats-not-the-worst-part/). 

### Featured

* [Wi-Fi problems? Add a wired network to your home without Ethernet cable - here's how](https://www.zdnet.com/article/wi-fi-problems-how-to-add-a-wired-network-to-your-home-without-ethernet-cable/)
* [The best smart rings you can buy: Expert tested](https://www.zdnet.com/article/best-smart-ring/)
* [One of the best budget tablets I've tested replaced both my Kindle and iPad](https://www.zdnet.com/article/one-of-the-best-budget-tablets-ive-tested-replaced-bot-my-kindle-and-ipad/)
* [Wiping a Windows laptop? Here's the safest free way to erase your personal data](https://www.zdnet.com/article/wiping-a-windows-laptop-heres-the-safest-free-way-to-erase-your-personal-data/)

On top of that, customers claimed that someone could use a link from Eufy's web portal to view the camera's livestream using a media player, in this case VLC. 

Anker says that is no longer the case.

"Today, all videos (live and recorded) shared between the user's device to the Eufy Security Web portal or the Eufy Security App utilize end-to-end encryption, which is implemented using AES and RSA algorithms," said Anker's global head of communications, Eric Villines, who responded to The Verge's inquiries after weeks of the company remaining silent regarding these issues.

As far as what gets uploaded to the cloud, [Eufy has made clear disclaimers](https://www.zdnet.com/home-and-office/smart-home/eufy-responds-to-security-concerns/) on the mobile app explaining that some data must be uploaded to cloud servers when users turn on features like video previews for push notifications.

From my point of view, the problem is not uploading screenshots to the cloud, as most smart security cameras do the same. The problem is that Eufy was aware that this was happening and still led customers to believe the opposite. 

**Review:** [**EufyCam 3 and HomeBase 3: Why I'm not getting rid of these cameras yet**](https://www.zdnet.com/home-and-office/smart-home/eufycam-3-homebase-3-review/)

For as long as it's been selling security cameras and the [HomeBase](https://buy.geni.us/Proxy.ashx?TSID=368250&GR%5FURL=https%3A%2F%2Fwww.amazon.com%2Fdp%2FB099RX62SC%3Ftag%3Dzd-buy-button-20%26ascsubtag%3D%5F%5FCOM%5FCLICK%5FID%5F%5F%7C1ce536e8-30ff-4015-8244-a8ebc895f9f0%7Cdtp&dtb=1), Eufy had also been claiming that all your data is kept completely local. There's no need to worry, everything will be safe and sound right in your HomeBase's built-in storage drive, or any HDD or SSD you choose to add to it if you have the [latest version](https://buy.geni.us/Proxy.ashx?TSID=368250&GR%5FURL=https%3A%2F%2Fwww.amazon.com%2Feufy-Expandable-Compatibility-Military-Grade-Encryption%2Fdp%2FB0B7MN5DRQ%3Ftag%3Dzd-buy-button-20%26ascsubtag%3D%5F%5FCOM%5FCLICK%5FID%5F%5F%7C1ce536e8-30ff-4015-8244-a8ebc895f9f0%7Cdtp&dtb=1).

In its emails to The Verge, Anker apologized to customers for the lack of response and is voicing a commitment to doing a better job in the future. One of the ways it's doing so is by working with an independent company to perform security and penetration testing in an effort to audit Eufy's system and practices. 

The pictured EufyCam 3 and HomeBase 3 already use WebRTC.

Maria Diaz/ZDNET

The goal is to "conduct a comprehensive security risk assessment of our products and eliminate potential risks," Villines explained.

The company is also committing to ensuring that all video stream requests from Eufy's web portal will be end-to-end encrypted and is updating all Eufy cameras to use WebRTC, which the HomeBase 3 and EufyCam 3/3C already use. According to Anker, only about 0.1% of current daily users use the web portal.

The firmware updates to the remaining Eufy cameras began rolling out last week. 

**Also:** [**Eufy Edge Security System hands-on: The most advanced security cameras yet?**](https://www.zdnet.com/home-and-office/smart-home/eufy-edge-security-system-hands-on/)

Users of the Eufy Security mobile app can rest assured that their footage and camera feeds were already end-to-end encrypted, and this was done locally either on the camera or HomeBase, according to Anker. 

The Eufy Security web portal, which requires users to log in before accessing, was not originally designed with end-to-end encryption, which Villines admits it should have been from the beginning. It is the only video streaming process that did not use encryption.

Going forward, the company has put in place new protocols and procedures for features that may be developed in the future, ensuring that all data going from users' devices to the Eufy Security mobile app or web portal must use end-to-end encryption.

"There are several normal processes that require the use of the cloud such as account setup, push notifications, initial device setup, device OTA, etc.," Villines said. 

Screenshot of Eufy's "Proof of Privacy" on its website at the time of the incident that has since been edited.

Screenshot by Maria Diaz/Eufy Security

### **ZDNET** Recommends

[The best security cameras Our top picks for commercial properties will help secure your workplace.  Read now](https://www.zdnet.com/article/best-security-camera/)

Eufy also denies that it ever sent facial recognition data to the cloud, but it does mention an update was done for the [Video Doorbell Dual](https://buy.geni.us/Proxy.ashx?TSID=368250&GR%5FURL=https%3A%2F%2Fwww.amazon.com%2Feufy-Security-Battery-Powered-Detection-Recognition%2Fdp%2FB099RX62SC%2F%3Ftag%3Dzd-buy-button-20%26ascsubtag%3D%5F%5FCOM%5FCLICK%5FID%5F%5F%7C1ce536e8-30ff-4015-8244-a8ebc895f9f0%7Cdtp&dtb=1), which was the only one that used AWS cloud servers to send an initial facial recognition image to other cameras, but now uses LAN/P2P process to do so. ZDNET still hasn't heard back from Anker about any of these issues. 

The company is also planning on launching a microsite with information on which of its key processes are done locally and which require the use of the cloud, and is promising to provide "more timely updates in our community (and to the media!) to keep consumers better informed on any updates to these strategies," with one of those updates coming in early February.

## So, can you trust Eufy security cameras?

Every so often, we hear about cybersecurity flaws and data leaks from companies that have gained user trust -- this isn't new. Each time it happens it seems people with opinions sort into three general groups: one that thinks it's all overblown, one that can't believe people aren't more outraged, and one that remains neutral. 

Generally, I try to stay in the neutral field. I try to take the bad with the good, and to recognize how hard it is to build a completely impermeable system and then throw it into a hurricane and hope for the best. Throughout the past few weeks, however, I've shifted between all three positions.

Having a number of [Eufy devices all over my home](https://www.zdnet.com/home-and-office/smart-home/eufycam-3-homebase-3-review/), I think the company has a long way to go to regain consumer trust, and though these new processes seem promising, it'll take time for that to happen.

Regarding an apology, Villines said, "An apology should come with more details on what happened and the corrective steps we've done to make sure this doesn't happen again," and I think that's one thing we can all agree on.

#### Security

[The best VPN services of 2024: Expert tested](https://www.zdnet.com/article/best-vpn/ "The best VPN services of 2024: Expert tested")

[How to turn on Private DNS Mode on Android (and why you should)](https://www.zdnet.com/article/how-to-turn-on-private-dns-mode-on-android-and-why-you-should/ "How to turn on Private DNS Mode on Android (and why you should)")

[The best antivirus software and apps you can buy](https://www.zdnet.com/article/best-antivirus/ "The best antivirus software and apps you can buy")

[The best VPN routers you can buy](https://www.zdnet.com/article/best-vpn-router/ "The best VPN routers you can buy")

[How to find and remove spyware from your phone](https://www.zdnet.com/article/how-to-find-and-remove-spyware-from-your-phone/ "How to find and remove spyware from your phone")

* [The best VPN services of 2024: Expert tested](https://www.zdnet.com/article/best-vpn/ "The best VPN services of 2024: Expert tested")
* [How to turn on Private DNS Mode on Android (and why you should)](https://www.zdnet.com/article/how-to-turn-on-private-dns-mode-on-android-and-why-you-should/ "How to turn on Private DNS Mode on Android (and why you should)")
* [The best antivirus software and apps you can buy](https://www.zdnet.com/article/best-antivirus/ "The best antivirus software and apps you can buy")
* [The best VPN routers you can buy](https://www.zdnet.com/article/best-vpn-router/ "The best VPN routers you can buy")
* [How to find and remove spyware from your phone](https://www.zdnet.com/article/how-to-find-and-remove-spyware-from-your-phone/ "How to find and remove spyware from your phone")

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
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-discover-best-border-apps-to-elevate-instagram-visuals/"><u>[New] In 2024, Discover Best Border Apps to Elevate Instagram Visuals</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-trackingcast-synopsis/"><u>[Updated] TrackingCast Synopsis</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/cafmp4web-movividconvert/"><u>CAFへのフリーMP4コンバート：無料Webツールが決め手 - MoviVidConvert</u></a></li>
<li><a href="https://win-amazing.techidaily.com/download-qualcomm-atheros-ar956x-wi-fi-card-drivers-step-by-step-guide/"><u>Download Qualcomm Atheros AR956x Wi-Fi Card Drivers: Step-by-Step Guide</u></a></li>
<li><a href="https://techidaily.com/hard-resetting-an-oneplus-nord-n30-se-device-made-easy-drfone-by-drfone-reset-android-reset-android/"><u>Hard Resetting an OnePlus Nord N30 SE Device Made Easy | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-3-facts-you-need-to-know-about-screen-mirroring-samsung-galaxy-f34-5g-drfone-by-drfone-android/"><u>In 2024, 3 Facts You Need to Know about Screen Mirroring Samsung Galaxy F34 5G | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-pros-best-top-8-tripods-excelling-at-4k-video-capture/"><u>In 2024, Pro's Best Top 8 Tripods Excelling at 4K Video Capture</u></a></li>
<li><a href="https://games-able.techidaily.com/navigating-mmos-new-horizon-a-fresh-perspective/"><u>Navigating MMO’s New Horizon: A Fresh Perspective</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/toms-tech-insights-in-depth-reviews-and-news/"><u>Tom's Tech Insights: In-Depth Reviews & News</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/toms-tech-review-expert-insights-on-the-latest-hardware/"><u>Tom's Tech Review: Expert Insights on the Latest Hardware</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/toms-tech-review-the-definitive-guide-to-hardware/"><u>Tom's Tech Review: The Definitive Guide to Hardware</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/top-picks-for-your-pc-needs-at-toms-hardware-hub/"><u>Top Picks for Your PC Needs at Tom's Hardware Hub</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/transfer-your-apple-iphone-12-pro-apps-to-new-iphone-drfone-by-drfone-transfer-from-ios/"><u>Transfer your Apple iPhone 12 Pro Apps to New iPhone | Dr.fone</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/unleash-immersive-gaming-experience-newly-launched-minisforum-portable-screen-156-hd-with-144hz-display-only-189/"><u>Unleash Immersive Gaming Experience: Newly Launched Minisforum Portable Screen – 15.6 HD with 144Hz Display Only $189</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/unveiling-advanced-computing-a-dive-into-toms-hardware-analysis/"><u>Unveiling Advanced Computing: A Dive Into Tom's Hardware Analysis</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/unveiling-the-latest-in-hard-drive-technology-with-tom/"><u>Unveiling the Latest in Hard Drive Technology with Tom</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/your-guide-to-gadgets-and-gear-in-depth-reviews-by-toms-hardware-experts/"><u>Your Guide to Gadgets and Gear: In-Depth Reviews by Tom's Hardware Experts</u></a></li>
</ul></div>

