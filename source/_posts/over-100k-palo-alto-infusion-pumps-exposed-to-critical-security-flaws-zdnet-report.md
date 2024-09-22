---
title: Over 100K Palo Alto Infusion Pumps Exposed to Critical Security Flaws - ZDNet Report
date: 2024-09-17 11:49:34
updated: 2024-09-20 12:19:20
tags:
  - cyber-threats
categories:
  - tech
thumbnail: https://www.zdnet.com/topic/cyber-threats/    https://www.zdnet.com/a/img/resize/6e3ab51abdd3e83ed1a63167e426e6f9a46a7ce3/2022/03/04/db416a51-8339-4cec-92b8-8d29b8300dd1/shutterstock-218458957.jpg?width=170&height=96&fit=crop&auto=webp
---

## Over 100K Palo Alto Infusion Pumps Exposed to Critical Security Flaws - ZDNet Report

In an examination of more than 200,000 infusion pumps on the networks of several healthcare organizations, Palo Alto Networks security researchers discovered that more than 52% were susceptible to two known vulnerabilities that were disclosed in 2019 – one with a "critical" severity score and the other with a "high" severity score.

Palo Alto Network's Unit 42 [released a report](https://unit42.paloaltonetworks.com/infusion-pump-vulnerabilities/) examining 200,000 infusion pumps on the networks of hospitals and clinics that use their security program for IoT devices. 

### **ZDNET** Recommends

* [Best VPN services](https://www.zdnet.com/article/best-vpn/)
* [Best security keys](https://www.zdnet.com/article/best-security-key/)
* [Best antivirus software](https://www.zdnet.com/article/best-antivirus/)
* [The fastest VPNs](https://www.zdnet.com/article/fastest-vpn/)

"An alarming 75% of infusion pumps scanned had known security gaps that put them at heightened risk of being compromised by attackers," the researchers said. "These shortcomings included exposure to one or more of some 40 known cybersecurity vulnerabilities and/or alerts that they had one or more of some 70 other types of known security shortcomings for IoT devices."

The report lists several vulnerabilities affecting most infusion pumps, including CVE-2019-12255, CVE-2019-12264, CVE-2016-9355, CVE-2016-8375, CVE-2020-25165, CVE-2020-12040, CVE-2020-12047, CVE-2020-12045, CVE-2020-12043 and CVE-2020-12041\. 

CVE-2019-12255, which had a 9.8 rating, was found in 52.11% of all the infusion pumps Palo Alto looked at. CVE-2020-12040, CVE-2020-12047, CVE-2020-12045, CVE-2020-12043 and CVE-2020-12041 all had ratings of 9.8 and were found in at least 15% of the infusion pumps examined. 

Aveek Das, the Unit 42 researcher who conducted the study, told _ZDNet_ that threat actors could potentially exploit some of these vulnerabilities to take control of pump functions, including medication dosing.

**Also: [Some 'Smol' NFTs returned after Treasure marketplace exploit leads to theft](https://www.zdnet.com/article/some-smol-nfts-returned-after-treasuredao-exploit-discovered/)**

Das added that the issues they discovered are "just the tip of the iceberg" and noted that it was likely that they would find similar things with other connected devices in hospitals.

"We focused on infusion pumps because they are so prevalent -- they account for 44% of all medical devices and are the most widely used type of connected devices in healthcare settings," Das said.

Most large hospital systems have thousands of infusion pumps, making it difficult for security teams to manage and figure out which ones need to be replaced or updated. 

"The most common vulnerabilities we observed that are specific to the infusion systems we studied can be grouped into several categories according to the effects they may have: leakage of sensitive information, unauthorized access and overflow. Other vulnerabilities stem from third-party TCP/IP stacks but can affect the devices and their operating systems," the researchers explained. 

"We observe that a large number of vulnerabilities in infusion pump systems – and in internet of medical things (IoMT) devices overall – are related to leakage of sensitive information. Devices vulnerable to this type of issue can leak operational information, patient-specific data, or device or network configuration credentials. Attackers looking to exploit these vulnerabilities need varying degrees of access. For example, CVE-2020-12040, which is specific to clear-text communication channels, can be remotely exploited by an attacker via a man-in-the-middle attack to access all the communication information between an infusion pump and a server. On the other hand, CVE-2016-9355 and CVE-2016-8375 can be exploited by someone with physical access to an infusion pump device to gain access to sensitive information – which makes the attack less likely, but still possible for an attacker with specific motivations."

The report adds that some of the other vulnerabilities discovered could give unauthenticated users the ability to gain access to a device or to send network traffic in a certain pattern that can cause a device to become unresponsive or operate in a way that is not expected. 

The researchers said the vulnerabilities can lead to a variety of bad outcomes, including disruptions to hospital operations and patient care.

"Continuous use of default credentials, which are readily available online via a simple search, is another major issue in IoT devices in general – since it can give anyone who is in the same hospital network as the medical devices direct access to them," the report said. 

"Many IoMT (and IoT) devices and their operating systems use third-party cross-platform libraries, such as network stacks, which might have vulnerabilities affecting the device in question. For example, for CVE-2019-12255 and CVE 2019-12264, the vulnerable TCP/IP stack IPNet is a component of the ENEA OS of Alaris Infusion Pumps, thereby making the devices vulnerable."

Infusion pumps [have long been a source of ire for cybersecurity experts](https://www.zdnet.com/article/b-braun-updates-faulty-iv-pump-after-mcafee-discovers-vulnerability-allowing-attackers-to-change-doses/) and vendors who have spent more than a decade trying to improve their security. Palo Alto noted that the US Food and Drug Administration announced [seven recalls for infusion pumps](https://www.fda.gov/medical-devices/medical-device-recalls/2021-medical-device-recalls) or their components in 2021 and [nine more recalls in 2020.](https://www.fda.gov/medical-devices/medical-device-recalls/2020-medical-device-recalls)

There has also been a [movement](https://www.fda.gov/news-events/press-announcements/fda-brief-fda-issues-draft-guidance-remanufacturing-and-discussion-paper-seeking-feedback) to [establish a base level](https://cmdc.umn.edu/) of cybersecurity for the industry, but it has been hampered by the fact that most infusion pumps last about 10 years. This means many hospitals are using years old pumps, making it more difficult to apply newer security features. 

Palo Alto could not say whether these vulnerabilities have ever been exploited, and almost no expert contacted could identify situations where these vulnerabilities were used during attacks. 

But Casey Ellis, CTO at Bugcrowd, said medical device security issues are incredibly personal and disconcerting. 

"I've seen wireless exploitation of similar systems used to create condition which were able to dump the entire contents of an infusion pump or cause a pacemaker to discharge its battery all at once. These vulnerabilities don't have that same kind of immediate safety implication, but an attacker could easily exploit the information leakage bugs, for example, to obtain data usable to threaten and extort a user with a similar outcome," Ellis said. 

"Medical devices are intimately tied with their user, and in the case of a targeted attack, the possibilities range from extortion to surveillance to direct compromise of the individual themselves. The vulnerabilities in the report don't seem to be directly tied to the ability to harm a user, but where there's smoke, there is usually fire. The implication of the report is that software vulnerabilities (and lag time in patches them) is a systemic problem with medical devices. This is partly an area of important improvement for medical device manufacturers, and partly a challenge of testing and updating safety-critical systems."

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
