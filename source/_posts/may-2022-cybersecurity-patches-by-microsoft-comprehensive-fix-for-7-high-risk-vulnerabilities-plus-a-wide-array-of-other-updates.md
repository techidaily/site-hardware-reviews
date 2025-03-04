---
title: "May 2022 Cybersecurity Patches by Microsoft: Comprehensive Fix for 7 High-Risk Vulnerabilities, Plus a Wide Array of Other Updates"
date: 2025-03-03T18:52:56.799Z
updated: 2025-03-04T19:19:40.162Z
tags:
  - cyber-threats
categories:
  - tech
thumbnail: https://thmb.techidaily.com/c72f65d6cf6eccfb8dd0cd66944cb2172744b7375f3b2c967f4222ce690bc4fc.jpg
---

## May 2022 Cybersecurity Patches by Microsoft: Comprehensive Fix for 7 High-Risk Vulnerabilities, Plus a Wide Array of Other Updates

Microsoft has released a total of 74 new security fixes for its software products. This includes one "important" flaw ([a Windows LSA Spoofing Vulnerability](https://msrc.microsoft.com/update-guide/vulnerability/CVE-2022-26925)) that was being actively exploited in the wild.

In the Redmond giant's latest [round of patches](https://msrc.microsoft.com/update-guide/en-us), usually released on the second Tuesday of each month on what is known as Patch Tuesday, Microsoft fixed the aforementioned active exploit, as well as seven other "critical" issues: five remote code execution (RCE) bugs and two elevation of privilege (EoP) flaws. The remaining list of 67 exploits are dominated by additional RCE and EoP bugs. A smattering of denial-of-service, information leaks, security feature bypasses, and spoofing issues were corrected as well. 

### **ZDNET** Recommends

[The best encryption software From home offices to hybrid cloud solutions, we have you covered.  Read now](https://www.zdnet.com/article/best-encryption-software/)

Products impacted by May's security update include the Windows OS and several of its components; the .NET and Visual Studio platforms; Office and its components; Exchange Server; BitLocker; Remote Desktop Client; NTFS; and Microsoft Edge. 

Some of the most severe vulnerabilities resolved in this update are: 

* [CVE-2022-26925](https://msrc.microsoft.com/update-guide/vulnerability/CVE-2022-26925): The only flaw this month listed as being actively exploited. This "important" flaw allows malicious actors to "call a method on the LSARPC interface and coerce the domain controller to authenticate to the attacker using NTLM." Microsoft assigned the flaw a CVSS severity score of 8.1, but noted that if it was combined with NTLM relay attacks, the severity would be bumped up to 9.8\. This patch corrects the flaw by detecting and disallowing anonymous connection attempts in LSARPC.
* [CVE-2022-26923](https://msrc.microsoft.com/update-guide/vulnerability/CVE-2022-26923\): This "critical" flaw exploits the issuance of certificates by inserting crafted data into a certificate request. This allows the attacker to obtain a certificate which is capable of authenticating a domain controller with a high-level of privilege. It essentially allows the individual with unauthorized authentication to become a domain admin within any domain running Active Directory Certificate Services. This flaw earned a CVSS score of 8.8

Both [CVE-2022-26937](https://msrc.microsoft.com/update-guide/vulnerability/CVE-2022-26937) and [CVE-2022-29972](https://msrc.microsoft.com/update-guide/vulnerability/CVE-2022-29972) are also of special note. The former is an RCE vulnerability in the Windows Network File System (NFS) that targets systems in environments with mixed OS use; the latter is a flaw in the Magnitude Simba Amazon Redshift ODBC Driver important enough to earn its [own blog post from Microsoft](https://msrc-blog.microsoft.com/2022/05/09/vulnerability-mitigated-in-the-third-party-data-connector-used-in-azure-synapse-pipelines-and-azure-data-factory-cve-2022-29972/). 

**Also:** [**Microsoft's latest Windows 11 test build adds new group policies, drops SMB1 enablement by default**](https://www.zdnet.com/article/microsofts-latest-windows-11-test-build-adds-new-group-policies-drops-smb1-enablement-by-default/)

According to the [Zero Day Initiative](https://www.zerodayinitiative.com/blog) (ZDI), [this month's fixes](https://www.zerodayinitiative.com/blog/2022/5/10/the-may-2022-security-update-review) fall in line with previous May Patch Tuesdays, resulting in the release of 19 more fixes than the previous year, but five fewer than 2019's equivalent. 

Last month, Microsoft resolved over 100 vulnerabilities in the April batch of security fixes. These included two zero-day vulnerabilities; a known Windows User Profile Service bug leading to privilege escalation; and another EoP flaw in the Windows Common Log File System Driver, which was being actively exploited at the time a security fix was issued. 

In other Microsoft news, Microsoft's [Q3 earnings](https://www.zdnet.com/article/microsoft-cloud-revenue-at-23-4-billion-in-q3-up-32-percent/) revealed revenues surging across the board, reaching $49.4 billion. Cloud revenue was reported as $23.4 billion, up 32% year-over-year.

---

Alongside Microsoft's Patch Tuesday, other vendors have published security updates which can be accessed below:

* Adobe [security updates](https://helpx.adobe.com/security.html)
* SAP [security updates](https://wiki.scn.sap.com/wiki/display/PSR/The+Official+SAP+Product+Security+Response+Space)
* VMWare [security advisories](https://www.vmware.com/security/advisories.html)
* Intel [security updates](https://www.intel.com/content/www/us/en/security-center/default.html)

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
<li><a href="https://fox-helps.techidaily.com/new-a-rundown-top-8-exceptional-free-online-translation-platforms-for-2024/"><u>[New] A Rundown Top 8 Exceptional Free Online Translation Platforms for 2024</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-2024-approved-essential-tactics-in-creating-convincing-testimonial-content/"><u>[Updated] 2024 Approved Essential Tactics in Creating Convincing Testimonial Content</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-latest-series-captivating-qanda-for-podcast-audience/"><u>2024 Approved Latest Series Captivating Q&A for Podcast Audience</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-reviewing-the-newest-2023-samsung-bd-j5900-model/"><u>2024 Approved Reviewing the Newest 2023 Samsung BD-J5900 Model</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/apex-spectrum-by-maingear-combining-customizable-rgb-lighting-with-advanced-liquid-cooling-features/"><u>Apex Spectrum by Maingear: Combining Customizable RGB Lighting with Advanced Liquid Cooling Features</u></a></li>
<li><a href="https://activate-lock.techidaily.com/bypass-icloud-activation-lock-with-imei-code-on-your-iphone-13-mini-by-drfone-ios/"><u>Bypass iCloud Activation Lock with IMEI Code On your iPhone 13 mini</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/1723964468371-discover-the-new-dawn-of-computing-with-intels-bean-canyon-nucs-superior-speed-and-throttled-tdp/"><u>Discover the New Dawn of Computing with Intel's Bean Canyon NUCs - Superior Speed & Throttled TDP</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/expedite-your-videos-on-tiktok-secrets-revealed-for-2024/"><u>Expedite Your Videos on TikTok Secrets Revealed for 2024</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/exploring-toms-tech-insights-a-guide-to-the-latest-in-computer-hardware/"><u>Exploring Tom's Tech Insights: A Guide to the Latest in Computer Hardware</u></a></li>
<li><a href="https://some-techniques.techidaily.com/get-started-with-streamlabs-on-mac-using-obs-instantly-for-2024/"><u>Get Started with Streamlabs on Mac Using OBS Instantly for 2024</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/how-will-us-import-duties-impact-the-cost-of-electronic-components-and-personal-computers-unraveling-the-complexity/"><u>How Will US Import Duties Impact the Cost of Electronic Components & Personal Computers? Unraveling the Complexity</u></a></li>
<li><a href="https://fox-blue.techidaily.com/in-2024-ascending-the-podium-in-drone-racing-plus-essential-fpv-brands/"><u>In 2024, Ascending the Podium in Drone Racing + Essential FPV Brands</u></a></li>
<li><a href="https://win11.techidaily.com/insightful-insights-essential-windows-11-weather-apps-guide/"><u>Insightful Insights: Essential Windows 11 Weather Apps Guide</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/introducing-the-qualcomm-snapdragon-development-board-bridging-microsoft-windows-and-arm-technology/"><u>Introducing the Qualcomm Snapdragon Development Board: Bridging Microsoft Windows and ARM Technology</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/quiet-powerhouse-creation-the-journey-to-an-rgb-less-whisper-quiet-computer-insights-from-toms-hardware/"><u>Quiet Powerhouse Creation: The Journey to an RGB-Less, Whisper-Quiet Computer - Insights From Tom's Hardware</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/toms-computer-review-the-ultimate-guide-to-tech-innovations/"><u>Tom's Computer Review: The Ultimate Guide to Tech Innovations</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/toms-tech-insights-the-ultimate-guide-to-computer-components-t17239718716137/"><u>Tom's Tech Insights: The Ultimate Guide to Computer Components</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/top-10-password-cracking-tools-for-oppo-a56s-5g-by-drfone-android/"><u>Top 10 Password Cracking Tools For Oppo A56s 5G</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/top-redux-masterpieces-of-2016-were-accepting-entries-now/"><u>Top Redux Masterpieces of 2016 - We're Accepting Entries Now!</u></a></li>
</ul></div>

