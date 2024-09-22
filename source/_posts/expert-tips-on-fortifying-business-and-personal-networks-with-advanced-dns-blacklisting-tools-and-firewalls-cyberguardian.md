---
title: Expert Tips on Fortifying Business & Personal Networks with Advanced DNS Blacklisting Tools & Firewalls | CyberGuardian
date: 2024-09-19 13:20:56
updated: 2024-09-20 11:15:16
tags:
  - cyber-threats
categories:
  - tech
thumbnail: https://www.zdnet.com/a/img/resize/3e23086ecc682f4b46845bf386a4ea9ab9a0b929/2022/02/21/3f793e0d-2744-4d2f-88f0-9d6bfcb926e1/gettyimages-1055693972-lit-laptop-keyboard2.jpg?width=278&height=156&fit=crop&auto=webp
---

## Expert Tips on Fortifying Business & Personal Networks with Advanced DNS Blacklisting Tools & Firewalls | CyberGuardian

How secure is your home or office network?

I'll assume you already have an [antimalware/antivirus solution](https://www.zdnet.com/article/best-antivirus/) in place, such as [Windows Security](https://support.microsoft.com/en-us/windows/stay-protected-with-windows-security-2ae0363d-0ada-c064-8b56-6a39afb6a963), which is built into Windows 10 and Windows 11 (and which I believe works particularly well). But antivirus isn't enough.

[Escalating international tensions](https://www.zdnet.com/article/ukraine-crisis-russian-cyberattacks-could-affect-organisations-around-the-world-so-take-action-now/) \-- coupled with an ever-increasing number of [professionals working remotely](https://www.zdnet.com/article/security-remote-work-support-top-concerns-amongst-firms/) \-- are driving the need for small-scale solutions and best practices to secure home- and small-business networks and mobile devices from malware, malvertising, and other threats. 

### **ZDNET** Recommends

* [Best VPN services](https://www.zdnet.com/article/best-vpn/)
* [Best security keys](https://www.zdnet.com/article/best-security-key/)
* [Best antivirus software](https://www.zdnet.com/article/best-antivirus/)
* [The fastest VPNs](https://www.zdnet.com/article/fastest-vpn/)

What follows is a brief guide -- with product recommendations and best practices -- for those of you looking to navigate the rapidly evolving cybersecurity landscape. If you have limited network security experience but want to provide additional security for yourself, your small business, or your friends and family, this guide is for you. (If you're looking for more extensive resources on networking security, [CISA's guide](https://www.zdnet.com/article/cisa-publishes-guide-with-free-cybersecurity-tools-resources-for-incident-response/) is a good place to start.) 

Below are the products I am currently using to protect my family's home networks and mobile devices. (I expect to add more product and service recommendations when I have sufficient time to investigate them.)

## Mobile and device-based DNS VPN firewall

[NextDNS](https://nextdns.io/pricing) 

If you can have only one solution, because you or your friends or loved ones cannot afford a hardware-based firewall device, look no further than NextDNS, which combines an encrypted VPN traffic tunnel with a hosted firewall and DNS blocking and filtering service. 

When installed as an app on a device, the service creates a private encrypted connection (VPN) to its cloud servers. Its basic functionality includes proxying Domain Name Services (DNS) queries against a large database of potentially malicious sites and blocking them, depending on how restrictive the service is set up. This means if you try to access a site listed on its blocklists, it will stop the connection. This also includes blocklists for advertisements and pornography, if enabled. 

It should be noted that NextDNS is not a VPN service (such as [these covered recently](https://www.zdnet.com/article/best-vpn/) by David Gewirtz) for creating anonymized private connections to the public internet and for end-to-end enterprise VPN connectivity (such as with [OpenVPN](https://openvpn.net/)) even though it uses its own VPN for the service to work. However, it can work in tandem with those services as needed.

The service has native clients for iOS, MacOS, Android, Windows, Linux, and Chrome OS, and can be set as the default DNS on a broadband router or an IoT device. And best of all, the lowest tier of service is absolutely free. The "Pro" service has unlimited devices, unlimited queries, unlimited configurations, and is a whole $20 per year.

The only main drawback of this service is that it is client-based -- meaning you need to install this software on every device you use it on. So it's ideal for smartphones, tablets, and laptops when you are on a mobile network or using a public Wi-Fi or ethernet connection, but not suitable for "blanket" device coverage on a home or small office broadband network. It is also a DNS-based solution rather than an IP-based and connection-oriented solution, so it is not a true intrusion prevention solution such as a hardware firewall.

[View now at NextDNS](https://nextdns.io/pricing) 

To begin using it, simply visit [nextdns.io](https://www.nextdns.io), and start a new configuration. The first thing you will want to take note of is your randomly-issued ID, which is how you and your family members will identify yourself to the service and how it will apply specific security settings you choose to them.

NextDNS initial configuration screen web user interface

Jason Perlow/ZDNet

The clients all have similar configuration screens and are all easy to install, but the key thing to remember is the Configuration ID and to "Send Device ID", because that ensures you are using the service with your specified configuration and that when the system logs activity, you will be able to narrow down to which device is having an event.

NextDNS Client configuration in iOS

Jason Perlow/ZDNet

Once you have the clients connected to the NextDNS VPN, you can verify they are using the service and that it is logging the connections with the **Logs** tab at the top of the web portal UX. The logs page allows you to look at traffic logs on a device per device basis, for all DNS queries or just blocked queries.

Logs menu of NextDNS user interface

Jason Perlow/ZDNet

Security protection options can be set in the **Security** menu tab where various services can be enabled, such as for AI-Driven Threats, Google Safe Browsing, Cryptojacking, DNS Rebinding, IDN Homograph Attacks, Typosquatting, Domain Generation Algorithms, Newly Registered Domains, Parked Domains, and Child Sexual Abuse Material. I have all of these currently turned on in my own configuration.

Tracking and Ad blocking are enabled in the **Privacy** menu tab. The two blocklists I currently have enabled are NextDNS's maintained list and OISD, which covers enough ground to protect mobile devices for most regular browsing and mobile app use while keeping functionality the least restrictive as possible. If you enable too many lists, you may find that certain apps (such as Facebook, with its Graph API) may begin to misbehave, and then you will need to disable NextDNS for them to work again temporarily. So I would only start adding more blocklists such as AdGuard and a few others on their curated list one at a time to see how it affects your usability. 

NextDNS Privacy menu

Jason Perlow/ZDNet

NextDNS also has a **Parental Controls** menu for locking out specific websites, apps, and games, as well as the ability to lock out pornography, piracy, dating, and social networks. NextDNS has the ability to have multiple Configuration IDs per account, so if you want to configure your children's devices, you might want to assign them a separate Configuration ID as well as enter a Parental Passcode in their NextDNS app settings screen so it cannot be altered. You'll also want to set Parental Controls on their devices using native app restrictions (Such as the Content and Privacy Restrictions menu on iOS) so the NextDNS app cannot be deleted.

## Open Source wide-spectrum DNS blocking

[Pi-Hole (Open Source)](https://pi-hole.net/) 

If you are inclined to host your own DNS proxy, and want the most flexible control over the domains you want to block on your premises, look no further than [Pi-Hole](https://pi-hole.net/). Originally built for the Raspberry Pi embedded development board, the open source project has become hugely popular with cybersecurity and privacy enthusiasts alike for its ability to block not just advertisers and trackers, but also malicious domains. 

[View now at Pi-Hole](https://pi-hole.net/) 

The easiest way to run it is to download Docker Desktop for your operating system ([Windows](https://hub.docker.com/editions/community/docker-ce-desktop-windows), [Mac](https://docs.docker.com/desktop/mac/install/)), or Docker Engine for [Linux](https://docs.docker.com/engine/install/), and then install Pi-Hole into a Docker Container. 

This sounds scarier than it actually is – the Docker Desktop is an easy wizard-based install, and the Pi-Hole part involves issuing a single command line to pull the Pi-Hole repository (docker pull pihole/pihole), and another command line to fire up the container:

> docker run -d --name pihole -e **ServerIP=172.16.154.130** \-e **WEBPASSWORD=password** \-e **TZ=Europe/Copenhagen** \-e **DNS1=1.0.0.1** \-e **DNS2=1.1.1.1** \-e **DNS3=8.8.8.8** \-p 80:80 -p 53:53/tcp -p 53:53/udp -p 443:443 --restart=unless-stopped pihole/pihole:latest

You will want to change the bolded sections to reflect your actual local IP address for ServerIP, the desired password, and the [Time Zone](https://en.wikipedia.org/wiki/List%5Fof%5Ftz%5Fdatabase%5Ftime%5Fzones) (I used America/New\_York). More elaborate instructions for Windows documented by Andrew Denty on his blog [can be found here](https://www.andrewdenty.com/blog/2020/01/25/installing-pi-hole-on-windows-10.html) and Mac can be found in Nathan Alderman's [article at iMore here.](https://www.imore.com/how-run-pi-hole-your-mac)

You will also want to make sure the system you intend to run it on has a static rather than a dynamic IP. The three DNS IP addresses I have chosen here for the Pi-Hole container are the two Cloudflare and Google servers.

Once you have Pi-Hole installed, you'll want to connect via browser to the administrative interface on the system running it. 

Pi-Hole administrative interface

Jason Perlow/ZDNet

As you can see, I have over two million domains set to be blocked. How do you do the same? You go into **Group Management**, choose **Adlist** (this is what Pi-Hole uses to refer to community-sourced lists of domains to be blocked), and then plug in the URL of the Adlist.

Which Adlists should you use? Well, there are many lists you can choose from, all of which have different purposes such as Advertising, Suspected Malware, Malvertising, and others. But I consulted with [Jason Ford](https://twitter.com/jasonford), a principal engineer at a prominent Silicon Valley-based infosec company, and asked him what he used on his Pi-Hole. He was nice enough to [give me his lists](https://github.com/jasonsford/pihole%5Fadlists) and his regular expressions for domain blocking. These include some very popular ones such as [OISD](https://oisd.nl/), [Steven Black](https://github.com/StevenBlack/hosts), and some curated ones from [Firebog](https://v.firebog.net/). 

If you decide to use all of his lists, you'll have over 2 million domains blocked on your Pi-Hole.

Once you have pasted the URLs of the Adlists into the UX, you'll want to go into **Tools** and choose **Update Gravity.** This is what refreshes the local database and populates the blocking engine. 

If there are specific domains you want to block or permit, you want to go into the **Blacklist** or **Whitelist** menus and put them in individually.

To begin using Pi-Hole on your devices and clients, [change your DNS settings](https://www.cnet.com/tech/computing/how-to-change-dns-windows-mac-osx/) to reflect that of the Pi-Hole machine. So, for example, my Pi-Hole is running on my **192.168.1.78** Windows machine – so I've set my Mac and my wife's Windows PC and a few other things to use it as the DNS.

If you find the Pi-Hole is blocking a specific site or functionality that you need to use (such as a needed tracking cookie or script), simply whitelist the site, or temporarily, click on **Disable** from the left-hand administrative menu. You can choose to disable it indefinitely, for 10 seconds, for 30 seconds, for 5 minutes, or a custom time.

**EDIT:** Pi-Hole developer Dan Schaper has communicated the following: "As an aside, we're not aware of any appliances that are planning to embed Pi-hole. Would you be able to share that information? It would be helpful to others to know that there are major changes planned and that some coordination may be in order."

## Hardware Firewalls

While there are many hardware firewall and network intrusion protection products available in the medium/large SMB and the Enterprise space (such as [Cisco Meraki,](https://meraki.cisco.com/products/security-sd-wan/) [Sonicwall](https://www.sonicwall.com/products/firewalls/), [Palo Alto Networks](https://www.paloaltonetworks.com/network-security/next-generation-firewall), [Fortinet](https://www.fortinet.com/solutions/small-business/product-selector), [Ubiquiti](https://store.ui.com/), [Watchguard](https://www.watchguard.com/), and [Sophos](https://www.sophos.com/en-us)), there are very few priced for home and smaller SMBs. What I currently use for myself, my immediate family, and have recommended to friends and colleagues is the [Firewalla](https://firewalla.com/) series of products, which is a company founded by a group of former Cisco engineers.

Firewalla web user interface (dashboard view)

Jason Perlow/ZDNet

I like Firewalla because it is very easy to install, it isn't particularly expensive, and it has no ongoing fees. Unlike the DNS blocking solutions above, it is a true embedded Linux, IP-based rules firewall with advanced intrusion detection capabilities that can monitor every device on your home network. 

Firewalla web interface (flows)

Jason Perlow/ZDNet

Firewalla also has a very good user interface and app for mobile devices for administrating it and receiving alerts and a pretty robust remote management web interface. You don't need to be a network security genius to set rules and protect your network. 

Firewalla mobile device app (iPad)

Jason Perlow/ZDNet

You can certainly do some very granular protections and permissions on a per-device basis and set block lists of different target groups and lots of other things, but for the most part, the default configuration when applied to all devices on the network is likely sufficient for most home users. 

Firewalla's CEO and founder, Jerry Chen, has published a best practices guide ([Part 1](https://help.firewalla.com/hc/en-us/articles/360049374514), [Part 2](https://help.firewalla.com/hc/en-us/articles/360050334233), [Part 3](https://help.firewalla.com/hc/en-us/articles/360049856394-How-to-Secure-Your-Network-with-Firewalla-Part-3-Protect)) that I suggest you review once you get your box running. Additionally, if you are not sure which router mode to use with your Firewalla (Router, Bridge, DHCP, Simple) [read this guide](https://help.firewalla.com/hc/en-us/articles/115004292514-How-does-Firewalla-Intercept-Traffic-Which-Firewalla-mode-to-use-), and if you want to understand how it intercepts network traffic, [read here.](https://help.firewalla.com/hc/en-us/articles/4411167832851-Firewalla-Router-Mode-Configuration-Guide-)

[Firewalla Red](https://firewalla.com/products/firewalla-red) 

**Firewalla Red** is for residences with 100 meg broadband or less. It's a small red box powered by a USB cable that plugs into one of the spare ports of your home broadband router. It uses ARP spoofing or DHCP mode to monitor all your network devices. 

[View now at Firewalla](https://firewalla.com/products/firewalla-red) 

[Firewalla Blue Plus](https://buy.geni.us/Proxy.ashx?TSID=368250&GR%5FURL=https%3A%2F%2Fwww.amazon.com%2FFirewalla-Security-Firewall-Business-Parental%2Fdp%2FB09GLPGDPK%3Fth%3D1%26tag%3Dzd-buy-button-20%26ascsubtag%3D%5F%5FCOM%5FCLICK%5FID%5F%5F%7C0b3bbd23-715c-47da-a818-cfbcec7ce52e%7Cdtp&dtb=1) 

**Firewalla Blue Plus** is for residences with 500 meg broadband or less. In addition to the faster network port and the capabilities of the Red, it has Geo-IP filtering so you can block entire countries off your network, not just IP ranges or domains. It also incorporates a VPN Server, VPN Client, and Site to Site VPN. Because of the Geo-IP filtering, and the currently evolving situation in Eastern Europe, my suggestion is that the Blue Plus should be the minimum considered configuration unless you are really on a budget or have a minimalistic device footprint at home.

[View now at Amazon](https://buy.geni.us/Proxy.ashx?TSID=368250&GR%5FURL=https%3A%2F%2Fwww.amazon.com%2FFirewalla-Security-Firewall-Business-Parental%2Fdp%2FB09GLPGDPK%3Fth%3D1%26tag%3Dzd-buy-button-20%26ascsubtag%3D%5F%5FCOM%5FCLICK%5FID%5F%5F%7C0b3bbd23-715c-47da-a818-cfbcec7ce52e%7Cdtp&dtb=1) 

[Firewalla Purple](https://firewalla.com/collections/firewalla-products/products/firewalla-purple) 

**Firewalla Purple** is for residences with 1 gig of broadband or less. It is the newest product released by the company and is pretty much the ultimate home network defense device you can buy for the money. In addition to the capabilities of the Blue Plus, it is a complete router replacement (which can act in bridge mode if the existing broadband router needs to stay in place) with twin gigabit Ethernet ports. It has a short-range Wi-Fi access point for tethering to a smartphone as backup internet connectivity.

[View now at Firewalla](https://firewalla.com/collections/firewalla-products/products/firewalla-purple) 

[Firewalla Gold](https://firewalla.com/products/firewalla-gold) 

**Firewalla Gold** is a powerful intrusion detection, IP firewall, and multi-gigabit router for SMBs (100 employees or less). Introduced before the Purple, it is essentially a Firewalla Purple on steroids, with four gigabit Ethernet ports, powered by an x86-based chip rather than an Arm-based chip the Purple, Red, and Blue all use. However, it's probably overkill for most homes unless you have a broadband connection with higher than gigabit network traffic requirements.

[View now at Firewalla](https://firewalla.com/products/firewalla-gold) 

## Open Source Firewalls: OPNSense and pfSense

If you are inclined to set up an actual software-based firewall on a border gateway on your premises and want something that is robust but not expensive, then look no further than OPNsense. 

[OPNSense](https://opnsense.org/) 

OPNSense, Hagennos, CC BY-SA 4.0, via Wikimedia Commons

OPNSense is an open source firewall system based on the BSD UNIX operating system (which, in turn, is also forked from other projects such as [pfSense](https://www.pfsense.org) and [m0n0wall](https://m0n0.ch/).) It has the following list of core features:

* Traffic Shaper
* Two-factor Authentication throughout the system
* Captive portal
* Forward Caching Proxy (transparent) with Blacklist support
* Virtual Private Network (site to site & road warrior, IPsec, OpenVPN & legacy PPTP support)
* High Availability & Hardware Failover (with configuration synchronization & synchronized state tables)
* Intrusion Detection and Prevention
* Built-in reporting and monitoring tools including RRD Graphs
* Netflow Exporter
* Network Flow Monitoring
* Support for plugins
* DNS Server & DNS Forwarder
* DHCP Server and Relay
* Dynamic DNS
* Encrypted configuration backup to Google Drive
* Stateful inspection firewall
* Granular control over state table
* 802.1Q VLAN support

[View now at OPNSense](https://opnsense.org/) 

Image: OPNSense, Hagennos, CC BY-SA 4.0, via Wikimedia Commons

[The complete feature list of what this software project can do](https://opnsense.org/about/features/) extends far beyond this list. It is downloadable as a [64-bit x86 ISO](https://opnsense.org/download/) or USB installer image so that you can install it on a PC with (at least two) Ethernet ports. The project also [sells it pre-installed on a hardware appliance](https://shop.opnsense.com/dec600-series-opnsense-desktop-security-appliances/) in multiple configurations, starting with 4-port gigabit networking, a 600mbps IPsec VPN, 16GB of flash storage, 4GB RAM, and a fanless casing and mainboard for 549 EUR.

Similar to OPNSense is [pfSense](https://www.pfsense.org/), which has a comparable feature set and similar hardware requirements. As with OPNSense, pre-configured appliances are available, from as [low as $189 for a small office/branch office configuration](https://shop.netgate.com/products/1100-pfsense). You could certainly use one of these for a home firewall solution, but you'd need a considerable amount of networking and network security experience to administrate it.

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
