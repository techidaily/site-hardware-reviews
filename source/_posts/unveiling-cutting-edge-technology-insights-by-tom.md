---
title: Unveiling Cutting-Edge Technology Insights by Tom
date: 2024-08-18T11:59:45.090Z
updated: 2024-08-19T11:59:45.090Z
tags:
  - laptop
categories:
  - hardware
thumbnail: https://cdn.mos.cms.futurecdn.net/AV9Ce3UoJLyHCed8rS4oG3-320-80.jpg
---

## Copilot+ Showcases Cutting-Edge Snapdragon Notebooks: Join Our Live Testing Event

Refresh

 June 18, 2024 at 10:29 PM

**Slow Setup Begins**

 So we're in the middle of setting up our Surface Laptop 15-inch with Snapdragon Elite X CPU and it is taking . . . forever. As part of the OOBE (Out of the Box Experience), Windows 11 demanded to run updates, which it claims will take 30 minutes.

 During the update process, we've been treated to promotional images of the various Copilot+ PC features. Of the Recall feature, the OOBE says it's "coming soon."

 Image 1 of 3

![cocreator image](https://vanilla.futurecdn.net/cyclingnews/media/img/missing-image.svg)

 (Image credit: Tom's Hardware)

![mickey mouse smoking](https://vanilla.futurecdn.net/cyclingnews/media/img/missing-image.svg)

 (Image credit: Tom's Hardware)

![concentration camp](https://vanilla.futurecdn.net/cyclingnews/media/img/missing-image.svg)

 (Image credit: Tom's Hardware)

 June 19, 2024 at 12:12 AM

## Early testing of Asus Vivobook S15 debuts

![Asus Vivobook S15 on a wooden table](https://cdn.mos.cms.futurecdn.net/J6H2dtCYE36NVCh4cr9QMT-320-80.jpg)

 (Image credit: Future, Windows Central)

 A few outlets, including[_**Tom's Guide**_](https://www.tomsguide.com/computing/laptops/asus-vivobook-s-15-snapdragon-x-elite-review) and[_**Windows Central**_ **,**](https://www.windowscentral.com/hardware/laptops/asus-vivobook-s-15-copilot-pc-review) have posted hands-on and early testing of the Asus Vivobook S15\. The latter has a full review, which it gave 4.5 out of 5 stars.  
  
 Both sites praised the Snapdragon X Elite's performance (specifically, the 45W TDP X1E78100), as well as the 15.6-inch OLED display. While_Windows Central_ deemed the battery life just "good,"_Tom's Guide_ called it "mind-blowing."  
  
_TG_ listed the following benchmark scores, which it says aren't from its official lab testing:  
  
 Geekbench 6 single-core: 2,418  
 Geekbench 6 multi-core: 14,352  
 Handbrake: 6:50  
  
 All of these scores and times were faster than the M3 MacBook Air the site tested._WC_ also found it trading blows with certain modern Intel and AMD processors in some tests. Neither site was able to test the NPU, partially due to driver issues.  
  
_WC_ also points out that Arm emulation is better than ever with far more compatibility than before, though it still had issues with Adobe Premiere. Additionally, while a few games loaded well, others couldn't be installed or would refuse an ARM CPU.  
  
 Check out both sites' reviews and hands-ons for more.

 June 19, 2024 at 12:58 AM

 **Paint's Cocreator Requires Internet Connection, Doesn't Follow Instructions**

![Paint Cocreator](https://cdn.mos.cms.futurecdn.net/JHh8cycEABpaZjJJJLtEWa-320-80.png)

 (Image credit: Tom's Hardware)

 We just tried Cocreator, a new Windows Paint feature that is one of the four big new features Microsoft offers exclusively for Copilot+ PCs. It's a a button in Paint that lets you generate images based on a combination of your drawings and a text prompt.

 Color us unimpressed with the feature. Not only does it not follow directions to a T, it also turns out to require an Internet connection as you can see above. While Microsoft never explicitly said that its new Copilot+ features would work offline, it seems ridiculous that these features require a system with a powerful NPU but then send their data to the cloud anyway.

![Paint Cocreator](https://cdn.mos.cms.futurecdn.net/4gbVXSpKFgBU7qeTLDVPGQ-320-80.png)

 (Image credit: Tom's Hardware)

 So how does it work? We hit the Cocreator button in the upper right corner of the screen, which is not to be confused with the "Image Creator" button that does something similar but is not exclusive to Copilot+ PCs. You're then shown a sidebar that tells you to "describe the image you'd like to create" and invites you to draw something. So you HAVE TO do both. You can't just give a text prompt and you can't just draw something.

 Just want to use text prompts? That's what Image Creator is for, but Image Creator not only requires the cloud, but also has a limited number of tokens you can use (50 by default) before you run out and presumably have to pay for extras.

 I wanted to get a picture of a cat driving a car so I drove a circle, a line and an oval with two wheels on it. I used the prompt "cat driving a car," but Cocreator didn't exactly follow my directions, showing just a plain cat with something under its arm. When I changed the prompt to "cat on a skateboard," I got a blurry skateboard below my cat.

![Paint Cocreator](https://cdn.mos.cms.futurecdn.net/An3VinrkVR68J3pTCq957e-320-80.png)

 (Image credit: Tom's Hardware)

 I had the Windows Task Manager open and watched as the NPU surged to 100 percent for a couple of seconds while Cocreator was redrawing. So it is using the processor, even though it won't work without an Internet connection.

 Incidentally, Cocreator is not close to immediate. When changing the prompt or the drawing, there was a lag of two to three seconds for redrawing. This is undoubtedly better than we've seen for something like Stable Diffusion on other systems, but it's still annoying if you're in a creative process.

_\-- Avram Piltch_

 June 19, 2024 at 2:08 AM

 **Paint Cocreator will draw a concentration camp, other controversial images**

 So we asked someone at Qualcomm why Paint Cocreator has to hit the Internet in order to generate an image. After all, isn't the point of the Snapdragon Elite X and its 45 TOPS NPU that it can do all the image generation offline? The answer we got is that Microsoft wants to make sure that you don't use prompts that would generate hateful or controversial images.

 I don't understand why Microsoft can't block bad prompts locally. Lots of people run Stable Diffusion locally and there are some chatbots that run locally so why can't Windows have the list of forbidden prompts stored locally as well?

 But guess what! Even though Cocreator blocks some bad prompts -- for example, it won't draw Hitler -- there are plenty of prompts it lets through. Granted, the quality of images is so awful that they may not be recognizable as what you asked for, but it will still do what you asked.

 For example, I asked Cocreator to draw a "concentration camp" and it drew a black and white camp area with some people walking through it. Could you tell that this was a concentration camp if you didn't read the prompt? Probably not.

 I also asked for "german camp ww2 jewish" and got a similar image. "German crematorium camp" showed some people lined up outside a smokey building, but if you didn't know what the prompt was, could you tell?

 Image 1 of 3

![cocreator image](https://vanilla.futurecdn.net/cyclingnews/media/img/missing-image.svg)

 (Image credit: Tom's Hardware)

![mickey mouse smoking](https://vanilla.futurecdn.net/cyclingnews/media/img/missing-image.svg)

 (Image credit: Tom's Hardware)

![concentration camp](https://vanilla.futurecdn.net/cyclingnews/media/img/missing-image.svg)

 (Image credit: Tom's Hardware)

 I also asked for Mickey Mouse smoking and, most of the time, I got weird things that were not recognizable as mickey mouse or as smoking. But this image does show Mickey with something long in his hand.

![mickey mouse smoking](https://cdn.mos.cms.futurecdn.net/4UAprbCUwcCsh96gaESpJ3-320-80.png)

 (Image credit: Tom's Hardware)

 Perhaps the worst image I saw was when I entered the prompt "jew angry" or "jewish angry." Here I got someone who looked literally like the devil. And "jewish boss angry" was a man with a big nose and devil ears.

 Image 1 of 2

![jewish boss angry](https://vanilla.futurecdn.net/cyclingnews/media/img/missing-image.svg)

 (Image credit: Tom's Hardware)

![jewish angry](https://vanilla.futurecdn.net/cyclingnews/media/img/missing-image.svg)

 (Image credit: Tom's Hardware)

 Anyway, if Microsoft's goal is to prevent its tool from generating biased or embarrassing content, it's not working.

_\-- Avram Piltch_

 June 19, 2024 at 3:40 AM

 **Snapdragon Laptop bests Intel in Handbrake, Falls behind in Geekbench ML**

 One real-world test we perform on every laptop is using Handbrake, a popular video encoding app, to transcode a 4K video into a 1080p clip. Fortunately, unlike so many apps, Handbrake already has a native Windows on Arm version so the Snapdragon X Elite chip, specifically an X Elite X1E-80-100, in our Surface Laptop 15-inch doesn't have to go into emulation to run it.

 As elsewhere, we're comparing the Surface Laptop's score to that of a ThinkPad X1 Carbon with Core Ultra 7 155H CPU. The Ultra 7 155H is part of Intel's current-gen Meteor Lake platform, which has a slower NPU than the Snapdragon X Elite (10 TOPS vs 45 TOPS), but has a much faster boost clock (4.8 GHz versus 4.0 GHz).

 So how did the Snapdragon X Elite chip fare? It actually was way, way faster than Intel's offering, completing the task in an average 4 minutes and 55 seconds of~~2 minutes and 39 seconds~~ versus 8 minutes and 57 seconds for the Intel chip. Update: We made a mistake using the wrong source file for the initial round of Snapdragon tests, but that has been corrected. It is still much faster than Intel's offering, but not quite as fast as we thought.

![Snapdragon X Elite vs Intel Ultra 7](https://cdn.mos.cms.futurecdn.net/Xe7diDdFrCChvvY9cUxjEa-320-80.png)

 (Image credit: Tom's Hardware)

 While we wouldn't call video transcoding an AI workload, it's clear that Qualcomm does a much better job of handling this task.

 Speaking of AI workloads, we also tried Geekbench ML, a relatively new synthetic benchmark that measures inference speed. Geekbench ML claims that it has[one single version](https://www.geekbench.com/ml/download/) for Windows x86 and Windows on Arm. I'm skeptical about whether Geekbench ML is truly optimized for Arm, because normally you need a different installer for Arm compiled apps. If it's not optimized for Arm, then the Snapdragon chip could be running in emulation mode, which definitely would slow it down.

 When we ran Geekbench ML, which measures overall machine learning, we selected DirectML as our inference backend so the system can then at least utilize the GPU rather than the CPU for processing (CPUs are always the slowest). Anyway, in this case, Intel's chip won 2834 to 2160\.

![Snapdragon X Elite vs Intel Ultra 7](https://cdn.mos.cms.futurecdn.net/4MxhSk3S2RPfUBUx24UygT-320-80.png)

 (Image credit: Tom's Hardware)

Overall, those are promising video numbers for Qualcomm, however.

 June 19, 2024 at 5:45 AM

**Painful Reminder: Windows 11 is Full of Ads**

 This probably goes without saying, but I'll say it here: Windows 11 is festooned with annoying ads. Setting up the Surface Laptop 15 fresh out of the box, I was reminded just how hard Microsoft tries to sell you things.

 Today, I was pestered by the operating system three different times to sign up to XBox Game Pass, a $16.99 a month service that lets you play games. First, during the OOBE (out of the box experience), Windows asked me to sign up for the service.

 Then, after I first got the system set up, I did not see the Codesigner feature in Windows Paint so I launched the Microsoft Store app in hopes of updating Paint. There was no update there (a reboot later mysteriously made my Paint update), but there was an extremely-annoying, uncloseable ad for -- you guessed it -- XBox Game pass.

![Xbox Game Pass Ultimate](https://cdn.mos.cms.futurecdn.net/Y4jEVXMrDT4SdvLrGdUxKk-320-80.png)

 (Image credit: Future)

 The Library section of the Microsoft Store is where you can see a list of all your Store apps and which ones need to be updated. Here, covering over part of my list of apps was a Game Pass ad with no close button. I could hit "Claim" and sign up for a free trial (after which I'd have to pay) or "more details" to get more promotional material. I hit "More details" and, even then, a Game Pass promotion remained on screen in my library.

 But wait, there's more! Later, I got a Windows notification asking me to sign up for Game Pass Ultimate. Why can't Microsoft take no for an answer? I guess it's hoping to fool users into giving their credit cards for a free 14-day trial and then forgetting to unsubscribe.

![Xbox Game Pass](https://cdn.mos.cms.futurecdn.net/v9Ehw4FrqgctBhSQEpcJch-320-80.png)

 (Image credit: Future)

 Also, on the lock screen, I got an ad for playing Candy Crush, a preloaded free-to-play game that tries to hook you and get you to spend a lot of money on microtransactions.

![Lock screen](https://cdn.mos.cms.futurecdn.net/WFSQFPLk87n4xivTTRQ7Xo-320-80.jpg)

 (Image credit: Future)

 June 19, 2024 at 9:54 AM

**Pardon me while I tear my remaining hair out!**

 One of the big challenges of working with any Windows on Arm device, let alone a brand new one, is compatibility. The thing I want to test most on a Snapdragon X1 Elite-powered laptop is its ability to run real-world AI workloads using models such as Whisper AI and Stable Diffusion.

 Stable Diffusion is a popular text-to-image model that can be run locally. Whisper AI is a free speech-to-text model from OpenAI that allows you to feed your computer an audio file and get back a transcript. This is a very helpful use of AI if you're a journalist like me and you're doing interviews or watching press announcements. And it's also great if you're a student recording a lecture from your teacher.

 Whisper AI can run in various programming languages, but the easiest to work with (though not necessarily the fastest) is Python. So, in preparing for our first day of testing, I benchmarked Whisper AI's base model on our Intel Core Ultra 7 155H-powered ThinkPad. It took 1 minute and 13 seconds to transcribe an 11-minute audio clip. This was using a short Python script that I wrote.

 Unfortunately, it's not so easy to get Whisper AI to run on a Snapdragon laptop, even though Qualcomm has the[Whisper Base model in its AI Hub](https://github.com/quic/ai-hub-models/tree/main/qai%5Fhub%5Fmodels/models/whisper%5Fbase%5Fen) . I just spent the past 4 hours trying to get this model to work, but it looks like -- after extensive effort -- that it may be impossible.

 The[instructions](https://github.com/quic/ai-hub-models/tree/main/qai%5Fhub%5Fmodels/models/whisper%5Fbase%5Fen) only describe how to run a quick demo, which transcribes a one-sentence audio clip that Qualcomm has chosen. There doesn't seem to be a way to deploy and use Qualcomm's Whisper for an actual Python script in which the user can supply their own audio file. It looks like this was made as a proof of concept and not for serious development as the documentation and examples only show you how to convert the sample audio.

 I'm also trying to use the standard Whisper AI python library, which is not maintained by Qualcomm. But that isn't working on this hardware. It gives a Numpy error because apparently Whisper requries Numpy, a popular Python library, that's less than version 2\. But Numpy less than version 2 won't install on Arm64 hardware, at least as far as I can tell.

 I'm still working on these problems, but the level of difficulty and awful documentation suggests that it may not be possible to build working AI apps in Python for Snapdragon. Qualcomm's AI hub is full of[proofs of concepts](https://aihub.qualcomm.com/compute/models) of hundreds of models, from those that to image generation to pose estimation to transcription and yet, instead of showing users how to actually use these models in applications, it offers demos with its own pre-chosen audio, images, etc. Intel actually has useful libraries and documentation, however poorly written, for its OpenVINO libraries. Qualcomm, not so much. I'm very frustrated.

 June 19, 2024 at 10:33 PM

**On to Day 2 of testing with many problems to solve**

![Copilot+_ PC at Best Buy](https://cdn.mos.cms.futurecdn.net/nK4M5CQHSiFXJcncejQnWS-320-80.jpg)

 (Image credit: Future)

 And we're back. After a frustrating several hours of attempting -- and failing -- to get Whisper AI running on a Snapdragon-powered laptop, I took a break for the evening and was so annoyed that I had to step away from all screens for about 12 hours.

 Today, we're going to continue our attempts to test the Snapdragon X Elite on a Surface Laptop 15 and a Surface Pro 2-in-1\. Overnight, I also learned about a few other frustrations we have to deal with in this process:

* **Battery tests don't work:**  Our lab folks have been attempting to run battery tests on a variety of Snapdragon laptops, including the Surface Pro, and of three different tests, all failed to run. First, our own Battery Informant test, which is written in C# .NET and surfs the web using Edge, failed to open at all. Then they tried PCMark10's battery test and it refused to run. Finally, the[Procyon](https://benchmarks.ul.com/procyon) battery test failed after an hour because it requires you to install Outlook, which we don't have for Arm (perhaps someone can get it, but it's not even part of our Office 365 package).
* **Geekbench ML Not optimized:** Qualcomm emailed us to note that Geekbench ML, which we ran yesterday, is not optimized to use the Snapdragon X Elite's NPU during its testing. So, in looking at the results we posted yesterday -- where we speculated that the test wasn't optimized -- I guess we should keep that in mind. Still, it's a valid test that runs, even if it doesn't take full advantage of all the processor has to offer.

 So what's on today's agenda? I'll be comparing the results from Cinebench 2024, which ran overnight on our Intel Meteor Lake system and also on our Surface Laptop. I'll be attempting to fix and recompile our battery test, which if it works, will probably take 12+ hours to run. And I'll be tearing our my hair attempting to get AI workloads to work.

 Also, I'll write about how some of the other Copilot+ exclusive features are running, Studio Effects, for example.

_\-- Avram Piltch_

 June 20, 2024 at 1:15 AM

**About those Handbrake numbers**

 So, it looks like the Handbrake numbers we published yesterday were a little off. We use Handbrake 1.8.0, the Arm version for Snapdragon laptops and the x86, 64-bit version for Intel or AMD laptops. We then take a 4K MOV file of Tears of Steel, an open-source movie, and transcode it to 1080p, using Handbrake's default settings (Fast 1080p, 30).

 During yesterday's run, I accidentally used the pre-compressed version of Tears of Steel on Snapdragon so it was turning a 1080p video into a 1080p video instead of a 4K video into a 4K video. This was a bad mistake, but it doesn't help that Windows, by default, hides the file extensions (always change this default right away). I otherwise would have noticed that the source file was an MP4 not the 4K MOV file we work with.

 Anyhow, I reran the test multiple times on The Surface Laptop 15 and we also got numbers from Surface Pro, which also has a Snapdragon Elite X inside. The numbers are now in the 5-minute range, which is versus 8 to 9 minutes on a laptop with an Intel Core Ultra 7 155H CPU inside.

![Snapdragon X Elite vs Intel Ultra 7 155H Handbrake](https://cdn.mos.cms.futurecdn.net/UL7HBa8DvKPtjKNJSqKvDL-320-80.png)

 (Image credit: Future)

 Our lab has also recently tested an LG Gram Pro 16 with a Core Ultra 7 155H and a Lenovo Yoga 7 with an AMD Ryzen 8840HS. As you can see in the chart, the AMD chip was quite a bit faster than Intel's offerings, but still lagged behind Snapdragon by a significant margin.

 June 20, 2024 at 2:57 AM

**Windows Studio Effects are pretty unimpressive**

![Windows studio effects animated mode](https://cdn.mos.cms.futurecdn.net/NuWahchShSGPjRpSqGXnMi-320-80.png)

 (Image credit: Future)

 With Windows' controversial[Recall feature now postponed](https://tools.techidaily.com) , there are only three Copilot+ exclusive features in Windows 11\. These are the Codesigner, the image generator that lives in Windows Paint, Live captions with translation and Windows Studio Effects. We talked about Codesigner and its limited utility in some prior posts.

 I spent some time fooling around with Studio Effects and I'm not impressed. Studio Effects is a set of webcam special effects that use your local processor instead of the cloud. But these special effects are nothing special and, interestingly, a few of them will run on any Windows 11 PC.

 The effects are available to any webcam in any application that accesses your camera. You can get to the settings for Studio Effects either from the Quick Settings menu in the system tray, the Camera section of the overall Settings menu or, if you're using the Windows Camera app, from a menu within the Windows Camera app (but only in Video mode).

 Image 1 of 3

![Studio effects menu](https://vanilla.futurecdn.net/cyclingnews/media/img/missing-image.svg)

 (Image credit: Future)

![Studio effects menu](https://vanilla.futurecdn.net/cyclingnews/media/img/missing-image.svg)

 (Image credit: Future)

![Studio effects menu](https://vanilla.futurecdn.net/cyclingnews/media/img/missing-image.svg)

 (Image credit: Future)

 Studio Effects has five types of settings: Automatic framing, Portrait light, Eye contact, Background effects and Creative filters. Automatic framing , Eye contact and Background effects all appear in the Studio Effects menu on non-Copilot+ PCs as I saw them on our ThinkPad X1 Carbon with Meteor Lake CPU.

![Studio effects menu on X1 Carbon](https://cdn.mos.cms.futurecdn.net/t2ExsUi2yKTHAwgkqWUyq-320-80.png)

 (Image credit: Future)

 However, the Eye Contact mode has two options on Copilot+ PCs: Standard and Teleprompter mode while it has only one on non-Copilot+ PCs. Either way, in my tests, Eye Contact doesn't work. What it's supposed to do is make it look like you are staring at the camera when you are actually looking away.

 Imagine if you were looking at a second monitor or at a teleprompter, but you want your viewers to think you are staring at them directly. Nice idea, but when I looked up on the Surface Pro, it didn't change anything.

![Studio effects eye contact](https://cdn.mos.cms.futurecdn.net/WphSRQeKowyqQ2uDrmbNxL-320-80.png)

 (Image credit: Future)

 Background effects has either Standard or Portrait blur on both Copilot+ and non-Copilot+ laptops and it seems to work pretty well. I prefer Portrait blur because it makes my torso stand out against the blurry background. However, I'm not too excited about background blur as a feature, because it's built into so many chat apps already and there are third-party alternatives such as XSplit VCam that will also do this for you.

 Automatic framing, another feature you can get elsewhere, works pretty well on either Copilot+ or non-Copilot+ PCs. It simply tries to put you in the center of the frame and it mostly accomplishes that.

 Portrait light seemed to have minimal impact on the lighting and colors. In my testing, I couldn't even see a difference with it on or off.

 That leaves us with the three Creative filters, which I'm not sure many people will want to use. There's Illustrated, Water color and Animated and these basically just make you look a little bit like a painting or a cartoon. the changes can be quite subtle and I noticed them most when looking at the skin on my bald head.

 Image 1 of 4

![Animated creative filter](https://vanilla.futurecdn.net/cyclingnews/media/img/missing-image.svg)

 (Image credit: Future)

![Water color creative filter](https://vanilla.futurecdn.net/cyclingnews/media/img/missing-image.svg)

 (Image credit: Future)

![Illustrated creative filter](https://vanilla.futurecdn.net/cyclingnews/media/img/missing-image.svg)

 (Image credit: Future)

![No Creative filters](https://vanilla.futurecdn.net/cyclingnews/media/img/missing-image.svg)

 (Image credit: Future)

 I think the Animated filter made me look most like a rotoscoped character from_A Scanner Darkly._ That's interesting, but not exactly a great selling point for a PC.

 June 20, 2024 at 5:19 AM

**Snapdragon X Elite Aces Cinebench 2024 Test**

![Cinebench 2024 Running on Surface Laptop 15](https://cdn.mos.cms.futurecdn.net/sRsrSrzCJSo7gEX2EgxWrX-320-80.png)

 (Image credit: Future)

 Cinebench is one of the most popular synthetic benchmarks around. It uses your CPU cores (or GPU if you choose) to render an image, block by block. We like to run Cinebench twenty times in a row on laptops to see not only how a system performs, but how its performance changes over time as it heats up and cools down.

 Unfortunately, at the present moment, Snapdragon X Elite chips don't properly broadcast their temperature or power consumption to Windows. Therefore, measurement tools such as HWinfo can't help us log those key metrics while we run Cinebench. We can only look at the scores.

 So we downloaded and ran Cinebench 2024, which is available in both x64 versions for Intel / AMD systems and a Windows on Arm version for Snapdragon laptops. Amazingly, in a 20-cycle run of the multicore CPU test, the Snapdragon X Elite-powered Surface Laptop 15 beat the Core Ultra 7 155H-powered ThinkPad X1 Carbon by 72 percent!

 The ThinkPad averaged a score of 537, with a low score of 466 on run 1 and a high of 585.9 on run 16\. Scores increased dramatically between runs 6 and 9, with the score never dropping below 548 after that. The Surface Laptop had its best score in its second run, hitting 947 and its lowest score on its first run, which was 909\. Most runs were in the 910 to 935 range so Snapdragon-powered laptop was not only faster, but more consistent.

![Cinebench 2024: Snapdragon vs Intel Core Ultra 7](https://cdn.mos.cms.futurecdn.net/oZJV8QsaCk363Uknvvzi4R-320-80.png)

 (Image credit: Future)

 It's important to note that scores on Cinebench 2024 scores are way lower than Cinebench R23\. The older test often returns numbers in the thousands or even in the 15,000 range. However, according to Cinebench 2024's results database, an Apple M1 Ultra CPU scored 1,625 and a Core i7-1289P-powered laptop returned 433\. With that scale in mind, it kind of makes sense that a Core Ultra 7 laptop and a Snapdragon laptop would be between those two other systems.

More about laptops

[Asus ROG Zephyrus Duo 15 GX550 Best Gaming Laptops 2024: Tested, benchmarked and reviewed](https://vanilla.futurecdn.net/cyclingnews/media/img/missing-image.svg) Best Gaming Laptops 2024: Tested, benchmarked and reviewed ](https://tools.techidaily.com) [Real Deals Dell's 16-inch G16 gaming laptop drops to $949](https://vanilla.futurecdn.net/cyclingnews/media/img/missing-image.svg) Dell's 16-inch G16 gaming laptop drops to $949 ](https://www.tomshardware.com/laptops/gaming-laptops/dells-16-inch-g16-gaming-laptop-drops-to-dollar949)

Latest

[XFX Speedster SWFT210 Radeon RX 7800 XT Core Edition  XFX brings back its SWFT 210 cooler for Radeon 7800 XT GPU — XFX Speedster SWFT210 Radeon RX 7800 XT Core Edition rocks dual-fan, minimalist cooler](https://vanilla.futurecdn.net/cyclingnews/media/img/missing-image.svg)  XFX brings back its SWFT 210 cooler for Radeon 7800 XT GPU — XFX Speedster SWFT210 Radeon RX 7800 XT Core Edition rocks dual-fan, minimalist cooler ](https://www.tomshardware.com/pc-components/gpus/xfx-brings-back-its-swft-210-cooler-for-radeon-7800-xt-gpu)

[See more latest ►](https://tools.techidaily.com)

11 Comments [Comment from the forums](https://forums.tomshardware.com/threads/copilot-pc-launch-day-live-blog-testing-the-new-snapdragon-laptops.3847323/)

* Its appears that the gaming performance is not very good right now. Hope it get better with time. There are more reviews incoming as well.  

 <https://www.notebookcheck.com/Asus-Vivobook-S-15-OLED-im-Test-Mit-dem-Snapdragon-X-Elite-in-ein-neues-Notebook-Zeitalter.847338.0.html>  
> _Gaming performance is certainly the biggest weak point at the moment and this is where we had the most problems. Basically, it is not easy for users to find out whether there really is a native version or whether the game is emulated._  
> 
> _We were not able to carry out all of our standard tests because there were some problems. On the one hand, there were image errors at higher details (e.g. Total War Pharaoh) or crashes (e.g. X-Plane, Shadow of the Tomb Raider), but many titles simply did not start at all. These include, for example, F1 23, F1 24, Prince of Persia: The Los Crown or Far Cry 5\. In Cyberpunk 2077, the game also occasionally crashed. We will be testing more titles in the next few days._  
> 
> _The Qualcomm chip supports what is known as automatic super resolution. Basically, the game is upscaled with AI support, so you can select a lower resolution, theoretically without any graphical loss. We will also be testing this in the next few days._  
> 
> _The gaming performance falls behind the other iGPUs and in general it must be said that the Snapdragon laptops are only suitable for gaming to a very limited extent._  

 <https://www.techpowerup.com/img/ZdVP4JWfzeQmN9EI.jpg>  
[Reply](https://forums.tomshardware.com/threads/copilot-pc-launch-day-live-blog-testing-the-new-snapdragon-laptops.3847323/)

* I guess more reviews are gonna come at a later date.  

 1803050279363023302 _View: <https://x.com/zacbowden/status/1803050279363023302>_  

 But here are some of them:  

 uyHs5-XYh6s:32 _View: <https://www.youtube.com/watch?v=uyHs5-XYh6s&t=32s&ab\_channel=MatthewMoniz>_  
 rSx0WZfDbE0:59 _View: <https://www.youtube.com/watch?v=rSx0WZfDbE0&t=59s&ab\_channel=Dave2D>_  
 svZHybT9Jg4 _View: <https://www.youtube.com/watch?v=svZHybT9Jg4&ab\_channel=TechTablets>_  
 _<https://i.imgur.com/foboDSs.png>_  
[Reply](https://forums.tomshardware.com/threads/copilot-pc-launch-day-live-blog-testing-the-new-snapdragon-laptops.3847323/)

* 35below0  
 Shat's with jews and concentration camps in the cocreator article?? Couldn't think of something else controversial that isn't playing with genocide?  
 Like images of a certain Prophet for example? Or you know, that old classic hard core photography of the human form.  

 Actually, i better not give any ideas  

 Actually, actually, now i'm wondering whether it could draw a censored protest in China, since all possible sources of information are supressed? Or back to the prophet again, because how would one know what he looks like?  
 Or something useful, like a pallete swap that is colorblind friendly. Maybe that one would be easy, maybe not.  
[Reply](https://forums.tomshardware.com/threads/copilot-pc-launch-day-live-blog-testing-the-new-snapdragon-laptops.3847323/)

* I guess the battery life seems to be the strongest factor for these Snapdragon X CPU Laptops. But it's frustrating to know that "Cocreator" won't work without an Internet connection.  

> _"So we're in the middle of setting up our Surface Laptop 15-inch with Snapdragon Elite X CPU and it is taking . . . forever."_  

 Any luck or progress yet ?  
[Reply](https://forums.tomshardware.com/threads/copilot-pc-launch-day-live-blog-testing-the-new-snapdragon-laptops.3847323/)

* Notton  
 Where are the naysayers that were out in droves in this thread?  
 <https://www.tomshardware.com/laptops/snapdragon-x-elite-in-the-wild-is-allegedly-slower-than-iphone-12-first-benchmarks-of-samsung-book4-edge-disappoint>  
[Reply](https://forums.tomshardware.com/threads/copilot-pc-launch-day-live-blog-testing-the-new-snapdragon-laptops.3847323/)
* Alvar "Miles" Udell  

> **Painful Reminder: Windows 11 is Full of Ads**  

 Friendly reminder: They're easily disabled.  
[Reply](https://forums.tomshardware.com/threads/copilot-pc-launch-day-live-blog-testing-the-new-snapdragon-laptops.3847323/)

* vijosef  
 This link is broken on the page, and there is no link to here  
 BETa8Cy  
[Reply](https://forums.tomshardware.com/threads/copilot-pc-launch-day-live-blog-testing-the-new-snapdragon-laptops.3847323/)
* KnightShadey  

> Metal Messiah. said:  
> 
> Its appears that the gaming performance is not very good right now. Hope it get better with time. There are more reviews incoming as well.  
> 
> <https://www.notebookcheck.com/Asus-Vivobook-S-15-OLED-im-Test-Mit-dem-Snapdragon-X-Elite-in-ein-neues-Notebook-Zeitalter.847338.0.html>  
> 
> 

 The disappointing thing is that NB didn't test it against more U series laptops. All the intel's are H series, which is fine if your only metric is price not efficient.  
 Price will change over time, but even a i7 150U would've been better than a 155H for comparison for this type of laptop.  

 Looks like they have no 150U nor 120U in their benchmark history, but if you manually compare results to the nearby Ci7 1365U, it looks to be very similar in performance, beating it in tests like Blender 727s vs 545s. Unfortunately many of the other tests are not compatible for comparison.  

 <https://www.notebookcheck.net/Intel-Core-i7-1365U-Processor-Benchmarks-and-Specs.678465.0.html>  
 In comparison to its segment, looks 'OK', not bad, but not as impressive as hyped.  
[Reply](https://forums.tomshardware.com/threads/copilot-pc-launch-day-live-blog-testing-the-new-snapdragon-laptops.3847323/)

* Kondamin  
 What options did you pick when doing the handbreak test?  
[Reply](https://forums.tomshardware.com/threads/copilot-pc-launch-day-live-blog-testing-the-new-snapdragon-laptops.3847323/)
* mikeztm  
 The single core performance is slower than an M2!  
[Reply](https://forums.tomshardware.com/threads/copilot-pc-launch-day-live-blog-testing-the-new-snapdragon-laptops.3847323/)
* [View All 11 Comments](https://forums.tomshardware.com/threads/copilot-pc-launch-day-live-blog-testing-the-new-snapdragon-laptops.3847323/)
 Show more comments

##### Most Popular

[](https://vanilla.futurecdn.net/cyclingnews/media/img/missing-image.svg) ](https://tools.techidaily.com)

[New 3D printer ink makes recyclable electric circuits without heat or light](https://tools.techidaily.com)

[](https://vanilla.futurecdn.net/cyclingnews/media/img/missing-image.svg) ](https://tools.techidaily.com)

[Nextorage launches blisteringly fast SSD for handheld gaming devices — PCIe 4.0 M.2 2230 drive delivers 7,400 MB/s speeds](https://tools.techidaily.com)

[](https://vanilla.futurecdn.net/cyclingnews/media/img/missing-image.svg) ](https://tools.techidaily.com)

[Broken Steam Deck repurposed into an ultra-compact mini-PC — revived device features an extra heatsink for cooler operation](https://tools.techidaily.com)

[](https://vanilla.futurecdn.net/cyclingnews/media/img/missing-image.svg) ](https://tools.techidaily.com)

[Intel Arrow Lake and Panther Lake CPU power profiles allegedly surfaced — leak details Intel Baseline, Performance, and Extreme profiles for next-gen chips](https://tools.techidaily.com)

[](https://vanilla.futurecdn.net/cyclingnews/media/img/missing-image.svg) ](https://tools.techidaily.com)

[AMD's 'Sinkclose' vulnerability affects hundreds of millions of processors, enables data theft — AMD begins patching issue in critical chip lines, more to follow](https://tools.techidaily.com)

[](https://vanilla.futurecdn.net/cyclingnews/media/img/missing-image.svg) ](https://tools.techidaily.com)

[God of War: Ragnarok's PC port requires an incredible 190GB for installation — PSN account is also a requirement](https://tools.techidaily.com)

[](https://vanilla.futurecdn.net/cyclingnews/media/img/missing-image.svg) ](https://tools.techidaily.com)

[Linux boot time reduced by 0.035 seconds thanks to a one-line kernel patch — aligning the slab in the ACPI code makes Linux boot faster](https://tools.techidaily.com)

[](https://vanilla.futurecdn.net/cyclingnews/media/img/missing-image.svg) ](https://tools.techidaily.com)

[Intel issues statement on microcode update that addresses CPU instability and crashing errors — claims patch has negligible performance impacts, future processors not impacted](https://tools.techidaily.com)

[](https://vanilla.futurecdn.net/cyclingnews/media/img/missing-image.svg) ](https://tools.techidaily.com)

[Raspberry Pi Compute Module 4 powers custom Sony PlayStation One](https://tools.techidaily.com)

[](https://vanilla.futurecdn.net/cyclingnews/media/img/missing-image.svg) ](https://tools.techidaily.com)

[Intel's Arrow Lake-H could feature three types of CPU cores according to Linux patch — hybrid designs could get more complex](https://tools.techidaily.com)

[](https://vanilla.futurecdn.net/cyclingnews/media/img/missing-image.svg) ](https://tools.techidaily.com)

[Kioxia showcases SSDs that communicate at the speed of light — optical connection enables storage as far as 40 meters or more from CPU](https://tools.techidaily.com)

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
<li><a href="https://screen-sharing-recording.techidaily.com/new-2024-approved-10-best-video-tools-perfect-your-webcam-vids/"><u>[New] 2024 Approved  10 Best Video Tools  Perfect Your Webcam Vids</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/024-approved-priority-picks-high-rated-graphics-cards-for-seamless-playback/"><u>[New] 2024 Approved  Priority Picks  High-Rated Graphics Cards for Seamless Playback</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-the-connected-world-sharing-twitter-media-in-whatsapp-chat/"><u>[New] 2024 Approved  The Connected World  Sharing Twitter Media in WhatsApp Chat</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-quick-strategies-logging-lectures-in-ppt/"><u>[New] In 2024, Quick Strategies  Logging Lectures in PPT</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-mastering-youtube-captions-3-effective-methods-to-download-srt-files/"><u>[New] Mastering YouTube Captions  3 Effective Methods to Download SRT Files</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-exploring-basic-hdr-a-thorough-review-guide/"><u>2024 Approved  Exploring Basic HDR  A Thorough Review Guide</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-laugh-labyrits-undead-sarcasm-spawners/"><u>2024 Approved  Laugh Labyrits  Undead Sarcasm Spawners</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/a-game-changer-in-connectivity-unveiling-the-might-of-asus-rt-be96u-7ghz-wifi-router/"><u>A Game Changer in Connectivity - Unveiling the Might of Asus RT-BE96U 7GHz WiFi Router</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/approach-recall-the-initial-stage-of-planning-for-land-division/"><u>Approach: Recall the Initial Stage of Planning for Land Division</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/approval-from-government-agencies-or-planning-commissions-is-typically-required-before-proceeding/"><u>Approval From Government Agencies or Planning Commissions Is Typically Required Before Proceeding.</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/benchmarking-the-kingston-fury-beast-a-deep-dive-into-ddr5-6000-cl40-performance-with-2x32gb-memory-modules/"><u>Benchmarking the Kingston Fury Beast - A Deep Dive Into DDR5-6000 (CL40) Performance with 2X32GB Memory Modules</u></a></li>
<li><a href="https://extra-tips.techidaily.com/capturing-audio-masterpieces-using-audacity/"><u>Capturing Audio Masterpieces Using Audacity</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/discover-the-best-in-computing-navigating-hardware-with-toms-guidance/"><u>Discover the Best in Computing: Navigating Hardware with Tom's Guidance</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/1723341712256-discover-the-unique-world-of-flsun-s1-fast-and-fun-solar-gadget/"><u>Discover the Unique World of FLSun S1 - Fast and Fun Solar Gadget!</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/discovering-top-tier-electronics-with-toms-hardware/"><u>Discovering Top-Tier Electronics with Tom's Hardware</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/exploring-sovol-sv0s-performance-a-modern-tribute-to-voron/"><u>Exploring Sovol SV0ˈs Performance: A Modern Tribute to Voron</u></a></li>
<li><a href="https://tech-haven.techidaily.com/exploring-the-capabilities-of-chatgpt-copilot-an-overview/"><u>Exploring the Capabilities of ChatGPT Copilot: An Overview</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/how-can-i-get-more-stardust-in-pokemon-go-on-realme-narzo-60-pro-5g-drfone-by-drfone-virtual-android/"><u>How can I get more stardust in pokemon go On Realme Narzo 60 Pro 5G? | Dr.fone</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/in-2024-fcp-in-the-spotlight-10-acclaimed-movies/"><u>In 2024, FCP in the Spotlight 10 Acclaimed Movies</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-location-on-tiktok-to-see-more-content-on-your-motorola-edge-40-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Location on TikTok to See More Content On your Motorola Edge 40 | Dr.fone</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/in-depth-analysis-of-the-flsun-s1-high-velocity-and-distinctive-delta-shape/"><u>In-Depth Analysis of the FLSun S1 - High Velocity and Distinctive Delta Shape</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/in-depth-analysis-of-the-valkyrie-vind-sl125-stunning-anime-design-but-disappointing-functionality/"><u>In-Depth Analysis of the Valkyrie Vind SL125: Stunning Anime Design but Disappointing Functionality</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/in-depth-electronics-analysis-by-tom-your-guide-to-top-tech-picks/"><u>In-Depth Electronics Analysis by Tom – Your Guide to Top Tech Picks</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/in-depth-performance-breakdown-of-the-nzxt-c1email-protected-platinum-supply/"><u>In-Depth Performance Breakdown of the NZXT C1([email Protected]) Platinum Supply</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/mastering-equipment-with-toms-hardware-guide/"><u>Mastering Equipment with Tom's Hardware Guide</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/mastering-gadgets-with-tom-a-hardware-journey/"><u>Mastering Gadgets with Tom - A Hardware Journey</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/mastering-gadgets-with-toms-hardware-experts/"><u>Mastering Gadgets with Tom's Hardware Experts</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/mastering-gadgets-with-toms-hardware-hub/"><u>Mastering Gadgets with Tom's Hardware Hub</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/navigating-through-raspberry-pis-enhanced-speed-and-capacity-insights-from-our-in-depth-analysis-of-the-m2-hatplus/"><u>Navigating Through Raspberry Pi's Enhanced Speed and Capacity: Insights From Our In-Depth Analysis of the M.2 HAT+</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/1723341686952-public-hearings-may-provide-community-members-with-a-platform-to-influence-the-land-division-process/"><u>Public Hearings May Provide Community Members with a Platform to Influence the Land Division Process</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/review-of-the-western-digital-my-passport-6tb-portable-ssd-compact-yet-capacious/"><u>Review of the Western Digital My Passport 6TB Portable SSD - Compact Yet Capacious</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/review-the-keychron-k2-he-special-edition-a-blend-of-vintage-style-and-contemporary-functionality/"><u>Review: The Keychron K2 HE Special Edition - A Blend of Vintage Style and Contemporary Functionality</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/shrinking-or-enlarging-images-on-your-iphone-effortlessly/"><u>Shrinking or Enlarging Images on Your iPhone Effortlessly</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/1723341683638-teamgroups-eco-ddr5-revolution-the-vulcan-memory-kit-ddr5-6000-c30-2x16gb-reviewed/"><u>TeamGroup's Eco-DDR5 Revolution: The Vulcan Memory Kit - DDR5-6000 C30, 2X16GB Reviewed!</u></a></li>
<li><a href="https://games-able.techidaily.com/the-art-of-crafting-engaging-successful-games-learn-from-helldivers-2/"><u>The Art of Crafting Engaging, Successful Games: Learn From Helldivers 2</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/the-game-changer-amd-ryzen-5-9600x-and-ryzen-7-9700xs-superior-gaming-capabilities-in-zen-5-era/"><u>The Game Changer: AMD Ryzen 5 9600X & Ryzen 7 9700X's Superior Gaming Capabilities in Zen 5 Era</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/the-kingston-fury-beast-ddr5-memory-kit-reviewed-exploring-its-capabilities-in-a-2x32gb-setup-at-5000mhz-and-cl4ncas-latency/"><u>The Kingston Fury Beast DDR5 Memory Kit Reviewed: Exploring Its Capabilities in a 2X32GB Setup at 5,000MHz and CL4n/CAS Latency</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/the-tom-showdown-innovative-hardware-evaluations-and-tips/"><u>The Tom Showdown: Innovative Hardware Evaluations and Tips</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/the-ultimate-4k-odyssey-unveiling-the-power-of-gigabytes-aorus-fo32u2p-monitor-a-fusion-of-elegance-and-buttery-smooth-240-hz-gaming/"><u>The Ultimate 4K Odyssey: Unveiling the Power of Gigabyte's Aorus FO32U2P Monitor, a Fusion of Elegance & Buttery-Smooth 240 Hz Gaming</u></a></li>
<li><a href="https://android-unlock.techidaily.com/the-ultimate-guide-how-to-bypass-swipe-screen-to-unlock-on-asus-rog-phone-8-device-by-drfone-android/"><u>The Ultimate Guide How to Bypass Swipe Screen to Unlock on Asus ROG Phone 8 Device</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/the-ultimate-resource-for-pc-gear-tips-from-tom/"><u>The Ultimate Resource for PC Gear - Tips From Tom</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/the-ultimate-review-of-hp-omnibook-x-extending-workdays-with-its-powerful-16-hour-battery-life-and-innovative-xpower-tech/"><u>The Ultimate Review of HP OmniBook X: Extending Workdays with Its Powerful 16-Hour Battery Life and Innovative XPower Tech</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/toms-gadget-guide-unlocking-the-potential-of-your-electronics/"><u>Tom's Gadget Guide: Unlocking the Potential of Your Electronics</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/toms-tech-reviews-comprehensive-analysis-of-the-latest-gear/"><u>Tom's Tech Reviews: Comprehensive Analysis of the Latest Gear</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/uncovering-tech-secrets-with-toms-equipment-insights/"><u>Uncovering Tech Secrets with Tom's Equipment Insights</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/unlocking-the-potential-asus-rog-swift-oled-pg32ucdp-reviewed-for-unmatched-gaming-clarity/"><u>Unlocking the Potential: Asus ROG Swift OLED PG32UCDP Reviewed for Unmatched Gaming Clarity</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/unveiling-cutting-edge-technology-through-toms-hardware-experts/"><u>Unveiling Cutting-Edge Technology Through Tom's Hardware Experts</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/unveiling-tech-secrets-an-inside-look-by-toms-hardware-experts/"><u>Unveiling Tech Secrets: An Inside Look by Tom's Hardware Experts</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/unveiling-the-best-electronics-with-toms-hardware-guidance/"><u>Unveiling the Best Electronics with Tom's Hardware Guidance</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/unveiling-the-pixio-px277s-brilliance-a-comprehensive-review-for-gamers-seeking-excellence/"><u>Unveiling the Pixio PX277's Brilliance: A Comprehensive Review for Gamers Seeking Excellence</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/unveiling-the-power-of-the-logitech-g-pro-x-2-lightspeed-the-ultimate-review-for-gamers-perfection/"><u>Unveiling the Power of the Logitech G Pro X 2 Lightspeed: The Ultimate Review for Gamers' Perfection</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35408920&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/FR-200-1.png" border="0">Glarysoft File Recovery Pro - Helps to recover your lost file/data, even permanently deleted data. </a>
<!-- affiliate ads end -->