---
title: Step-by-Step Tutorial for Manual Google Pixel OS Update Through Sideloaded Files
date: 2024-08-28 13:42:47
updated: 2024-08-29 10:27:52
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
    
##  Sideload the OTA Update

 Your Pixel will reboot following the last command, and you'll see a screen with a sad Android robot lying on his back with a red exclamation mark. To open the hidden recovery menu, press the Volume Up button while holding the Power button.

![Dead Android robot screen.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/05/IMG_8463-650x433-1-650x277.jpg?trim=1,1&amp;bg-color=000&amp;pad=1,1) 

 Now use the Volume Down button to navigate to "Apply update from ADB" option, then press the Power button to select the option.

![Select &quot;Apply update from ADB.&quot;](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/05/IMG_8461-650x433.jpg?trim=1,1&amp;bg-color=000&amp;pad=1,1) 

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
