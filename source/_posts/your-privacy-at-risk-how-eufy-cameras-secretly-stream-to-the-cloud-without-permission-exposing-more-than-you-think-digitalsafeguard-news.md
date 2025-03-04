---
title: "Your Privacy at Risk: How Eufy Cameras Secretly Stream to the Cloud Without Permission, Exposing More Than You Think | DigitalSafeguard News"
date: 2025-03-02T16:48:15.339Z
updated: 2025-03-04T20:02:06.300Z
tags:
  - cyber-threats
categories:
  - tech
thumbnail: https://thmb.techidaily.com/fd49bc993ce8510e13bd3ece8f5853b9890f1d550e51d2b3c30dcfc01a7a61b2.jpg
---

## Your Privacy at Risk: How Eufy Cameras Secretly Stream to the Cloud Without Permission, Exposing More Than You Think | DigitalSafeguard News

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
<li><a href="https://tiktok-videos.techidaily.com/updated-permanent-tiktok-account-elimination-guide/"><u>[Updated] Permanent TikTok Account Elimination Guide</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-unpacking-the-power-of-auditory-melds-in-production-for-2024/"><u>[Updated] Unpacking the Power of Auditory Melds in Production for 2024</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-the-initial-step-in-youtube-fame-account-registration/"><u>2024 Approved The Initial Step in YouTube Fame Account Registration</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/firefox-on-turbocharge-unlock-extreme-speed-with-these-effortless-tweaks/"><u>Firefox on Turbocharge: Unlock Extreme Speed with These Effortless Tweaks</u></a></li>
<li><a href="https://android-location.techidaily.com/getting-the-pokemon-go-gps-signal-not-found-11-error-in-oppo-a1-5g-drfone-by-drfone-virtual/"><u>Getting the Pokemon Go GPS Signal Not Found 11 Error in Oppo A1 5G | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-old-call-logs-from-your-oppo-reno-9a-by-fonelab-android-recover-call-logs/"><u>How to recover old call logs from your Oppo Reno 9A?</u></a></li>
<li><a href="https://hardware-help.techidaily.com/improve-your-pcs-visual-performance-with-the-newest-intel-iris-xe-drivers-for-win-1011/"><u>Improve Your PC’s Visual Performance with the Newest Intel Iris Xe Drivers for Win 10/11</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/in-2024-whats-the-real-distinction-between-youtube-and-dailymention/"><u>In 2024, What's the Real Distinction Between YouTube and DailyMention?</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/toms-tech-reviews-a-comprehensive-guide-by-toms-hardware/"><u>Tom's Tech Reviews: A Comprehensive Guide by Tom's Hardware</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/toms-tech-reviews-in-depth-analysis-of-latest-computer-components/"><u>Tom's Tech Reviews: In-Depth Analysis of Latest Computer Components</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/toms-tech-reviews-in-depth-gadget-evaluations-and-guides/"><u>Tom's Tech Reviews: In-Depth Gadget Evaluations & Guides</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/top-picks-best-ssd-and-hdd-offers/"><u>Top Picks: Best SSD & HDD Offers</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/top-notch-tech-insights-from-toms-review-hub/"><u>Top-Notch Tech Insights From Tom's Review Hub</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/ultimate-guide-to-affordable-solid-state-drives-and-hard-disk-drives-in-202/"><u>Ultimate Guide to Affordable Solid State Drives & Hard Disk Drives in 202</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/unbeatable-prime-day-offerings-save-big-with-4tb-ssds-for-only-four-pennies-per-gb-in-a-spectacular-storage-sale-event/"><u>Unbeatable Prime Day Offerings: Save Big with 4TB SSDs for Only Four Pennies per GB in a Spectacular Storage Sale Event</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-vintage-makeover-transform-into-classic-windows-98/"><u>Windows 11 Vintage Makeover: Transform Into Classic Windows 98</u></a></li>
</ul></div>

