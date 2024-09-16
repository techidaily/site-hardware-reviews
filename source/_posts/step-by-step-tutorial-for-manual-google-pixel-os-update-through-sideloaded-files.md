---
title: Step-by-Step Tutorial for Manual Google Pixel OS Update Through Sideloaded Files
date: 2024-09-10T16:06:45.638Z
updated: 2024-09-16T16:06:35.104Z
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

##  Connect Device and Boot into Recovery Mode

 Okay, now we can really get started. First, connect your Pixel phone to your Windows or Mac computer. You will immediately be asked to "Allow USB Debugging" on your smartphone. Select "Always Allow From This Computer" and tap "OK."

 The "Allow USB Debugging" message might not appear the moment you plug your Pixel into your computer. If it doesn't, continue following the steps below, and the notice should appear once you run the 

        `adb devices`
    
 command.

![Allow USB debugging.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/12/2021-12-27_16-41-02.jpg) 

 Next, on Windows 11 or 10, go to the folder where you downloaded the ADB files. Press Shift on your keyboard and right-click on your mouse simultaneously on a blank area and select "Open Command Windows Here"---or "PowerShell"---from the menu.

![Click "Open Command Windows here."](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/12/2021-12-27_16-56-52.jpg) 

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
<a href="https://appsumo.8odi.net/c/5597632/2123737/7443" target="_top" id="2123737">
  <img src="//a.impactradius-go.com/display-ad/7443-2123737" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123737/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Sideload the OTA Update

 Your Pixel will reboot following the last command, and you'll see a screen with a sad Android robot lying on his back with a red exclamation mark. To open the hidden recovery menu, press the Volume Up button while holding the Power button.

![Dead Android robot screen.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/05/IMG_8463-650x433-1-650x277.jpg?trim=1,1&amp;bg-color=000&amp;pad=1,1) 

 Now use the Volume Down button to navigate to "Apply update from ADB" option, then press the Power button to select the option.

![Select &quot;Apply update from ADB.&quot;](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/05/IMG_8461-650x433.jpg?trim=1,1&amp;bg-color=000&amp;pad=1,1) 

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123476/16836" target="_top" id="2123476">
  <img src="//a.impactradius-go.com/display-ad/16836-2123476" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123476/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Go back to your computer and type the following command. Replace "updatefile.zip" with the name of your OTA file. If the OTA file isn't in the same folder as your ADB files, you can drag it from the File Explorer on Windows or Finder on Mac into the Command Prompt or Terminal.

        `adb sideload updatefile.zip`
    
![Sideload the OTA file.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/12/2021-12-27_17-04-12.jpg) 

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
<li><a href="https://screen-recording.techidaily.com/new-2024-approved-navigating-the-decision-to-adopt-itop-recording/"><u>[New] 2024 Approved Navigating the Decision to Adopt ITop Recording</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-in-2024-hands-free-strategies-for-logging-online-meetings/"><u>[New] In 2024, Hands-Free Strategies for Logging Online Meetings</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/n-2024-top-10-most-watched-youtube-video-in-24-hours/"><u>[New] In 2024, Top 10 Most Watched YouTube Video in 24 Hours</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-ultimate-eco-conscious-cinematography-setups-guide-for-2024/"><u>[New] Ultimate Eco-Conscious Cinematography Setups Guide for 2024</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-zooming-into-success-syncing-with-fb-live-on-zoom/"><u>[Updated] Zooming Into Success Syncing with FB Live on Zoom</u></a></li>
<li><a href="https://common-error.techidaily.com/1723211260772-step-by-step-guide-to-restore-lost-devices-in-overwatch-quick-resolution-tips/"><u>Step-by-Step Guide to Restore Lost Devices in Overwatch - Quick Resolution Tips!</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/step-by-step-strategies-to-locate-and-retrieve-lost-airpods-devices/"><u>Step-by-Step Strategies to Locate and Retrieve Lost AirPods Devices</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/the-essential-guide-to-external-drives-why-theyre-indispensable-even-with-cloud-backup-options/"><u>The Essential Guide to External Drives: Why They're Indispensable Even With Cloud Backup Options</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/the-rise-of-horizontal-pc-cases-as-the-ultimate-choice-in-motherboard-enclosures-insights-revealed/"><u>The Rise of Horizontal PC Cases as the Ultimate Choice in Motherboard Enclosures – Insights Revealed</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/top-11-essential-smart-home-setups-a-must-have-guide-for-every-household/"><u>Top 11 Essential Smart Home Setups: A Must-Have Guide for Every Household</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/top-7-technology-items-to-avoid-purchasing-this-season/"><u>Top 7 Technology Items to Avoid Purchasing This Season</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/top-microsd-cards-ranked-buyers-guide/"><u>Top MicroSD Cards Ranked : Buyer's Guide</u></a></li>
</ul></div>

