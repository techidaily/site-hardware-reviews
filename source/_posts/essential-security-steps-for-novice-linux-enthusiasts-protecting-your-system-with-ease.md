---
title: "Essential Security Steps for Novice Linux Enthusiasts: Protecting Your System with Ease"
date: 2025-03-03T19:36:34.312Z
updated: 2025-03-04T20:54:36.654Z
tags:
  - cyber-threats
categories:
  - tech
thumbnail: https://thmb.techidaily.com/fea69578f265b77158961ce9649233eee0ace50ab1ad8d0ca655a5decd1786bf.jpg
---

## Essential Security Steps for Novice Linux Enthusiasts: Protecting Your System with Ease

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
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-quick-methods-for-saving-google-voice-communication/"><u>[New] 2024 Approved Quick Methods for Saving Google Voice Communication</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-anonymous-engagement-how-to-watch-instagram-stories-without-profile-reveal-pc-android-iphone/"><u>[Updated] In 2024, Anonymous Engagement How to Watch Instagram Stories without Profile Reveal [PC, Android, iPhone]</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/addressing-the-problem-how-msi-is-fixing-the-heat-sink-design-error-in-new-z790-motherboards/"><u>Addressing the Problem: How MSI Is Fixing the Heat Sink Design Error in New Z790 Motherboards</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/asrock-b760m-pro-rs-motherboard-analysis-budget-friendly-with-plenty-of-m2-support/"><u>ASRock B760M Pro RS Motherboard Analysis: Budget-Friendly with Plenty of M.2 Support</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/asus-prime-x670-p-wifi-am5-mobo-exceptional-deal-at-just-135/"><u>Asus Prime X670-P WiFi AM5 Mobo - Exceptional Deal at Just $135!</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/best-in-class-gaming-motherboards-of-2024-find-your-ideal-socket-compatibility-and-chipset-configuration/"><u>Best-in-Class Gaming Motherboards of 2024: Find Your Ideal Socket Compatibility and Chipset Configuration</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/chill-out-with-power-gigabyte-unveils-the-next-gen-golden-cpu-socked-misty-iceberg-design-intelligent-board/"><u>Chill Out with Power: Gigabyte Unveils the Next-Gen Golden CPU Socked Misty Iceberg Design Intelligent Board</u></a></li>
<li><a href="https://win-able.techidaily.com/civilization-6-wont-start-heres-how-to-fix-it-on-your-windows-10-pc/"><u>Civilization 6 Wont Start? Here's How to Fix It on Your Windows 10 PC</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/crop-circles-the-essential-list-of-farming-games/"><u>Crop Circles The Essential List of Farming Games</u></a></li>
<li><a href="https://hardware-help.techidaily.com/effortless-integration-mastering-the-quick-addition-of-your-surface-dock-driver-today/"><u>Effortless Integration: Mastering the Quick Addition of Your Surface Dock Driver Today</u></a></li>
<li><a href="https://article-files.techidaily.com/essential-6-microphone-selections-for-high-quality-livestreams-for-2024/"><u>Essential 6 Microphone Selections for High-Quality Livestreams for 2024</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/1723862868318-how-much-will-you-pay-for-elite-gaming-the-declassified-x670e-by-evga-demands-over-1300/"><u>How Much Will You Pay for Elite Gaming? The Declassified X670E by EVGA Demands Over $1,300!</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/strategies-seo-efficaces-pour-un-succes-durable-dans-le-partenariat-winxdvd/"><u>Stratégies SEO Efficaces Pour Un Succès Durable Dans Le Partenariat WinXDVD</u></a></li>
</ul></div>

