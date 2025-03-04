---
title: "Eufy Surveillance Cams: Unauthorized Cloud Uploads Revealed - What Else Is Hidden? | TechInsights"
date: 2025-03-03T16:58:25.123Z
updated: 2025-03-04T20:36:17.855Z
tags:
  - cyber-threats
categories:
  - tech
thumbnail: https://thmb.techidaily.com/60fe1a74657905b47d054d52197782d9df31df8374f9444c7a6b8dc97d98722a.jpg
---

## Eufy Surveillance Cams: Unauthorized Cloud Uploads Revealed - What Else Is Hidden? | TechInsights

![A Pinocchio doll looks down with Eufy cameras in background](https://www.zdnet.com/a/img/resize/b20025299658fc223a48faa5444d772049fb2a8a/2022/12/02/f73a1d83-25ee-4dcf-8982-0628f4bf5851/eufy-security-issues.jpg?auto=webp&width=1280)

Constantly selling the idea of private, secure local storage, Eufy Security has been caught misleading consumers.

Illustration: Maria Diaz / ZDNET | Photo: MaryAnnShmueli via Getty Images

[Eufy's claims](https://us.eufy.com/pages/security-eufycam3?ref=quickintro) to keep "privacy in your own hands" have been rendered null, after a researcher caught the security camera company uploading local-only footage to the cloud without user authorization or knowledge. To top it all off, users have also been made aware that you can watch camera streams using [VLC](https://www.videolan.org/vlc/) without authentication.

[Paul Moore](https://paul.reviews/), a security researcher, was the first to expose the security flaw in local data being stored in the cloud. He pointed out in the video below that, even though Eufy Security claims to take "every step imaginable" to keep its users' data private and local, it still uploads not only video thumbnails to cloud servers but also photos of the faces of people detected in the video, and user identifier data. 

**Also:** [**Eufy responds to camera security concerns**](https://www.zdnet.com/home-and-office/smart-home/eufy-security-responds-to-security-concerns/)

Eufy Security, a brand owned by the Chinese company Anker Innovations, touts to keep captured video data in the [HomeBase](https://buy.geni.us/Proxy.ashx?TSID=368250&GR%5FURL=https%3A%2F%2Fwww.amazon.com%2Feufy-Security-Compatibility-Military-Grade-Encryption%2Fdp%2FB09QG8FJ13%3Ftag%3Dzd-buy-button-20%26ascsubtag%3D%5F%5FCOM%5FCLICK%5FID%5F%5F%7C6967e010-289d-4c6b-9bd2-bfd2b21dedb6%7Cdtp&dtb=1), which is like a smart home hub on steroids. The HomeBase connects to Eufy devices around your home and stores the data within it, so your videos and pictures stay local and you don't have to pay for cloud services like you would with other companies such as [Ring](https://buy.geni.us/Proxy.ashx?TSID=368250&GR%5FURL=https%3A%2F%2Fwww.amazon.com%2Fstores%2FRing%2Fpage%2F77B53039-540E-4816-BABB-49AA21285FCF%3Ftag%3Dzd-buy-button-20%26ascsubtag%3D%5F%5FCOM%5FCLICK%5FID%5F%5F%7C6967e010-289d-4c6b-9bd2-bfd2b21dedb6%7Cdtp&dtb=1). 

### Privacy

* [How to delete yourself from internet search results and hide your identity online](https://www.zdnet.com/article/how-to-delete-yourself-from-internet-search-results-and-hide-your-identity-online/)
* [The best browsers for privacy](https://www.zdnet.com/article/best-browser-for-privacy/)
* [Samsung's smartphone 'Repair Mode' stops technicians from viewing your photos](https://www.zdnet.com/article/samsungs-smartphone-repair-mode-will-keep-nosy-technicians-from-looking-at-your-photos/)
* [Are period tracking apps safe?](https://www.zdnet.com/article/period-tracking-apps-are-no-longer-safe-delete-them/)

It's popular among smart home enthusiasts because of this very feature: your videos and any pertinent data stay safely in your home, only saved in the HomeBase's memory drive and/or an added HDD or SSD. 

**Also:** [**These file types are the ones most commonly used by hackers to hide their malware**](https://www.zdnet.com/article/these-file-types-are-the-ones-most-commonly-used-by-hackers-to-hide-their-malware/)

Moore tested this by walking to his [Eufy Video Doorbell Dual](https://buy.geni.us/Proxy.ashx?TSID=368250&GR%5FURL=https%3A%2F%2Fwww.amazon.com%2Feufy-Security-Battery-Powered-Detection-Recognition%2Fdp%2FB09QFK3JWS%3Ftag%3Dzd-buy-button-20%26ascsubtag%3D%5F%5FCOM%5FCLICK%5FID%5F%5F%7C6967e010-289d-4c6b-9bd2-bfd2b21dedb6%7Cdtp&dtb=1), waiting for the notification to appear on his phone, then unplugging the HomeBase. 

Moore pointed out that once his HomeBase was offline, two photos remained in the AWS cloud server: one of the video thumbmail and the other of his face when the doorbell camera detected a person, as well as user identifier information. The video was no longer available on the mobile app on his phone, of course, since the HomeBase was unreachable.

There is an option to enable cloud storage in the Eufy Security app, but Moore discovered the data was uploaded to cloud servers even when the cloud storage was disabled.

**Review:** [**Eufy Edge Security System: Why I'm not getting rid of these cameras yet**](https://www.zdnet.com/home-and-office/smart-home/eufycam-3-homebase-3-review/)

[Eufy responded](https://twitter.com/Paul%5FReviews/status/1595793302565146626/photo/1) by admitting to the issue and pointing out that the images are only used for notifications and immediately deleted from the server when the user deletes the events. However, once he deleted the events from his Eufy Security app, [the images were still left on the server](https://www.youtube.com/watch?v=etpbq%5FHH79c).

To top it all off, other users exposed that anyone could potentially access a Eufy camera without authentication or encryption by using VLC remotely.

> Ah well, the cats out the bag now... so may as well tell you.  
> You can remotely start a stream and watch [@EufyOfficial](https://twitter.com/EufyOfficial?ref%5Fsrc=twsrc^tfw) cameras live using VLC. No authentication, no encryption.  
> Please don't ask for a PoC - I can't release this one.  
> Heads up [@TechLinkedYT](https://twitter.com/TechLinkedYT?ref%5Fsrc=twsrc^tfw) [@LinusTech](https://twitter.com/LinusTech?ref%5Fsrc=twsrc^tfw) <https://t.co/sU3FyRaELX>
> 
> — Paul Moore (@Paul\_Reviews) [November 25, 2022](https://twitter.com/Paul%5FReviews/status/1596048648416423936?ref%5Fsrc=twsrc^tfw)

Since these allegations came out, [The Verge](https://www.theverge.com/2022/11/30/23486753/anker-eufy-security-camera-cloud-private-encryption-authentication-storage?rel=%22nofollow%22) said it tried this successfully, "proving that Anker has a way to bypass encryption and access these supposedly secure cameras through the cloud".

ZDNET reached out to Anker, Eufy's parent company, for comment but we've yet to hear back.

## Does this mean Eufy isn't secure?

According to [an email](https://twitter.com/Paul%5FReviews/status/1595793302565146626/photo/1) from Eufy Security to Moore, the HomeBase 3 is exempt from using the AWS cloud server to upload event screenshots due to a "high-performance database" made on the device. 

Unplugging your HomeBase is like disconnecting a USB flash drive from your computer: whatever is on the flash drive is no longer available on the computer when it's removed. 

Eufy should have a heartbeat check that, once the HomeBase is offline, any screenshots taken are deleted from that profile. At the very least, a disclaimer should appear when you enable snapshots on your notifications to say that these images would be stored in a cloud server if enabled. 

The biggest problem with this situation isn't that users' data is stored in cloud servers; it's that this is being done not only without consumers' consent, but with Eufy publicly touting to do the opposite. 

As far as someone else accessing the Eufy camera streams remotely? All I can say is that I'm keeping my Eufy cameras outside my home for the time being. 

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
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-secure-mobile-messaging-made-simple-with-these-10-best-free-chat-services-on-iphoneandroid/"><u>[New] 2024 Approved Secure Mobile Messaging Made Simple with These 10 Best Free Chat Services on iPhone/Android</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/new-in-2024-capture-coastlines-best-surfer-cams/"><u>[New] In 2024, Capture Coastlines Best Surfer Cams</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-next-level-designers-post-acid-tools-explored/"><u>[New] Next-Level Designers Post-ACID Tools Explored</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-in-2024-smart-techniques-to-curve-and-sculpt-pixels/"><u>[Updated] In 2024, Smart Techniques to Curve and Sculpt Pixels</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-unlocking-memories-facebook-look-back-editing-steps/"><u>[Updated] In 2024, Unlocking Memories Facebook Look Back Editing Steps</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-brightening-videos-android-tips/"><u>2024 Approved Brightening Videos Android Tips</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/approach-assess-the-influence-of-community-input-on-planning-decisions/"><u>Approach: Assess the Influence of Community Input on Planning Decisions.</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/deciphering-computing-power-insightful-reviews-from-toms-hardware-hub/"><u>Deciphering Computing Power: Insightful Reviews From Tom's Hardware Hub</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/elevating-your-videography-through-audio-storytelling-for-2024/"><u>Elevating Your Videography Through Audio Storytelling for 2024</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/implement-a-take-back-program-to-encourage-recycling-or-repurposing-of-used-products/"><u>Implement a Take-Back Program to Encourage Recycling or Repurposing of Used Products</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-change-spotify-location-after-moving-to-another-country-on-honor-x9a-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Spotify Location After Moving to Another Country On Honor X9a | Dr.fone</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/navigating-the-hardware-world-with-toms-pc-and-component-guide/"><u>Navigating the Hardware World with Tom's PC & Component Guide</u></a></li>
<li><a href="https://extra-skills.techidaily.com/smartphones-superior-topping-video-capture-lists-for-2024/"><u>Smartphones Superior Topping Video Capture Lists for 2024</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/the-lowdown-on-sabrents-rocket-nano-an-in-depth-examination-of-the-1tb-m2-222-gen3-x4-ssd/"><u>The Lowdown on Sabrent's Rocket Nano – An In-Depth Examination of the 1TB M.2 22#2 Gen3 X4 SSD</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/unveiling-top-notch-hardware-at-toms-reviews/"><u>Unveiling Top-Notch Hardware at Tom's Reviews</u></a></li>
</ul></div>

