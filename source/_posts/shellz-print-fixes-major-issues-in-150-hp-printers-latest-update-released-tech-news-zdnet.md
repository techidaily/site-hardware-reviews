---
title: Shellz Print Fixes Major Issues in 150 HP Printers, Latest Update Released - Tech News | ZDNet
date: 2024-11-14T17:04:28.321Z
updated: 2024-11-17T17:52:10.782Z
tags:
  - printer
categories:
  - tech
thumbnail: https://www.zdnet.com/a/img/resize/37181492efa227c16190a9a3a48a387dd769f520/2021/11/18/34f27153-3810-4fdd-8223-40800769b2c5/screenshot-2021-11-18-at-12-24-33.png?width=170&height=128&fit=crop&format=pjpg&auto=webp
---

## Shellz Print Fixes Major Issues in 150 HP Printers, Latest Update Released - Tech News | ZDNet

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
<li><a href="https://some-techniques.techidaily.com/updated-get-the-videos-you-love-from-pinterest-for-free/"><u>[Updated] Get the Videos You Love From Pinterest for Free</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-sony-fdr-x1000v-action-camera-complete-review/"><u>[Updated] Sony FDR-X1000V Action Camera Complete Review</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/209636296-9781633411128-allow-me-to-introduce/"><u>Allow Me to Introduce | Free Book</u></a></li>
<li><a href="https://win-able.techidaily.com/banish-your-fifa-19-pc-issues-with-these-troubleshooting-tips/"><u>Banish Your FIFA 19 PC Issues with These Troubleshooting Tips</u></a></li>
<li><a href="https://tech-haven.techidaily.com/boost-productivity-using-chatgpt-features-within-visual-studio-code-a-guide-to-10-key-strategies/"><u>Boost Productivity: Using ChatGPT Features Within Visual Studio Code - A Guide to 10 Key Strategies</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/chatgpts-max-token-limit-and-breaking-past-it/"><u>ChatGPT's Max Token Limit & Breaking Past It</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/comprehensive-guide-to-using-the-clevetura-clvx-wireless-keyboard-with-enhanced-keys/"><u>Comprehensive Guide to Using the Clevetura CLVX Wireless Keyboard with Enhanced Keys</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/expert-review-exceptional-visual-quality-on-gigabytes-aorus-co4nedq-monitor-with-oled-technology/"><u>Expert Review: Exceptional Visual Quality on Gigabyte's Aorus CO4nEDq Monitor with OLED Technology</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/exploring-the-asus-rog-strix-xg27acs-qhd-180hz-gaming-display-a-true-game-changer-in-visuals-and-response-times/"><u>Exploring the Asus ROG Strix XG27ACS QHD 180Hz Gaming Display - A True Game Changer in Visuals and Response Times</u></a></li>
<li><a href="https://ai-video-translation.techidaily.com/google-translate-video-a-complete-guide-to-translate-video-with-google/"><u>Google Translate Video A Complete Guide To Translate Video With Google</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-downgrade-iphone-13-mini-to-an-older-ios-version-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Downgrade iPhone 13 mini to an Older iOS Version? | Dr.fone</u></a></li>
<li><a href="https://win-able.techidaily.com/how-to-resolve-easy-anti-cheat-missing-when-starting-games/"><u>How to Resolve 'Easy Anti-Cheat Missing' When Starting Games</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-use-phone-clone-to-migrate-your-oneplus-nord-n30-se-data-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Use Phone Clone to Migrate Your OnePlus Nord N30 SE Data? | Dr.fone</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/inside-toms-gear-room-a-deep-dive-into-cutting-edge-pc-components/"><u>Inside Tom's Gear Room: A Deep Dive Into Cutting-Edge PC Components</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/mastering-devices-with-expertise-from-toms-hardware-experts/"><u>Mastering Devices with Expertise From Tom's Hardware Experts</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/pioneering-tech-insight-toms-hardware-essentials/"><u>Pioneering Tech Insight: Tom's Hardware Essentials</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/the-ultimate-guide-to-technology-according-to-toms-hardware/"><u>The Ultimate Guide to Technology According to Tom's Hardware</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/toms-tech-insights-unraveling-the-latest-computer-innovations/"><u>Tom's Tech Insights: Unraveling the Latest Computer Innovations</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/unveiling-the-latest-in-technology-with-toms-hardware-guide/"><u>Unveiling the Latest in Technology with Tom's Hardware Guide</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2134501/19576" target="_top" id="2134501">
  <img src="//a.impactradius-go.com/display-ad/19576-2134501" border="0" alt="https://techidaily.com" width="640" height="90"/>
</a>
<img height="0" width="0" src="https://aidotcom.pxf.io/i/5597632/2134501/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

