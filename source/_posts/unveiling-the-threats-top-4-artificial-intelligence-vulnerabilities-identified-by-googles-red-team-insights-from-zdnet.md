---
title: "Unveiling the Threats: Top 4 Artificial Intelligence Vulnerabilities Identified by Google’s Red Team – Insights From ZDNet"
date: 2025-03-03T18:35:46.042Z
updated: 2025-03-04T17:31:27.883Z
tags:
  - cyber-threats
categories:
  - tech
thumbnail: https://thmb.techidaily.com/783d5a68cd1201f00d72d69bc7ad0995ab16e6e244585454342ca9de98074a9b.jpg
---

## Unveiling the Threats: Top 4 Artificial Intelligence Vulnerabilities Identified by Google’s Red Team – Insights From ZDNet

![Cyber attack protection, conceptual illustration.](https://www.zdnet.com/a/img/resize/6ec23cb637587aa23801c99b0472a58a55b8d6ef/2023/08/11/ec9f7b5c-39f1-41d1-9286-1ed71f370959/umbrella.jpg?auto=webp&width=1280)

Andrzej Wojcicki/Science Photo Library via Getty Images

Anytime a new technology becomes popular, you can expect there's someone trying to hack it. Artificial intelligence, specifically generative AI, is no different. To meet that challenge, Google created a 'red team' about a year and a half ago to explore how hackers could specifically attack AI systems. 

"There is not a huge amount of threat intel available for real-world adversaries targeting machine learning systems," Daniel Fabian, the head of Google Red Teams, told [The Register](https://www.theregister.com/2023/08/10/google%5Fai%5Fred%5Fteam%5Flead/) in an interview. His team has already pointed out the biggest vulnerabilities in today's AI systems. 

**Also:** [**How researchers broke ChatGPT and what it could mean for future AI development**](https://www.zdnet.com/article/vulnerabilities-in-chatgpt-and-other-chatbots/)

Some of the biggest threats to machine learning (ML) systems, explains Google's red team leader, are adversarial attacks, data poisoning, prompt injection, and backdoor attacks. These ML systems include those built on large language models, like ChatGPT, Google Bard, and Bing AI. 

#### Newsletters

ZDNET Tech Today

ZDNET's Tech Today newsletter is a daily briefing of the newest, most talked about stories, five days a week.

 Subscribe

[See all](https://www.zdnet.com/newsletters/)

These attacks are commonly referred to as 'tactics, techniques and procedures' (TTPs). 

"We want people who think like an adversary," Fabian told The Register. "In the ML space, we are more trying to anticipate where will real-world adversaries go next." 

**Also:** [**AI can now crack your password by listening to your keyboard clicks**](https://www.zdnet.com/article/ai-can-crack-your-password-by-listening-to-your-keyboard-clicks-heres-how-you-can-stay-protected/)

Google's AI red team recently published [a report](https://services.google.com/fh/files/blogs/google%5Fai%5Fred%5Fteam%5Fdigital%5Ffinal.pdf) where they outlined the most common TTPs used by attackers against AI systems. 

## 1\. Adversarial attacks on AI systems

Adversarial attacks include writing inputs specifically designed to mislead an ML model. This results in an incorrect output or an output that it wouldn't give in other circumstances, including results that the model could be specifically trained to avoid.

**Also:** [**ChatGPT answers more than half of software engineering questions incorrectly**](https://www.zdnet.com/article/chatgpt-answers-more-than-half-of-software-engineering-questions-incorrectly/)

"The impact of an attacker successfully generating adversarial examples can range from negligible to critical, and depends entirely on the use case of the AI classifier," Google's AI Red Team report noted.

## 2\. Data-poisoning AI

Another common way that adversaries could attack ML systems is via data poisoning, which entails manipulating the training data of the model to corrupt its learning process, Fabian explained. 

"Data poisoning has become more and more interesting," Fabian told The Register. "Anyone can publish stuff on the internet, including attackers, and they can put their poison data out there. So we as defenders need to find ways to identify which data has potentially been poisoned in some way."

**Also:** [**Zoom is entangled in an AI privacy mess**](https://www.zdnet.com/article/zoom-is-entangled-in-an-ai-privacy-mess/)

These data poisoning attacks include intentionally inserting incorrect, misleading, or manipulated data into the model's training dataset to skew its behavior and outputs. An example of this would be to add incorrect labels to images in a facial recognition dataset to manipulate the system into purposely misidentifying faces. 

One way to prevent data poisoning in AI systems is to secure the data supply chain, according to Google's AI Red Team report.

## 3\. Prompt injection attacks

Prompt injection attacks on an AI system entail a user inserting additional content in a text prompt to manipulate the model's output. In these attacks, the output could result in unexpected, biased, incorrect, and offensive responses, even when the model is specifically programmed against them.

**Also:** [**We're not ready for the impact of generative AI on elections**](https://www.zdnet.com/article/were-not-ready-for-the-impact-of-generative-ai-on-elections/)

Since most AI companies strive to create models that provide accurate and unbiased information, protecting the model from users with malicious intent is key. This could include restrictions on what can be input into the model and thorough monitoring of what users can submit.

## 4\. Backdoor attacks on AI models

Backdoor attacks are one of the most dangerous aggressions against AI systems, as they can go unnoticed for a long period of time. Backdoor attacks could enable a hacker to hide code in the model and sabotage the model output but also steal data.

"On the one hand, the attacks are very ML-specific, and require a lot of machine learning subject matter expertise to be able to modify the model's weights to put a backdoor into a model or to do specific fine-tuning of a model to integrate a backdoor," Fabian explained.

**Also:** [**How to block OpenAI's new AI-training web crawler from ingesting your data**](https://www.zdnet.com/article/how-to-block-openais-new-ai-training-web-crawler-from-ingesting-your-data/)

These attacks can be achieved by installing and exploiting a backdoor, a hidden entry point that bypasses traditional authentication, to manipulate the model.

"On the other hand, the defensive mechanisms against those are very much classic security best practices like having controls against malicious insiders and locking down access," Fabian added.

Attackers also can target AI systems through training data extraction and exfiltration.

## Google's AI Red Team  

The red team moniker, Fabian explained in a [recent blog post](https://blog.google/technology/safety-security/googles-ai-red-team-the-ethical-hackers-making-ai-safer/), originated from "the military, and described activities where a designated team would play an adversarial role (the 'red team') against the 'home' team."

"Traditional red teams are a good starting point, but attacks on AI systems quickly become complex, and will benefit from AI subject matter expertise," Fabian added. 

**Also:** [**Were you caught up in the latest data breach? Here's how to find out**](https://www.zdnet.com/article/were-you-caught-up-in-the-latest-data-breach-heres-how-to-tell/)

Attackers also must build on the same skillset and AI expertise, but Fabian considers Google's AI red team to be ahead of these adversaries with the AI knowledge they already possess.

Fabian remains optimistic that the work his team is doing will favor the defenders over the attackers.

"In the near future, ML systems and models will make it a lot easier to identify security vulnerabilities," Fabian said. "In the long term, this absolutely favors defenders because we can integrate these models into our software development life cycles and make sure that the software that we release doesn't have vulnerabilities in the first place."

#### Artificial Intelligence

[Photoshop vs. Midjourney vs. DALL-E 3: Only one AI image generator passed my 5 tests](https://www.zdnet.com/article/is-photoshops-new-text-to-image-as-good-as-midjourney-and-dall-e-we-test-it-and-see/ "Photoshop vs. Midjourney vs. DALL-E 3: Only one AI image generator passed my 5 tests")

[AI-powered 'narrative attacks' a growing threat: 3 defense strategies for business leaders](https://www.zdnet.com/article/ai-powered-narrative-attacks-a-growing-threat-3-defense-strategies-for-business-leaders/ "AI-powered 'narrative attacks' a growing threat: 3 defense strategies for business leaders")

[Copilot Pro vs. ChatGPT Plus: Which AI chatbot is worth your $20 a month?](https://www.zdnet.com/article/copilot-pro-vs-chatgpt-plus-which-is-ai-chatbot-is-worth-your-20-a-month/ "Copilot Pro vs. ChatGPT Plus: Which AI chatbot is worth your $20 a month?")

[How my 4 favorite AI tools help me get more done at work](https://www.zdnet.com/article/how-my-4-favorite-ai-tools-help-me-get-more-done-at-work/ "How my 4 favorite AI tools help me get more done at work")

* [Photoshop vs. Midjourney vs. DALL-E 3: Only one AI image generator passed my 5 tests](https://www.zdnet.com/article/is-photoshops-new-text-to-image-as-good-as-midjourney-and-dall-e-we-test-it-and-see/ "Photoshop vs. Midjourney vs. DALL-E 3: Only one AI image generator passed my 5 tests")
* [AI-powered 'narrative attacks' a growing threat: 3 defense strategies for business leaders](https://www.zdnet.com/article/ai-powered-narrative-attacks-a-growing-threat-3-defense-strategies-for-business-leaders/ "AI-powered 'narrative attacks' a growing threat: 3 defense strategies for business leaders")
* [Copilot Pro vs. ChatGPT Plus: Which AI chatbot is worth your $20 a month?](https://www.zdnet.com/article/copilot-pro-vs-chatgpt-plus-which-is-ai-chatbot-is-worth-your-20-a-month/ "Copilot Pro vs. ChatGPT Plus: Which AI chatbot is worth your $20 a month?")
* [How my 4 favorite AI tools help me get more done at work](https://www.zdnet.com/article/how-my-4-favorite-ai-tools-help-me-get-more-done-at-work/ "How my 4 favorite AI tools help me get more done at work")

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
<li><a href="https://video-capture.techidaily.com/new-easy-screen-capture-in-vlc-player-for-2024/"><u>[New] Easy Screen Capture in VLC Player for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-exploring-new-realms-of-engagement-in-facebook-ad-videos/"><u>[New] Exploring New Realms of Engagement in Facebook Ad Videos</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-in-2024-navigating-the-landscape-of-fb-med-ad-optimization/"><u>[New] In 2024, Navigating the Landscape of FB Med Ad Optimization</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-premium-picks-for-pros-top-10-webcams-in-win-11/"><u>2024 Approved Premium Picks for Pros Top 10 Webcams in Win 11</u></a></li>
<li><a href="https://some-tips.techidaily.com/does-sending-and-receiving-the-same-email-twice-in-gmail-consume-more-storage/"><u>Does Sending and Receiving the Same Email Twice in Gmail Consume More Storage?</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/expert-analysis-the-ultimate-guide-to-the-pixio-px2n7-oled-max-top-choice-for-gamers/"><u>Expert Analysis: The Ultimate Guide to the Pixio PX2n7-OLED Max - Top Choice for Gamers</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/explore-top-tech-in-depth-analysis-at-toms-hardware-hub/"><u>Explore Top Tech: In-Depth Analysis at Tom's Hardware Hub</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/gain-a-competitive-edge-optimize-your-site-using-the-cookiebot-platform/"><u>Gain a Competitive Edge: Optimize Your Site Using the Cookiebot Platform</u></a></li>
<li><a href="https://iphone-location.techidaily.com/in-2024-5-ways-change-your-home-address-in-googleapple-map-on-apple-iphone-7ipad-drfone-by-drfone-virtual-ios/"><u>In 2024, 5 Ways Change Your Home Address in Google/Apple Map on Apple iPhone 7/iPad | Dr.fone</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/navigating-tech-trends-with-toms-hardware-comprehensive-gear-evaluations/"><u>Navigating Tech Trends with Tom's Hardware - Comprehensive Gear Evaluations</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/sovol-sv08-speedster-breakdown-honoring-the-legacy-of-voron/"><u>Sovol SV08 Speedster Breakdown: Honoring the Legacy of Voron</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/the-ultimate-resource-for-understanding-toms-tech-hardware/"><u>The Ultimate Resource for Understanding Tom's Tech Hardware</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/toms-tech-review-comprehensive-guides-on-computer-hardware/"><u>Tom's Tech Review - Comprehensive Guides on Computer Hardware</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/unlocking-the-full-power-of-apples-m4-ipad-pro-anticipating-revolutionary-features-at-wwdc-and-the-role-of-artificial-intelligence/"><u>Unlocking the Full Power of Apple's M4 iPad Pro: Anticipating Revolutionary Features at WWDC & The Role of Artificial Intelligence</u></a></li>
</ul></div>

