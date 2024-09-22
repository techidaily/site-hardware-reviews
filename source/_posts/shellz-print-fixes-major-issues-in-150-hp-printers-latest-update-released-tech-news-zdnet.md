---
title: Shellz Print Fixes Major Issues in 150 HP Printers, Latest Update Released - Tech News | ZDNet
date: 2024-09-19 17:16:15
updated: 2024-09-20 12:11:37
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
