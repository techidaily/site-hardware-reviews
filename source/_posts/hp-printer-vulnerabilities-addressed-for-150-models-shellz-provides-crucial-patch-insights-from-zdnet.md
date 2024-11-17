---
title: "HP Printer Vulnerabilities Addressed for 150 Models: Shellz Provides Crucial Patch - Insights From ZDNet"
date: 2024-11-15T17:30:35.139Z
updated: 2024-11-17T17:15:08.334Z
tags:
  - printer
categories:
  - tech
thumbnail: https://thmb.techidaily.com/2579e58fb859f12bcf75d41bfcd2bb7289ef81a099867df0bbc5e1bf070a408f.jpg
---

## HP Printer Vulnerabilities Addressed for 150 Models: Shellz Provides Crucial Patch - Insights From ZDNet

![screenshot-2021-11-18-at-12-24-33.png](https://www.zdnet.com/a/img/resize/b638bc1117340e3e7e411473e389e70a5a0ceaa7/2021/11/18/34f27153-3810-4fdd-8223-40800769b2c5/screenshot-2021-11-18-at-12-24-33.png?auto=webp&width=1280)

F-Secure

HP has patched critical flaws impacting approximately 150 printer models. 

Printers are usually connected to business networks -- and potentially forgotten when it comes to security -- so they can easily provide an avenue of attack. Highlighting this issue is [PrintNightmare](https://www.zdnet.com/article/microsoft-fixes-windows-10-printnightmare-flaw-with-this-update/), CVE-2021-34481, a Windows Print Spooler service vulnerability that permits attackers to escalate privileges to system level, which was patched in August. In addition, HP patched a separate, 16-year-old privilege escalation[driver flaw in July](https://www.zdnet.com/article/hp-patches-vulnerable-printer-driver-impacting-millions-of-devices/). 

### Security

* [The best VPN services of 2024: Expert tested](https://www.zdnet.com/article/best-vpn/)
* [How to turn on Private DNS Mode on Android (and why you should)](https://www.zdnet.com/article/how-to-turn-on-private-dns-mode-on-android-and-why-you-should/)
* [The best antivirus software and apps you can buy](https://www.zdnet.com/article/best-antivirus/)
* [The best VPN routers you can buy](https://www.zdnet.com/article/best-vpn-router/)
* [How to find and remove spyware from your phone](https://www.zdnet.com/article/how-to-find-and-remove-spyware-from-your-phone/)

**Also:** [**Microsoft just revealed another Print Spooler bug**](https://www.zdnet.com/article/windows-10-microsoft-just-revealed-another-print-spooler-bug/)

Now, researchers from F-Secure have documented "[Printing Shellz](https://labs.f-secure.com/publications/printing-shellz)," a set of vulnerabilities impacting multifunction printers (MFPs). 

On Thursday, the research team said that their tests involved the HP MFP M725z. However, the vulnerabilities -- dating back to 2013 -- impact an estimated 150 products. These include models in the HP Color LaserJet Enterprise, HP LaserJet Enterprise, HP PageWide, HP OfficeJet Enterprise Color, and HP ScanJet Enterprise 8500 FN1 Document Capture Workstation ranges. 

The first issue the researchers discovered was [CVE-2021-39238](https://nvd.nist.gov/vuln/detail/CVE-2021-39238). Assigned a CVSS severity score of 9.3, this potential buffer overflow issue could allow the creation of a "self-propagating network worm capable of independently spreading to other vulnerable MFPs on the same network," according to F-Secure researchers Alexander Bolshev and Timo Hirvonen. 

The second issue, [CVE-2021-39237](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-39237) (CVSS 7.1), is described by HP as an information disclosure bug. F-Secure says this flaw was caused by exposed physical ports, so local access is required as an avenue for attack. 

It's possible to exploit these flaws locally via physical access to the device, such as by printing from USB. And when it comes to CVE-2021-39238, another potential attack vector involves sending an exploit payload directly from a browser via cross-site printing (XSP). 

"These vulnerabilities give attackers an effective way to steal information: defenders are unlikely to proactively examine the security of a printer, and so the attacker can simply sit back and steal whatever information it comes across (via employees printing, scanning, etc)," F-Secure comments. "They could also use the MFP as a pivot point to move through the corporate network." 

HP was informed of F-Secure's discoveries on April 29 and has since released two advisories ([1](https://support.hp.com/us-en/document/ish%5F5000383-5000409-16/hpsbpi03749),[2](https://support.hp.com/us-en/document/ish%5F5000124-5000148-16/hpsbpi03748)), detailing the vulnerabilities. Patches and firmware updates were released in November. 

There is no evidence of exploitation in the wild. 

"Any organizations using affected devices should install the patches as soon as they're available," the researchers say. "While exploiting these issues is somewhat difficult, the public disclosure of these vulnerabilities will help threat actors know what to look for to attack vulnerable organizations." 

---

**Have a tip?** Get in touch securely via WhatsApp | Signal at +447713 025 499, or over at Keybase: charlie0 

---

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
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-expert-techniques-for-smooth-screen-casting/"><u>[New] 2024 Approved Expert Techniques for Smooth Screen Casting</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-2024-approved-conquering-macs-record-functionality-keyboard-driven-tips/"><u>[Updated] 2024 Approved Conquering Mac's Record Functionality Keyboard-Driven Tips</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-turning-heads-with-efficient-video-rotation-in-vlc/"><u>[Updated] Turning Heads with Efficient Video Rotation in VLC</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-ultimate-list-hashtags-for-maximum-video-engagement-in-games/"><u>2024 Approved Ultimate List Hashtags for Maximum Video Engagement in Games</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/affordable-diy-circuit-creation-cytron-maker-uno-rp2040-feedback/"><u>Affordable DIY Circuit Creation: Cytron Maker Uno RP2040 Feedback</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/breaking-down-the-asrock-z790i-lightning-wi-fi-board-performance-small-form-factor-big-impact/"><u>Breaking Down the ASRock Z790I Lightning Wi-Fi Board Performance: Small Form Factor, Big Impact</u></a></li>
<li><a href="https://vp-tips.techidaily.com/elevate-image-quality-to-professional-levels-with-winxvideo-ai-achieve-stunning-4k8k10k-resolution/"><u>Elevate Image Quality to Professional Levels with WinxVideo AI - Achieve Stunning 4K/8K/10K Resolution!</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/elevate-your-gaming-experience-with-the-asus-rog-strix-xg27acs-a-qhd-180hz-display-reviewed-for-speed-and-precision/"><u>Elevate Your Gaming Experience with the Asus ROG Strix XG27ACS - A QHD 180Hz Display Reviewed for Speed and Precision</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/expert-reviews-by-tom-top-tier-computer-gear-insight/"><u>Expert Reviews by Tom - Top-Tier Computer Gear Insight</u></a></li>
<li><a href="https://win-blog.techidaily.com/how-to-stop-left-4-dead-2-from-crashing-effective-strategies-and-fixes/"><u>How to Stop Left 4 Dead 2 From Crashing: Effective Strategies and Fixes</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-explore-the-finest-18-wireless-camcorders-today/"><u>In 2024, Explore the Finest 18 Wireless Camcorders Today</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/1723341695305-in-depth-review-of-the-rode-streamer-x-fulfill-your-live-broadcast-needs/"><u>In-Depth Review of the Rode Streamer X: Fulfill Your Live Broadcast Needs!</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/mastering-the-fix-a-comprehensive-approach-to-overcoming-the-500-server-error/"><u>Mastering the Fix: A Comprehensive Approach to Overcoming the 500 Server Error</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/navigating-the-world-of-technology-with-toms-hardware-hub/"><u>Navigating the World of Technology with Tom's Hardware Hub</u></a></li>
<li><a href="https://fix-guide.techidaily.com/strategies-for-apps-that-wont-download-from-play-store-on-lava-yuva-3-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Strategies for Apps That Wont Download From Play Store On Lava Yuva 3 Pro | Dr.fone</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/the-ultimate-guide-to-advanced-hardware-by-toms-technological-reviewers/"><u>The Ultimate Guide to Advanced Hardware by Tom's Technological Reviewers</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/unveiling-the-rode-streamer-x-a-step-closer-to-streaming-perfection/"><u>Unveiling the Rode Streamer X: A Step Closer to Streaming Perfection?</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2132162/7443" target="_top" id="2132162">
  <img src="//a.impactradius-go.com/display-ad/7443-2132162" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2132162/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

