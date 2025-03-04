---
title: "1. Essential Security Practices Every Beginner in Linux Should Know: A Comprehensive Guide"
date: 2025-02-25T17:28:22.785Z
updated: 2025-03-04T20:51:59.679Z
tags:
  - cyber-threats
categories:
  - tech
thumbnail: https://thmb.techidaily.com/e72d3325cc82dd8ab836962e9def246da610dd4efd3b2a55aada121de71f2e2a.jpg
---

## 1. Essential Security Practices Every Beginner in Linux Should Know: A Comprehensive Guide

![penguins threatening seal](https://www.zdnet.com/a/img/resize/fba2fa5404af40fd68488037c5567d5cacd23987/2023/10/09/e0ce6b74-3b82-43f7-9e95-363efe7bccc6/gettyimages-904833442.jpg?auto=webp&width=1280)

Richard McManus/Getty Images

It is no secret that [Linux is a far more secure option than Windows](https://www.zdnet.com/article/if-youre-looking-to-up-your-desktop-computer-security-linux-might-be-your-best-bet/). From the ground up, Linux was designed to be highly secure. Since I started using Linux (back in '97), I've only had one cybersecurity threat arise, which was a rootkit on a server I inherited. Sadly, that server was so badly compromised that I had to re-install the OS and start from scratch.

That was the only instance, in decades, of having to suffer the consequence of a security breach. Otherwise, it's been smooth sailing.

**Also:** [**The best VPN services (and how to choose the right one for you)**](https://www.zdnet.com/article/best-vpn/)

You, too, can enjoy the heightened security that comes with the Linux OS. However, you shouldn't just assume that you can install Linux and never worry about security again. My take on security is if a device is connected to a network, it's vulnerable. 

To that end, I thought I'd share some advice that even those who are brand new to Linux can easily follow. Don't worry, I'm not going to have you editing init scripts, issuing complicated _iptables_ commands, or installing software like fail2ban. Instead, this is all about what new users can do to help prevent malware, ransomware, or other attacks.

#### Newsletters

ZDNET Tech Today

ZDNET's Tech Today newsletter is a daily briefing of the newest, most talked about stories, five days a week.

 Subscribe

[See all](https://www.zdnet.com/newsletters/)

If you're a Linux admin, this might be a good thing to share with end users who are using Linux as their daily driver operating system.

With that said, let's get to the tips.

## 1\. Upgrade regularly

This is the first piece of advice I give to any user, regardless of the operating system they use and I'm always shocked at how many people ignore it.

**Also: [6 simple cybersecurity rules to live by](https://www.zdnet.com/article/6-simple-cybersecurity-rules-to-live-by/)**

You see, upgrades aren't just about getting new features. More important in those upgrades are the security patches that address vulnerabilities. I check (and apply) updates daily. Sometimes those updates are minor but other times they include crucial patches that fix critical Common Vulnerabilities and Exposures (CVEs). 

No matter what Linux distribution you've chosen, check daily (at best) or weekly for updates. As soon as you see updates available, apply them and (if the kernel is upgraded) reboot when the process completes.

## 2\. Don't install apps from unknown sources

Similar to the advice I give to Android users, the safest thing you can do is only install applications from the built-in package manager(s). Whether your system uses apt, dnf, snap, flatpak, pacman, or zypper, I would highly recommend you only install apps using those methods.

**Also: [New cryptographic protocol aims to bolster open-source software security](https://www.zdnet.com/article/new-cryptographic-protocol-aims-to-bolster-open-source-software-security/)**

I know what you're thinking: That removes a world of applications that can be installed. Although that's true, I always recommend the "safe over sorry" method when it comes to installing software.

Sure, you might find an app you really want to install that isn't found in the standard repositories. If that's the case, check to see if it's available as either a [Snap or Flatpak](https://www.zdnet.com/article/why-snap-and-flatpak-make-linux-a-better-os-for-the-average-user/) package. If so, install with one of those methods. If not, and you seriously need that app, do a bit of research to see if the repository can be trusted.

It only takes the installation of one rogue app to compromise a system. A bit of caution can help you avoid such a problem.

## 3\. Use a strong password

It's your desktop, not a server. Right? Although that may be true, it doesn't mean you should continue using _password_ or _12345678_ as your password. There are a couple of things you should keep in mind when setting your user password:

* Network attacks
* Prying eyes

The most likely cybersecurity breach on a desktop is someone logging into your computer and accessing your information. But just because you're using a desktop doesn't mean it can't be breached by a threat actor who's gained access to your network. 

**Also: [The best password managers](https://www.zdnet.com/article/best-password-manager/)**

Because of that, it's essential that you use a strong/unique password. Remember, that password isn't only required to log into your desktop but to run upgrades, install apps, and handle other admin tasks.

## 4\. Don't use Chrome

Most Linux distributions default to either the Firefox web browser or Chromium. Although Chrome is available to easily install on the open-source operating system (and is the [most widely-used web browser](https://www.zdnet.com/home-and-office/networking/chrome-is-obviously-the-top-browser-but-you-wont-believe-whats-2/) on the planet), it's also one of the least secure. 

**Also: [How to use Tor browser (and why you should)](https://www.zdnet.com/article/how-to-use-tor-browser-and-why-you-should/)**

If you check out our list of [most secure browsers for 2023](https://www.zdnet.com/article/best-browser-for-privacy/), you'll notice that Chrome is nowhere to be found. On that list you'll find Brave, Firefox, Tor, DuckDuckGo, and Mullvad. Of those browsers, I would suggest either Firefox or Tor for Linux. 

## 5\. Enable your firewall

It might come as a surprise to you but some Linux distributions ship without the firewall enabled. For example, many distributions based on Ubuntu do not enable Uncomplicated Firewall out of the box. And most of the popular Ubuntu-based Linux distributions also don't ship with a firewall GUI. 

To avoid having to run commands (although enabling UFW from the command line is as simple as _sudo ufw enable_), you could install the gufw GUI app (which can be installed from your distribution's app store). Once installed, you can enable the firewall by switching the On/Off slider to the On position.

Gufw is one of the simplest firewall GUIs you'll ever use.

Jack Wallen/ZDNET

After you've enabled the firewall, you can enable any service (such as SSH or Samba) that you need to allow in, without having to run commands (such as _sudo ufw allow ssh_). 

## 6\. Never log in as root

Although Ubuntu-based distributions disable the root account, some distributions (such as Debian and Fedora) leave it enabled, so you could easily log in as the root user and do whatever you want without having to worry about sudo. 

**Also: [Linux security: What is sudo and why is it so important?](https://www.zdnet.com/article/why-sudo-is-so-important-in-linux-and-how-to-use-it/)**

This is not good. If you log in as the root user, you open a hyper-privileged account. Should anyone breach your system, they too would have unfettered access to every service, app, and all of the data you've stored.

To that end, never log in as the root user. Ever. Always use _sudo_ for admin tasks, so as to not leave your system open to heightened attacks.

## 7\. Use Full Disk Encryption

If you're the one installing Linux on your machine, and your distribution of choice offers Full Disk Encryption (FDE), your best bet is to opt in. Why? Simple. Say someone were to steal your laptop. Without full disk encryption, they could remove the drive, mount it on another machine (which would avoid having to crack your user password) and have at the data within.

With FDE enabled, if that threat actor were to remove your drive and attempt to mount it, they would be unsuccessful, unless they knew your encryption password. Of course, this also isn't a guarantee. Remember the old saying, where there's a will, there's a way. But if you enable FDE, you'll make it considerably harder for someone to access your data without that encryption password.

## Conclusion

You don't have to be a sysadmin to keep your Linux desktop distribution safe from cybersecurity threats. Follow these pieces of advice and you'll go a long way to keeping all of the data you have on your machine safe from attacks.

#### Linux

[The best Linux laptops for consumers and developers](https://www.zdnet.com/article/best-linux-laptop/ "The best Linux laptops for consumers and developers")

[Want to save your aging computer? Try these 5 Linux distributions](https://www.zdnet.com/article/want-to-save-your-old-computer-try-these-5-linux-distributions/ "Want to save your aging computer? Try these 5 Linux distributions")

[The best distros for beginners](https://www.zdnet.com/article/best-linux-desktops-for-beginners/ "The best distros for beginners")

[How to enable Linux on your Chromebook (and why you should)](https://www.zdnet.com/article/how-to-enable-linux-on-your-chromebook-and-why-you-should/ "How to enable Linux on your Chromebook (and why you should)")

* [The best Linux laptops for consumers and developers](https://www.zdnet.com/article/best-linux-laptop/ "The best Linux laptops for consumers and developers")
* [Want to save your aging computer? Try these 5 Linux distributions](https://www.zdnet.com/article/want-to-save-your-old-computer-try-these-5-linux-distributions/ "Want to save your aging computer? Try these 5 Linux distributions")
* [The best distros for beginners](https://www.zdnet.com/article/best-linux-desktops-for-beginners/ "The best distros for beginners")
* [How to enable Linux on your Chromebook (and why you should)](https://www.zdnet.com/article/how-to-enable-linux-on-your-chromebook-and-why-you-should/ "How to enable Linux on your Chromebook (and why you should)")

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
<li><a href="https://facebook-video-files.techidaily.com/new-the-pano-way-to-online-visibility-posting-360-photos-through-mobile-apps/"><u>[New] The Pano-Way to Online Visibility Posting 360 Photos Through Mobile Apps</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/comparing-giants-in-tech-can-you-find-the-right-fit-for-an-iphone-or-android/"><u>Comparing Giants in Tech: Can You Find the Right Fit for an iPhone or Android?</u></a></li>
<li><a href="https://win-able.techidaily.com/how-to-get-your-snap-camera-working-again-simple-fixes/"><u>How to Get Your Snap Camera Working Again - Simple Fixes</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/mastering-computer-hardware-with-expert-tips-from-toms-systems-guides/"><u>Mastering Computer Hardware with Expert Tips From Tom's Systems Guides</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/mastering-hardware-choices-through-toms-comprehensive-analysis/"><u>Mastering Hardware Choices Through Tom's Comprehensive Analysis</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/mastering-the-tech-world-insights-from-toms-gear-analysis/"><u>Mastering the Tech World: Insights From Tom's Gear Analysis</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/msi-unveils-top-tier-z890-and-b8n60-boards-for-intel-arc-s-certified-before-the-excitement-of-computex-2024-begins/"><u>MSI Unveils Top-Tier Z890 and B8n60 Boards for Intel Arc S, Certified Before the Excitement of Computex 2024 Begins!</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/msis-pre-computex-2024-launch-premium-z890-and-b860-motherboards-for-intel-arc-s-system-leak-detected/"><u>MSI's Pre-Computex 2024 Launch: Premium Z890 and B860 Motherboards for Intel Arc S System Leak Detected</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/navigating-from-armory-crate-to-advanced-illumination-with-microsoft-and-asus-collaborative-bios-enhancement/"><u>Navigating From Armory Crate to Advanced Illumination with Microsoft and Asus' Collaborative BIOS Enhancement</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/navigating-hardware-solutions-with-toms-reviews/"><u>Navigating Hardware Solutions with Tom's Reviews</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/navigating-new-innovations-in-computing-a-guide-by-toms-hardware/"><u>Navigating New Innovations in Computing - A Guide by Tom's Hardware</u></a></li>
<li><a href="https://sound-issues.techidaily.com/no-noise-from-your-speakers-on-apex-legends-these-fixes-can-help/"><u>No Noise From Your Speakers on Apex Legends? These Fixes Can Help!</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/the-essential-5-points-to-think-about-prior-to-purchasing-a-fitness-device/"><u>The Essential 5 Points to Think About Prior to Purchasing a Fitness Device</u></a></li>
<li><a href="https://technical-tips.techidaily.com/the-ultimate-troubleshooting-techniques-for-dealing-with-a-lost-binkw32dll-file/"><u>The Ultimate Troubleshooting Techniques for Dealing with a Lost Binkw32.dll File</u></a></li>
<li><a href="https://fox-blue.techidaily.com/tomtom-bandit-action-camera-review/"><u>TomTom Bandit Action Camera Review</u></a></li>
<li><a href="https://discover-data.techidaily.com/una-guia-exhaustiva-para-dominar-la-sincronizacion-del-kernel-en-una-mac/"><u>Una Guía Exhaustiva Para Dominar La Sincronización Del Kernel en Una Mac</u></a></li>
<li><a href="https://discover-community.techidaily.com/windows-11-update-fehler-losung-fur-nicht-installierbare-version-auf-deinem-computer/"><u>Windows 11 Update Fehler: Lösung Für Nicht Installierbare Version Auf Deinem Computer</u></a></li>
</ul></div>

