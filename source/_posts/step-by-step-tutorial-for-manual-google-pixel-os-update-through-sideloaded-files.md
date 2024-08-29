---
title: Step-by-Step Tutorial for Manual Google Pixel OS Update Through Sideloaded Files
date: 2024-08-28T04:21:51.388Z
updated: 2024-08-29T04:21:51.388Z
tags:
  - android
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/10/android-logo-adb.png
---

## Step-by-Step Tutorial for Manual Google Pixel OS Update Through Sideloaded Files

### Quick Links

* [Get Everything Ready](https://graphic-issues.techidaily.com/cutting-edge-visuals-updated-nvidia-geforce-for-windows-10/)
* [Connect Device and Boot into Recovery Mode](https://screen-video-capture.techidaily.com/transform-speech-into-text-the-accurate-google-method/)
* [Sideload the OTA Update](https://android-unlock.techidaily.com/in-2024-how-to-unlock-samsung-galaxy-m34-pattern-lock-if-forgotten-6-ways-by-drfone-android/)

 Google Pixel phones generally get updates before other Android devices, but that's not always the case. There are times when you may want to manually install a firmware update before it arrives over the air. We'll show you how to sideload an OTA update on Pixels.

 In order to do this, we'll be using the Android SDK and running some commands [Command Prompt](https://fox-access.techidaily.com/unleashing-your-cameras-potential-with-top-rated-drones-gimbals-for-2024/) on Windows 10 and 11 and [Terminal](https://bypass-frp.techidaily.com/in-2024-how-to-bypass-frp-from-vivo-s17-by-drfone-android/) on Mac. This is not a terribly difficult process, but if not followed correctly, it can permanently damage your device.

 This process does not wipe your Android device clean. It installs just like any other update. However, it's a good idea to [back up everything](https://facebook-clips.techidaily.com/optimal-mp4-transporter-to-fb-hub/) you might not want to lose if something goes wrong.

##  Get Everything Ready

 Before we start the process, there are a number of things we need to get ready. The first thing you'll need is ADB and "Platform Tools." [Follow the steps in our ADB guide](https://techtrends.techidaily.com/how-to-successfully-obtain-a-refund-for-your-purchased-games-on-steam/) to install the appropriate files and get it all up and running on your Windows or Mac computer.

Related: [How to Install and Use ADB, the Android Debug Bridge Utility](https://techtrends.techidaily.com/how-to-successfully-obtain-a-refund-for-your-purchased-games-on-steam/) 

 Next, we need to turn on USB debugging on your handset. [Enabling USB debugging](https://buynow-tips.techidaily.com/navigating-marvels-team-up-the-truth-behind-the-avengers-ratings/) on Pixels is a simple process that we've outlined in a separate guide.

![Enable USB debugging.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/12/2021-12-27_16-30-01.jpg) 

 The last thing we need is the OTA file for your device. This is the actual update that will be applied to your specific Google Pixel. You can find the latest OTA for your Pixel from [Google's website](https://developers.google.com/android/ota#legal). The latest OTA will be at the bottom of each device's list.

 Be extra sure you are downloading the OTA for the correct Pixel device and mobile carrier.

![Download the OTA file.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/12/2021-12-27_16-33-09.jpg) 

<!-- affiliate ads begin -->
<a href="https://tinyland.pxf.io/c/5597632/1793214/19135" target="_top" id="1793214"><img src="//a.impactradius-go.com/display-ad/19135-1793214" border="0" alt="" width="900" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793214/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  Connect Device and Boot into Recovery Mode

 Okay, now we can really get started. First, connect your Pixel phone to your Windows or Mac computer. You will immediately be asked to "Allow USB Debugging" on your smartphone. Select "Always Allow From This Computer" and tap "OK."

 The "Allow USB Debugging" message might not appear the moment you plug your Pixel into your computer. If it doesn't, continue following the steps below, and the notice should appear once you run the 

        `adb devices`
    
 command.

![Allow USB debugging.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/12/2021-12-27_16-41-02.jpg) 

 Next, on Windows 11 or 10, go to the folder where you downloaded the ADB files. Press Shift on your keyboard and right-click on your mouse simultaneously on a blank area and select "Open Command Windows Here"---or "PowerShell"---from the menu.

![Click "Open Command Windows here."](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/12/2021-12-27_16-56-52.jpg) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4694919&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/jutoh-logo-1200x1600.jpg" border="0">Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. </a>
<!-- affiliate ads end -->
 On Mac, [open](https://bypass-frp.techidaily.com/in-2024-how-to-bypass-frp-from-vivo-s17-by-drfone-android/)[the Terminal app](https://bypass-frp.techidaily.com/in-2024-how-to-bypass-frp-from-vivo-s17-by-drfone-android/) and type 

        `cd "folder destination"`
    
 \---replace "folder destination" with the location of where you saved the ADB files. For example, if the ADB and Platform Tools files were saved to your Downloads folder, you would type in 

        `cd Downloads`
    
 (capitalization matters).

![CD command in Terminal.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/12/image-12.png) 

 In the command or Terminal window, make sure the computer can see the device with the following command. You will see a device listed if everything is working.

 On Mac, the 

        `adb `
    
 command is 

        `./adb`
    
 . Make sure you are using that command everywhere 

        `adb`
    
 is mentioned in the steps below.

        `adb devices`
    
![Device listed in ADB.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/12/2021-12-27_16-57-50.jpg) 

 Next, use this command to reboot the device into recovery:

        `adb reboot recovery`
    
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4615471&QTY=1&AFFILIATE=108875&CART=1"><img src="https://images.wondershare.com/affiliate-image/affiliate_banners_en/max_782x90.png" border="0"></a>
<!-- affiliate ads end -->
##  Sideload the OTA Update

 Your Pixel will reboot following the last command, and you'll see a screen with a sad Android robot lying on his back with a red exclamation mark. To open the hidden recovery menu, press the Volume Up button while holding the Power button.

![Dead Android robot screen.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/05/IMG_8463-650x433-1-650x277.jpg?trim=1,1&amp;bg-color=000&amp;pad=1,1) 

<!-- affiliate ads begin -->
<a href="https://turtlebeacheu.sjv.io/c/5597632/1996818/23722" target="_top" id="1996818"><img src="//a.impactradius-go.com/display-ad/23722-1996818" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1996818/23722" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Now use the Volume Down button to navigate to "Apply update from ADB" option, then press the Power button to select the option.

![Select &quot;Apply update from ADB.&quot;](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/05/IMG_8461-650x433.jpg?trim=1,1&amp;bg-color=000&amp;pad=1,1) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075475/7443" target="_top" id="2075475"><img src="//a.impactradius-go.com/display-ad/7443-2075475" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075475/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Go back to your computer and type the following command. Replace "updatefile.zip" with the name of your OTA file. If the OTA file isn't in the same folder as your ADB files, you can drag it from the File Explorer on Windows or Finder on Mac into the Command Prompt or Terminal.

        `adb sideload updatefile.zip`
    
![Sideload the OTA file.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/12/2021-12-27_17-04-12.jpg) 

<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892107/21290" target="_top" id="1892107"><img src="//a.impactradius-go.com/display-ad/21290-1892107" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892107/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 You'll see a completion percentage while the file is being pushed to your device. When it's finished, the recovery menu will show up again on your phone, with the "Reboot system now" option already highlighted. Hit the Power button to restart your Pixel.

![Progress of installation.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/12/2021-12-27_17-05-14.jpg) 

 That's it! Your Pixel phone will now be running the latest OTA update from Google. This is a much easier process than it used to be, thankfully. Hopefully, you [don't have to do it too often](https://screen-mirror.techidaily.com/how-to-stream-apple-iphone-11-pro-to-computer-drfone-by-drfone-ios/), though.

Related: [How to Manually Check for System Updates on an Android Phone](https://screen-mirror.techidaily.com/how-to-stream-apple-iphone-11-pro-to-computer-drfone-by-drfone-ios/)

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
<li><a href="https://extra-tips.techidaily.com/new-a-hackers-guide-to-scoring-cool-images-at-pexels/"><u>[New] A Hacker's Guide to Scoring Cool Images at Pexels</u></a></li>
<li><a href="https://extra-information.techidaily.com/new-augmented-gaming-experience-the-top-8-list/"><u>[New] Augmented Gaming Experience  The Top 8 List</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-enhance-your-iphone-footage-from-speed-to-extended-muted-visuals-for-2024/"><u>[New] Enhance Your iPhone Footage  From Speed to Extended, Muted Visuals for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-innovative-way-of-merging-gopro-footage-into-continuous-360-degree-narratives/"><u>[New] Innovative Way of Merging GoPro Footage Into Continuous 360-Degree Narratives</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-live-feed-capture-via-obs-for-instagram-for-2024/"><u>[New] Live Feed Capture via OBS for Instagram for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-mastering-cost-effective-visual-integration-in-writing/"><u>[New] Mastering Cost-Effective Visual Integration in Writing</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-ultimate-vivocut-guide-for-enhanced-video-creation/"><u>[New] Ultimate VivoCut Guide for Enhanced Video Creation</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-2024-approved-professional-photographers-pick-of-edits/"><u>[Updated] 2024 Approved  Professional Photographers' Pick of Edits</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-2024-approved-the-quest-for-content-videos-in-social-media-network/"><u>[Updated] 2024 Approved  The Quest for Content  Videos in Social Media Network</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-explore-efficient-two-screen-viewing-on-netflix-for-2024/"><u>[Updated] Explore Efficient Two-Screen Viewing on Netflix for 2024</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-in-2024-discover-the-thrill-panasonics-wearable-actioncam-hx-a1/"><u>[Updated] In 2024, Discover the Thrill  Panasonic’s Wearable ActionCam, HX-A1</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-turning-tidal-wave-of-tiktoks-into-manageable-drafts-through-editing/"><u>[Updated] Turning Tidal Wave of TikToks Into Manageable Drafts Through Editing</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-freelancers-dream-top-free-3d-text-psd-arsenal/"><u>2024 Approved  Freelancer’s Dream  Top FREE 3D Text PSD Arsenal</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-strategic-guide-gain-traction-with-podcast-seo-techniques/"><u>2024 Approved  Strategic Guide  Gain Traction with Podcast SEO Techniques</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-streamline-your-media-collection-with-funimate/"><u>2024 Approved  Streamline Your Media Collection with Funimate</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/a-comprehensive-guide-to-mastering-ipogo-for-pokemon-go-on-apple-iphone-xs-max-drfone-by-drfone-virtual-ios/"><u>A Comprehensive Guide to Mastering iPogo for Pokémon GO On Apple iPhone XS Max | Dr.fone</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/addressing-the-problem-how-msi-is-fixing-the-heat-sink-design-error-in-new-z790-motherboards/"><u>Addressing the Problem: How MSI Is Fixing the Heat Sink Design Error in New Z790 Motherboards</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/asrock-b760m-pro-rs-motherboard-analysis-budget-friendly-with-plenty-of-m2-support/"><u>ASRock B760M Pro RS Motherboard Analysis: Budget-Friendly with Plenty of M.2 Support</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/asus-prime-x670-p-wifi-am5-mobo-exceptional-deal-at-just-135/"><u>Asus Prime X670-P WiFi AM5 Mobo - Exceptional Deal at Just $135!</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/best-in-class-gaming-motherboards-of-2024-find-your-ideal-socket-compatibility-and-chipset-configuration/"><u>Best-in-Class Gaming Motherboards of 2024: Find Your Ideal Socket Compatibility and Chipset Configuration</u></a></li>
<li><a href="https://fox-glue.techidaily.com/branding-beats-technicalities-focus-on-your-streams-signature-style-for-2024/"><u>Branding Beats Technicalities  Focus on Your Stream's Signature Style for 2024</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/breaking-news-amd-patches-zen-2-vulnerability-dont-delay-apply-msis-updated-agesa-120-bios/"><u>Breaking News: AMD Patches Zen 2 Vulnerability - Don’t Delay! Apply MSI's Updated AGESA 1.2.0 BIOS</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/chill-out-with-power-gigabyte-unveils-the-next-gen-golden-cpu-socked-misty-iceberg-design-intelligent-board/"><u>Chill Out with Power: Gigabyte Unveils the Next-Gen Golden CPU Socked Misty Iceberg Design Intelligent Board</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/comprehensive-guide-to-asus-pro-b760m-ct-csm-motherboard-why-choose-a-certified-supermom/"><u>Comprehensive Guide to Asus Pro B760M-CT CSM Motherboard - Why Choose a Certified Supermom?</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/critical-bug-fixes-in-motion-as-amds-partner-brands-update-bios/"><u>Critical Bug Fixes in Motion as AMD's Partner Brands Update BIOS</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/decoding-the-beast-a-deep-dive-into-the-asus-rog-z790-formulas-top-notch-hardware-and-efficient-cooling-mechanisms/"><u>Decoding the Beast: A Deep Dive Into the Asus ROG Z790 Formula's Top-Notch Hardware and Efficient Cooling Mechanisms</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/discover-chinas-longsun-processor-motherboards-and-complete-systems-for-us-market-priced-at-a-low-of-just-373/"><u>Discover China's Longsun Processor Motherboards and Complete Systems for U.S Market, Priced at a Low of Just $373!</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/discover-toms-gadget-guidance-mastering-hardware-solutions/"><u>Discover Tom's Gadget Guidance: Mastering Hardware Solutions</u></a></li>
<li><a href="https://location-social.techidaily.com/edit-and-send-fake-location-on-telegram-for-your-oppo-a1-5g-in-3-ways-drfone-by-drfone-virtual-android/"><u>Edit and Send Fake Location on Telegram For your Oppo A1 5G in 3 Ways | Dr.fone</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/expert-advice-from-toms-pc-world-find-the-perfect-hardware-solutions/"><u>Expert Advice From Tom's PC World: Find the Perfect Hardware Solutions</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/expert-analysis-on-gadgets-at-toms-technology-hub/"><u>Expert Analysis on Gadgets at Tom's Technology Hub</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/expert-insights-on-gadgets-and-hardware-from-toms-hardware/"><u>Expert Insights on Gadgets and Hardware From Tom's Hardware</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/exploring-the-latest-in-technology-with-toms-guide-to-hardware/"><u>Exploring the Latest in Technology with Tom's Guide to Hardware</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/find-your-perfect-pc-part-with-toms-hardware-advice/"><u>Find Your Perfect PC Part with Tom's Hardware Advice</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/future-tech-uncovered-the-upcoming-line-of-certified-msi-z890-and-b860-boards-engineered-for-the-anticipated-intel-arrow-lake-s-chip-sneak-peek-before-compu82/"><u>Future Tech Uncovered: The Upcoming Line of Certified MSI Z890 & B860 Boards Engineered for the Anticipated Intel Arrow Lake-S Chip - Sneak Peek Before Computex 2024 Showcase</u></a></li>
<li><a href="https://network-issues.techidaily.com/hardware-preferences-now-secure/"><u>Hardware Preferences Now Secure</u></a></li>
<li><a href="https://some-techniques.techidaily.com/harnessing-the-full-potential-of-lunapic-artistry-for-2024/"><u>Harnessing the Full Potential of LunaPic Artistry for 2024</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/1723862868318-how-much-will-you-pay-for-elite-gaming-the-declassified-x670e-by-evga-demands-over-1300/"><u>How Much Will You Pay for Elite Gaming? The Declassified X670E by EVGA Demands Over $1,300!</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-oppo-find-x7-ultra-get-deleted-pictures-back-with-ease-and-safety-by-fonelab-android-recover-pictures/"><u>How to Oppo Find X7 Ultra Get Deleted Pictures Back with Ease and Safety?</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-pc-screen-to-poco-x5-pro-phones-drfone-by-drfone-android/"><u>In 2024, How to Mirror PC Screen to Poco X5 Pro Phones? | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-nokia-c32-by-phone-number-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track Nokia C32 by Phone Number | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-lava-yuva-2-to-blackberry-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Lava Yuva 2 to BlackBerry | Dr.fone</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/in-depth-gadget-analysis-by-toms-technology-hub/"><u>In-Depth Gadget Analysis by Tom's Technology Hub</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/in-depth-hardware-analysis-by-toms-technology-experts/"><u>In-Depth Hardware Analysis by Tom's Technology Experts</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/1723862867060-maxsun-debuts-backside-gpu-placement-on-their-latest-mini-itx-motherboard-a-game-changer/"><u>MaxSun Debuts Backside GPU Placement on Their Latest Mini-ITX Motherboard: A Game Changer</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/navigate-through-technology-with-tom-the-hardware-guide/"><u>Navigate Through Technology with Tom: The Hardware Guide</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/pokemon-go-cooldown-chart-on-oneplus-nord-3-5g-drfone-by-drfone-virtual-android/"><u>Pokémon Go Cooldown Chart On OnePlus Nord 3 5G | Dr.fone</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/premier-selection-of-best-indoor-android-games-no-wi-fi-required-for-2024/"><u>Premier Selection of Best Indoor Android Games (No Wi-Fi Required) for 2024</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/the-ultimate-buyers-guide-to-electronics-expertise-from-toms-hardware/"><u>The Ultimate Buyer's Guide to Electronics: Expertise From Tom's Hardware</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/the-unmissable-eyoy-em105-review-exceptional-value-meets-miniaturization-at-105-inches/"><u>The Unmissable EYOY EM105 Review – Exceptional Value Meets Miniaturization at 10.5 Inches</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/the-updated-method-to-bypass-tecno-camon-30-pro-5g-frp-by-drfone-android/"><u>The Updated Method to Bypass Tecno Camon 30 Pro 5G FRP</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/toms-computer-gear-the-ultimate-guide/"><u>Tom's Computer Gear: The Ultimate Guide</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/toms-tech-reviews-in-depth-insights-and-analysis-t17238628805655/"><u>Tom's Tech Reviews: In-Depth Insights and Analysis</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/unveiling-gigabytes-high-end-ice-sports-design-golden-socketed-intel-z790-aorus-xtreme-x-motherboard-featuring-colossal-m2-cooling/"><u>Unveiling Gigabyte's High-End Ice Sports Design: Golden Socketed Intel Z790 Aorus Xtreme X Motherboard Featuring Colossal M.2 Cooling</u></a></li>
</ul></div>
