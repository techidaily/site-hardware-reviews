---
title: Essential Security Practices Every Beginner Ubuntu User Should Know - Insider
date: 2025-02-26T19:14:07.373Z
updated: 2025-03-04T16:44:13.958Z
tags:
  - cyber-threats
categories:
  - tech
thumbnail: https://www.zdnet.com/topic/cyber-threats/    https://www.zdnet.com/a/img/resize/8de73e493176d07b8b02a07544d4158e79c2101e/2023/10/09/e0ce6b74-3b82-43f7-9e95-363efe7bccc6/gettyimages-904833442.jpg?width=170&height=96&fit=crop&auto=webp
---

## Essential Security Practices Every Beginner Ubuntu User Should Know - Insider

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
<li><a href="https://fox-http.techidaily.com/updated-2024-approved-connectivity-at-its-peak-usb-c-and-the-hp-envy-27-monitor/"><u>[Updated] 2024 Approved Connectivity at Its Peak USB-C & the HP Envy 27 Monitor</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-in-2024-giggles-galore-7-entertaining-video-sets-for-chuckleheads/"><u>[Updated] In 2024, Giggles Galore 7 Entertaining Video Sets for Chuckleheads</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-watch-without-limits-15plus-free-apps-to-save-your-favorite-content/"><u>[Updated] Watch Without Limits 15+ Free Apps to Save Your Favorite Content</u></a></li>
<li><a href="https://unlock-android.techidaily.com/7-ways-to-unlock-a-locked-vivo-y28-5g-phone-by-drfone-android/"><u>7 Ways to Unlock a Locked Vivo Y28 5G Phone</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/complete-blueprint-for-tracking-yt-viewsrevenue-for-2024/"><u>Complete Blueprint for Tracking YT Views/Revenue for 2024</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/discover-the-power-an-experts-take-on-the-value-packed-gigabyte-b760m-ds3h-ax-motherboard-for-multi-screen-enthusiasts/"><u>Discover the Power: An Expert's Take on the Value-Packed Gigabyte B760M DS3H AX Motherboard for Multi-Screen Enthusiasts</u></a></li>
<li><a href="https://fox-that.techidaily.com/fix-a-world-without-app-icons-tips-for-iphone-and-ipad-users/"><u>Fix a World Without App Icons: Tips for iPhone & iPad Users</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/imaging-techniques-like-oct-may-be-used-postoperatively-to-confirm-the-success-of-surgical-interventions-such-as-retinal-detachment-repair/"><u>Imaging Techniques Like OCT May Be Used Postoperatively to Confirm the Success of Surgical Interventions Such as Retinal Detachment Repair.</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/1723341683423-surgical-intervention-may-be-necessary-for-certain-types-of-eye-injuries-to-preserve-vision-and-prevent-further-damage/"><u>Surgical Intervention May Be Necessary for Certain Types of Eye Injuries to Preserve Vision and Prevent Further Damage</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/toms-tech-reviews-ultimate-guide/"><u>Tom's Tech Reviews: Ultimate Guide</u></a></li>
<li><a href="https://vp-tips.techidaily.com/top-5-virtual-reality-mishaps-and-prevention-tips/"><u>Top 5 Virtual Reality Mishaps & Prevention Tips</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/ultimate-comparison-guide-for-high-speed-ssds-exploring-the-lexar-professional-sl600-and-sl500-with-remarkable-20g-speed-capabilities/"><u>Ultimate Comparison Guide for High-Speed SSDs: Exploring the Lexar Professional SL600 & SL500 with Remarkable 20G Speed Capabilities</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/unveiling-toms-gear-a-deep-dive-into-technology-and-hardware/"><u>Unveiling Tom's Gear: A Deep Dive Into Technology and Hardware</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/watching-harry-potter-a-perfect-film-series-progression-for-fans/"><u>Watching Harry Potter: A Perfect Film Series Progression for Fans</u></a></li>
</ul></div>

