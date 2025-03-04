---
title: "Navigating Advanced Authentication Challenges: Top 4 Tips to Fortify Your Network Security | ZDNet"
date: 2025-02-26T18:39:25.036Z
updated: 2025-03-04T20:07:02.395Z
tags:
  - cyber-threats
categories:
  - tech
thumbnail: https://thmb.techidaily.com/755e6887211290e7a3605c3c466915e29d575ef749d02f8bbbc7b8223952f6c6.jpg
---

## Navigating Advanced Authentication Challenges: Top 4 Tips to Fortify Your Network Security | ZDNet

![gettyimages-1199270450](https://www.zdnet.com/a/img/resize/9b8c4462ccb16c6283ee11b3c8dc4061d23a70ad/2024/01/10/52912e1e-32e4-4b1e-b640-21e03ecbd18d/gettyimages-1199270450.jpg?auto=webp&width=1280)

Sarayut Thaneerat / Moment / Getty

_This article was written by Wolfgang Goerlich, advisory CISO at Cisco Duo_

How do I know who you are? It's a simple question without a simple answer. Yet it's at the heart of so many security conversations and decisions we have these days. How does the organization identify its customers? How does any one of us authenticate customer support or the bank when they call us? This process of trusting whoever is on the other end of the phone or the screen is certainly not without risk.

The superficial answer is we check their credentials. The word "credentials" is important here because that's how identity works on the internet. When a request comes in from john@acme.com, though, how do we know that John Smith the human is sitting there at his computer, and not someone else who has intervened? This is the problem with authentication.

To be clear, there are tools to help us overcome these problems. Credentials are traditionally linked to a password, one that only the aforementioned John Smith should know. But passwords aren't ideal – they are often easy to guess, and can be stolen or bought by bad actors. We've adopted techniques like multi-factor authentication (MFA), bolstering the password with a second form of authentication, either proof that you possess a device or a biometric signature. Once relatively obscure, MFA is now ubiquitous; for example, almost all banks enforce MFA at account login. 

But ubiquity has brought its own set of problems. Reports validate [again](https://www.idsalliance.org/white-paper/identity-security-a-work-in-progress-2/) and [again](https://www.verizon.com/business/resources/reports/dbir/2023/introduction/) that more than 70% of breaches include an identity-based component. Considering this fact, we must ask ourselves: Why do authentication efforts continue to fail?

gorodenkoff / iStock / Getty Images Plus

Compromised identity remains a foundational component for most cyberattacks today. To overcome these vulnerabilities, organizations must step up their digital defenses in ways we'll cover here.

## Digital identity is more complicated than ever before

As the internet matured, the complexity of identity increased exponentially. As my colleague and Cisco Fellow Nancy Cam-Winget succinctly put it: "Identity is now an overloaded term." Identity is a credential, an individual. It is a superpower, and identity is a perimeter. It's complicated.

For starters, identities take on many different roles. There are customer identities, workforce identities, contractor identities, vendors, and even third- or fourth-party identities in the supply chain. This proliferation makes it hard to know which identity (and associated privileges) are relevant at any given moment. 

Take the identity of John Smith. In some cases he is a customer, in others he's a worker at Acme Corp, and in others still he may be a third-party consultant for Acme Corp. Each of these identities mean different things and are associated with different relationships and levels of trust. The problem here is that if an attacker gains access to one identity, it can often be easy to access another more valuable identity.

Another problem is the mapping of credentials or identifiers to any given real human identity. Every person is associated with multiple markers across different platforms and applications. For example, jsmith@gmail.com, john@acme.com, and john.smith@acmeconsultants.com might all belong to the same person. These change over the course of a person's lifetime, and accurately distilling which set of identifiers are associated with the right physical person is a challenging problem. If we fail to create accurate links of all identifiers to a real person, their ghost accounts, ripe for exploitation, can continue to wander the halls of our environments. Spooky, indeed.

Identity is also broader than just people. It can also be associated with devices, machines, and even programmatic processes. Organizations ahead of the curve on robotic process automation (RPA) have been early adopters of these emerging problems. We not only need to map possession of devices (i.e. this laptop belongs to John Smith), but now also need to account for and map privileges onto machines working asynchronously to any human oversight.

Tero Vesalainen / iStock / Getty Images Plus

There is no hyperbole when using the word "exponential" when discussing the complexity of the identity environment. The identity attack surface is growing rapidly, along multiple dimensions, simultaneously.

## Authentication is also more complex than ever before

This attack surface would be reason enough to explain the persistence of identity-based security incidents. The problem is further exacerbated by the increasing sophistication of identity-targeted attacks. Whenever a security control is put in place, attackers begin to find ways around, under, or through the protection. The security measure becomes just another part of the landscape that an attacker needs to subvert.

The weaknesses of passwords as an authentication mechanism are well-known. They are cheap to steal, easy to guess, and simple to spray. Even controls like MFA – which to be clear, still dramatically increase friction for attackers – are facing more advanced attacks. At one point, a common belief was that once MFA reached sufficient market adoption this account compromise tactics would disappear. Instead, attackers now expect to deal with the possibility of MFA and develop new ways to address the obstacle.

One way attackers navigate around MFA is with [advanced social engineering](https://duo.com/blog/social-engineering-101-what-it-is-how-to-safeguard-your-organization). At this point, most of us know not to send Nigerian princes any of our retirement savings. When receiving a phone call or text message from our organization's help desk asking for information so they can help with an IT issue, though, we might end up getting duped. The idea of customizing fraudulent requests specifically for a target has become commonplace. It requires the attacker to do slightly more research, such as find the company IT person on LinkedIn, but it pays dividends in attack effectiveness.

Another way to subvert MFA is with a more technical approach like [Adversary-in-the-Middle (AitM)](https://attack.mitre.org/techniques/T1557/). This involves an attacker setting up a fake login site and directing a user there instead of the true site. When the user attempts to login, the attacker simply retrieves all the forms of authentication they need and proceeds to use them at the real site.

Organizations simultaneously face a proliferation of identities and an increase in sophistication of identity-based attacks. The combination certainly contributes to the prevalence of breaches, with identity being a core component.

## What Can Be Done to Defend Identity?

We have made tremendous strides in identification and authentication. Each improvement has bought us time to strengthen other defenses. And yet, whenever a security improvement becomes widely adopted, it quickly becomes widely circumvented.

With that in mind, and with an eye towards continuous improvement, here are four tactical steps to take to improve our defenses.

### No. 1: Increase visibility into the identity perimeter

To defend the identity perimeter, the first important step is to understand it. This means centralizing and organizing all relevant identities and their authentication patterns within an environment. It also means centralizing logging and audit trails. 

It's important for identity visibility to be cross-platform (i.e. any & all user directories) so that discrepancies or gaps can be highlighted. The perimeter will be constantly shifting as the identities are added, removed, or changed, so keeping things organized will be difficult. But work on visibility is work that will provide the baseline for all other defensive measures.

### No. 2: Improve identity posture and implement stronger authentication controls

The starting point of better defense is to deploy the strongest possible authentication.  
Not all MFA is created equal. For example, SMS as a second factor is susceptible to SIM-swap attacks. On the other hand, there are phishing-resistant forms of MFA like a security key or[WebAuthn](https://webauthn.io/) – both of which mitigate AiTM and proxy attacks. By reducing the use of weaker forms of MFA and increasing the use of stronger forms, teams can further improve their identity posture.

The combination of the person's identity and the device's identity is one innovation from FIDO2 (WebAuthn) which can and should be replicated to all requests. Why allow anyone on any of a billion internet-connected devices to login with your credentials? Think of how much the attack surface will be reduced when MFA is restricted to only you logging in on your assigned devices. 

### No. 3: Leverage techniques to detect and respond to suspicious activity at authentication and beyond

Even if posture is improved and stronger forms of MFA are invoked at login, attackers will constantly be looking for new holes to exploit. Therefore, it's important to put in place detection logic and checks for compromise. Ideally, detections should target known attack techniques, but also leverage ML/AI algorithms to detect anomalous or novel suspicious behavior. For example, knowing historical access patterns can highlight when credentials suddenly attempt access from a new device or location.

Put differently, authentication can no longer be only about authentication. The decision to validate a credential must be more than a question of the right password and MFA. It must include the context and conditions of the request, checked and confirmed by policy each time. When identity-based attacks are detected, automated responses should be invoked. This can mean stepping up authentication requirements, revoking access, quarantining an identity until the situation is resolved, or executing more complex responses.

### No. 4: Iterate and improve

The real lesson of MFA bypasses is the lesson we should have learned with password complexity and hashing. Each step we take buys us time while our adversaries determine counter-tactics. Eventually our adversaries will work around our defenses. 

As identities and their associated access patterns change over time, it's important to consistently evaluate the usability and defensibility of our controls. We must enrich identification and authentication, and we must establish a steady practice of improving identity threat detection and response. When we do this, the specter of identity-based threats, while never fully erased, can be minimized.

[Visit duo.com to learn more](http://www.duo.com/)

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
<li><a href="https://fox-info.techidaily.com/new-capturing-movement-with-clarity-implementing-motion-blur-on-peoples-photos-with-picsart/"><u>[New] Capturing Movement with Clarity Implementing Motion Blur on People's Photos with Picsart</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/discover-cutting-edge-gadgets-at-toms-digital-workshop/"><u>Discover Cutting-Edge Gadgets at Tom's Digital Workshop</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-reset-a-locked-nubia-red-magic-9-pro-phone-by-drfone-android/"><u>How to Reset a Locked Nubia Red Magic 9 Pro Phone</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/in-2024-advanced-equipment-guide-top-5-innovative-slow-motion-devices/"><u>In 2024, Advanced Equipment Guide Top 5 Innovative Slow Motion Devices</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-is-pgsharp-legal-when-you-are-playing-pokemon-on-apple-iphone-xr-drfone-by-drfone-virtual-ios/"><u>In 2024, Is pgsharp legal when you are playing pokemon On Apple iPhone XR? | Dr.fone</u></a></li>
<li><a href="https://buynow-help.techidaily.com/is-fintie-the-best-choice-for-securing-your-macbook-pro-13-unveiling-durability-affordability-and-performance-in-our-latest-review/"><u>Is Fintie the Best Choice for Securing Your MacBook Pro 13? Unveiling Durability, Affordability & Performance in Our Latest Review</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/is-the-affordable-netgear-orbi-770-worth-it-examining-quality-vs-price-for-budget-conscious-shoppers/"><u>Is the Affordable Netgear Orbi 770 Worth It? Examining Quality vs Price for Budget Conscious Shoppers</u></a></li>
<li><a href="https://discover-great.techidaily.com/m4vmovwindows/"><u>M4VビデオファイルをMOV形式にWindows環境で変換する手順</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/mastering-modern-technology-essential-reviews-by-the-tomer/"><u>Mastering Modern Technology: Essential Reviews by The Tom'er</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/1723341757587-never-attempt-to-remove-any-penetrating-objects-from-an-eye-injury-it-may-exacerbate-the-damage-or-introduce-infection/"><u>Never Attempt to Remove Any Penetrating Objects From an Eye Injury; It May Exacerbate the Damage or Introduce Infection</u></a></li>
<li><a href="https://games-able.techidaily.com/step-by-step-guide-to-supercharge-your-steam-decks-dock-use/"><u>Step-By-Step Guide to Supercharge Your Steam Deck's Dock Use</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/trustworthy-advice-on-building-your-dream-machine-from-toms-hardware-pioneers/"><u>Trustworthy Advice on Building Your Dream Machine From Tom's Hardware Pioneers</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/ultimate-guide-to-get-the-meltan-box-pokemon-go-for-realme-gt-5-drfone-by-drfone-virtual-android/"><u>Ultimate guide to get the meltan box pokemon go For Realme GT 5 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-and-configure-with-ease-control-panel-steps/"><u>Unlock & Configure with Ease: Control Panel Steps</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/unmatched-precision-meets-pristine-quality-in-the-dough-spectrum-black-an-elite-27-oled-monitor-tailored-for-true-gamers-satisfaction/"><u>Unmatched Precision Meets Pristine Quality in the Dough Spectrum Black - An Elite 27 OLED Monitor Tailored for True Gamers' Satisfaction</u></a></li>
</ul></div>

