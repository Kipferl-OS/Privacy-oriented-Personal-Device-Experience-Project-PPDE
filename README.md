Privacy-oriented Personal Device Experience Project (PPDEP)

**An extensive guide for running an alternative smartphone operating system as a daily driver, stripped out of vendors' analytics, telemetry or most of the personal data that is typically sent via the current most popular phone brands.**

**Transforming an outdated Android device (Google Pixel 3A) into a fully-functional, long-lasting and reliable alternative for general consumer usage, with the thought in mind of obtaining an experience as close as to the presently available vendor ecosystems.**


## Guide structure & forewords
There are more aspects to be discussed before directly jumping into the technical installation steps part. Because I wanted to create this guide as accessible and foolproof as possible for most smartphone users (as it was intended for), some pieces of information should be best followed before attempting to follow this project.

I have thus decided to split this guide into **three major parts**, each one with its separate points, being the following:

**1. Introductory factors - a better understanding of the current trends related to smartphone usage & applications' behaviour.
2. Installation procedure - porting Ubuntu Touch into Google Pixel 3a (installation steps).
3. Application alternatives resources overview; recommendations for a privacy-oriented ecosystem.**

Before further reading, if you are only interested in the **technical installation steps**, then I suggest you directly jump to the second part.

Without taking advantage of any potential dramatic discourse, it has become more evident that privacy, particularly when referring to the online world, has significantly lost its consistency throughout the internet's overall development. Most of the services that we consume, beginning from the products themselves and then straight to the very/exclusively digital parts of those do not guarantee that the privacy of a consumer is respected and that no relevant user data is sent for further analytics. Although there have been incremental changes and measures taken for protecting the user and his/her personal information, the recent historical events in the digital world have shown us that it might not be the best choice to leave this task up to the companies or businesses whose services we are operating. 

I will not be digging too much into the issue itself. That is because, when talking about the concept of *owning and using a phone* nowadays, it has far left the mere meaning of using a not-so-sophisticated piece of electronics that was originally intended for pure communications. Undoubtedly, these have attained the badge of *smart*, but despite their exceptional practicality for running specific tasks or activities, we have also come to the point in which these are now part of our daily life, starting from reading any information and up to making financial transactions, each one of them having a more or less impact, with different consequences. 

We have also had such a rapid shift in terms of technological development that nobody has been fully capable of keeping up with the constant changes that we are being exposed to. Intercepting a phone conversation in the past was something that you would rarely see or hear about, mainly in movies, but we have now reached a point in which various people can easily be tracked of more than casual conversations, whose exposure can lead to far more dangerous risks, and I believe that there are enough examples to follow this point. As this guide is oriented towards something different, I will be summarizing these under a less extensive concept, the **motivation behind shifting to an open-source, privacy-oriented alternative**, which I will be showing in the first chapter, along with some official documentation that can justify it so.

Throughout this guide, I will be taking a both statistical and technical approach, by explaining the current risks that there are to be considered when operating on a generic commercially available smartphone, as well as widespread applications that are used for socialization needs, user and password managers, entertainment, apps involving tracking different information etc.

After that, I will be covering a brief comparison between what's currently available on the market, in terms of both user apps and general devices from particular vendors, by stating the positive and negative aspects of operating both elements in the current state. This will be aided by making a further comparison of how both device operating systems and apps should function & be operated so that there would be fewer or close to 0 risks in terms of personal data processing, analytics etc.

This guide will also contain currently available resources that can be used and chosen to create a better environment in terms of privacy concerns, but also dig more into exploring these options so that, at last, we can reach the expected results, by taking into consideration minimal effects on the overall user experience. As this matters the most, **a deprecated, inefficient, sluggish user experience will prove to influence the results and be discouraging for general consumers to approach the given alternatives**.

For the technical aspect, **the installation procedures will also be taken into consideration as these should not be too extensive, costly and complicated, which would also be a discouraging factor for the typical user**.

Ultimately, I will be proceeding with an overview of the whole process, providing an extensive list of essential applications that were sought as alternatives for the most widely used ones in the current market, their functionality and how the alternative operating system(s) can be easily paired with other open-source available alternative operating systems for desktop computers, which would also allow for an "ecosystem" type of experience, similar to the most popular ones that are available on the market.

With all that information in mind, I happily invite you to start checking out the first part, where we can understand the drive or need behind this project much better. Good luck!

***To make the whole research even more worthy of its direction, I will be only relying on free, open-source available tools, so that the reason behind its creation can be strengthened even further :). I will be adding the list of all used tools at the end of the guide.**


##  Introductory factors - understanding current trends related to smartphone usage & applications' behaviour.

***Because of how extensive the following touched points might become in the given discussions, I have decided to take a different direction, which is presenting a summary of the essential ideas I was interested in sharing with you, while the more in-depth source of each addressed issue will be added here so that you can read and discover more on your own, especially if you are seeking to understand more pieces of information of this subject. I initially thought of "PPDEP" to be a more straightforward project, but while I might be able to go shorter on the technical part of it (as I believe it is not too complex for the average user), the main issue from which I have taken the motivation to write this requires far more data to work with & aspects to be discussed. Consequently, feel free to explore on your own if you want to know even more about the current imbalances that are found in the daily usage of the current smartphones' experience, operating systems, widely used apps etc.**

**A business behaviour impacting general consumers' approach to the situation**

The **first motivation point** starts from the current way or direction smartphone companies have started (and they have been doing it for quite a while) to impact general users through the decisions made in terms of their business approach, which, of course, contains lots of aspects to be addressed, but I will be limiting that on few examples, such as the tendency of creating inflexible or restricting-type-of behaviour ecosystems, which normally could only work at their best potential if the usage of that particular business' products are all used together and the activity is being synchronized through those. To be more specific, company X or Y would try to ensure their customers that they can benefit from unlimited cloud storage through the acquisition of their smartphone brand because only that model would go hand-in-hand with that feature. Or, they would advertise an incredibly efficient file-sharing feature between smartphones and other desktops/IoT etc. types of devices, given that you have also purchased the assets designed specifically by them. 

Another example would be the usage of proprietary apps that are provided by a smartphone vendor. However, even if these apps are running on a universal (even open-source!) type of operating system, such as **Android OS**, the functionality of these apps not only is, in fact, closed-source but they are also restricted to be found or even function on that given vendor's provided custom devices. If let's say, you are used to and work very well with the messaging app provided by Samsung, which is only found on their proprietary Samsung devices, don't expect to be able to port the same application on another custom-sold Android-based OS. The technicalities depend on the same foundation, however, companies have learnt to set imaginary boundaries when working in this field, so that they are sure to strengthen their product brand image or signature, which would also, whether intentional or not, limit users from switching on other alternatives, in the case they have already just accustomed the usage of a certain company ecosystem in their daily lives. Some people manage to adapt and work in multiple environments, but this should certainly not be considered applicable as a habit for most consumers. It would only bring further exhaustion, which, at the same time, can be regarded through another approach, via the following argument.

**Internet general safety approach to the situation**

According to **"Reengineering the user: privacy concerns about personal data on smartphones" (Matina Tsavli, Pavlos S. Efraimidis, Vasilios Katos, Lilian Mitrou) research paper**, you will find in its abstract a particularly fascinating and quite relevant idea that was one of their study conclusions: 

*The results of this work indicate that, even though providing access to the personal data of smartphone users is by definition neither problematic nor unlawful, today’s smartphone operating systems do not provide an adequate level of protection for the user’s personal data.*

**You can find the paper available for further reading here: [Reengineering the user: Privacy concerns about personal  
data on smartphones](http://eprints.bournemouth.ac.uk/24543/7/Reengineering%20the%20user.pdf)**

There is even more consistent information that the research paper contains, specifically in *chapter 2 (Data taxonomy on smartphone devices)* and *chapter 3 (Data protection requirements)* which further state the similarities between typical desktop device functionalities and the one we currently find in nowadays' smartphones, and, while there's so far nothing maleficent going on with the backed structure, we can still be sure that there is **no official guarantee and prerequisites taken from most vendors, although promoted as such in some cases, that the personal data of each and every user is in safe hands**. Moreover, the multitude of daily used applications which are typically found in the most popular software catalogues or so-called "stores" are not even provided by these vendors, but they are originating from various third parties. Although there are specific mechanisms that strive with ensuring that the user does not end up being compromised by particular apps, it is impossible to provide 100% coverage and avoid zero slips from offering such a desired level of security. As mere examples, there have been plenty of cases where infected applications have been detected too late by the official vendors, and even after removing those from public access, the damage was still inflicted on the users that have already downloaded them. Strolling around a few articles related to that, there were even some **recent cases** that I found at the time of writing this guide: 

**[Recent case of malware detected on specific apps available via Apple's Appstore](https://lifehacker.com/great-now-the-apple-app-store-has-malware-too-1849386738)**

**[Recent case of dozens of malicious apps that were found available via Google's Play Store](https://www.bitdefender.com/blog/labs/real-time-behavior-based-detection-on-android-reveal-dozens-of-malicious-apps-on-google-play-store/)**

When already dealing with such circumstances, it is undoubtedly true that **we're at the moment dealing with both the more-or-less flawed design of the currently available official vendor-provided operating systems, as well as a not-so-friendly and safe environment of smartphone applications** that are free of malware or other unwanted "gifts" which would not only pose a risk to the general user but also disrupt their activity. We're mostly talking about two major widely used smartphone environments, provided by either Apple's iOS (or iPad OS for tablet devices) and Android OS (that comes in different flavours) from the other vendors (Google, Huawei, Xiaomi, Oppo, Vivo, Samsung etc.), thus it is imperative to express that such issues are guaranteed to be found in both, even if the percentages can differ.


## Introductory factors (II): Overview of the currently available alternative resources

Now that we've got a little bit of a grip on knowing what problems we are or will be dealing with, I think most of you will be prone to ask yourself: Okay, what are we supposed to do now? Who do we trust? How to avoid all these risks?

Fortunately, we do not need to find ourselves completely stuck in what the consumerist culture is providing us at the moment, as smartphone software (and even hardware) technology is not limited only to most vendors' control. Here's where the concept of open-source comes in aid, and this guide will exactly, if not even exclusively be relying upon this concept.

As we can not fully grant our trust to what the market has to give users, some alternatives can be taken into consideration, and that can be fully implemented to our own devices (depending on the ones we're using), at a software level. In this case, we will be replacing our current smartphone operating system provided by the device's vendor with a free, open-source alternative that does not depend on a chaotic third-party APP environment which has already been proven not to be safe enough for most users. 

Just before diving more into this, **please note that this guide will not, sadly, apply to Apple devices. There's too much of a long story to explain why, but the simple answer would be that apple devices predominantly run on closed-source software, which...eh, does not benefit from such a broad individual development separate from Apple itself. However, we will be tackling Android OS, which is even advertised as open-source, and yes, they are honest about that. It even is stated on their official "technical" name, being **[AOSP (Android Open Source Project)](https://en.wikipedia.org/wiki/Android_(operating_system))**.

To clarify the latter, we're talking about a foundation of a Linux kernel-based distribution that was specifically designed by smartphones or other portable devices (but not limited to that), Android OS. The core components are universally available to all applicable devices, however, visually speaking, they would look different to an inexperienced user, as the current market provides a vendor-customized user interface and software suites, which are simply said, customized versions of the proprietary operating system. Most of the 'kitschy' (my personal opinion, sorry) interfaces that you're seeing on most popular smartphone brands available on the market, are nothing more than Android systems at the core, but with tons of "make-up" put over. Even Google which owns the project comes with preinstalled Google-specific applications, however, even without those, the actual Android interface ((known as "stock") is far simpler, cleaner and less noisy than the other ones. Here's a quick visual comparison article: **[example](https://techwiser.com/stock-android-vs-miui/)**.

We're now aware of the AOSP not being owned in that manner by one or more specific vendors, so be assured that there are custom alternatives that the community of developers has taken its time to release for particular smartphone models (known as custom ROMs). Some are more official than others, meaning that they are being provided more or less support in terms of updates for that particular device(s). We will be going over that a little bit later, but currently, we should focus on the following question: 

**What operating systems that are privacy-oriented and that can provide a greater level of safety on the internet are there available for the common users?**

Luckily, I went ahead of you with that and compiled a quick list of the alternatives that are, at least in my opinion, worthy of checking out. All the descriptions have been taken from its according main website.

**[Lineage OS](https://lineageos.org/)**: as stated on the website, is a free and open-source operating system for various devices, based on the Android mobile platform.

**[/e/OS](https://e.foundation/about-e/)**: /e/OS consists of a fully deGoogled mobile operating system (OS) and carefully selected applications, together forming a privacy-enabled internal environment for mobile phones.

**[Calyx OS](https://calyxos.org/)**: Android mobile operating system that puts privacy and security into the hands of everyday users. Plus, proactive security recommendations and automatic updates take the guesswork out of keeping your data personal.

**[Divest OS](https://divestos.org/index.php)**: vastly diverged unofficial soft fork of Lineage OS, made to be even more privacy-enforced.

**[Graphene OS](https://grapheneos.org)**: privacy and security-focused mobile OS with Android app compatibility developed as a non-profit [open source](https://grapheneos.org/source) project. It's focused on the research and development of privacy and security technology including substantial improvements to sandboxing, exploit mitigations and the permission model. It was founded in 2014 and was [formerly known as CopperheadOS](https://grapheneos.org/history/copperheados).

**[Ubuntu Toutch](https://ubuntu-touch.io/)**: privacy and freedom-focused mobile software - a viable alternative to Android and iOS. Free and open-source GNU/Linux-based mobile operating system

**[SailfishOS](https://sailfishos.org/)**: secure mobile operating system optimized to run on smartphones and tablets, and also easily adaptable to all kinds of embedded devices and use cases.

**[postmarketOS](https://postmarketos.org/)**: Linux distribution for phones and other portable devices.

As can be seen, there are already plenty of official options I strongly suggest you check them out, as they both truthfully state what they're offering and they are quite accessible for most beginner users so that the installation & overall user experience becomes as straightforward and encouraging as possible.

One crucial observation that I would like to also state is that there's also the concept of "custom ROM" that is available on Android-based devices, essentially referring to an individual, usually a non-profit modified version of the original AOSP system, which is made by community users and can provide a sweet experience, depending on the user's particular needs. Although still open-source, these are not privacy-focused, but their "degooglefied" versions provide a similar experience (yet, it requires more settings to be tackled by the user itself to reach the desired experience), and are keener on offering almost full flexibility in terms of all tweaking options available for the device that is designated for. And speaking of devices, please note that the options that I have mentioned above are not to be treated as a universal alternative to ALL existing smartphones that are out there. There's currently a limited list of devices that have obtained support for developing compatible software that can be further installed on those, therefore make sure to check which device is covered by which alternative OS and ensure to follow the installation steps accordingly, because...*sigh*...despite all of them being based on Android, almost every device has a different way of preparing the prerequisites before jumping to the installation itself. A comparison between the original vendor-based Android OS and the given alternatives would have also been worth making out, however, as each alternative comes with its bundle of advantages and disadvantages, hence I will be focusing on this particular aspect through the final choice that was taken for this guide.

Having that in mind, let us take a look at what alternative OS we will be exploring and analyse together the reasoning behind that, as well as a brief installation process showcase.

## Introductory factors (III): Owning an old-fashioned Google device via the support of the UBports community

I will be going through the following imaginary scenario. Let's assume that I had an old device lying around my drawer and I wanted to revive it for the current times but as an ordinary consumer, I am pretty fond to think that phones do not last at their full potential (even lower than that if we want to refer to budget devices, depending on the options available) and that I feel reluctant to proceed to do anything else, as most of its updates have already been deprecated and the device is not currently supported by its main vendor. It gets stuck at an older Android version, everything feels sluggish and it could only tempt me to either get back to my actual device if I have one or go ahead and buy the latest jewel available from the same vendor. Wouldn't that make sense for anyone to do? Well, not necessarily.

You see, while not every single device available on the market can benefit from this, there are a few devices out there that have been pumped with lots of support from communities over the world. In this case, we will be checking out an already out-of-production Google Pixel 3A device, which was not the cheapest alternative at its times but wasn't a flagship either. It was more in-between the range of devices' overall performance. At the moment of writing this guide, this phone still miraculously supports a more recent Android version (12), but it's not the latest one and will not be able to receive it through Google's official development channel. However, as there was a lot of accessibility in terms of its software development, many of the alternatives that I have stated in the previous chapter do offer full compatibility and support to this phone as well. One of them, which I will be covering for the most part left of this guide, is UBPorts or known as Ubuntu Touch, which is a mobile device adaption of the popular Linux distribution known as Ubuntu, that was made with the scope of offering a similar swift, secure, and user-friendly experience available for current smartphones as well. The reason I have chosen Google Pixel 3A as the perfect device for showcasing the porting process of Ubuntu Touch is, well, the phone is available on the list of supported devices(there are many others available as well), but it's also one of the devices that have achieved 100% compatibility with the alternative OS, meaning that all the phone-related functions are working flawlessly and that there are no casual bugs to be reported or worked on. You can find all the required information about this [here](https://devices.ubuntu-touch.io/device/sargo/).

There's even been some news on the internet about it: **[Google Pixel 3A achieves 100% Ubuntu Touch support score](https://tuxphones.com/google-pixel-3a-full-stable-ubports-linux-ubuntu-touch-feature-support/)**.

[insert screenshot from the website here.jpeg]

Moreover, as we'll be checking every step together, compared to a "traditional" way of installing custom ROMs, the approach taken via UBPorts is much more simplified, fail-proof (so that you do not end up breaking your device), and prompt. Trust me, over all the phones that I have been tweaking via the custom ROM development, getting Ubuntu Touch up and running on my pixel phone proved to be less stressful and problematic.

Of course, there's also the idea of having a more unified type of ecosystem experience, just like the ones we typically see being marketed from the popular vendors, and in case you haven't guessed yet, having an Ubuntu (or honestly any other Linux distribution at hand that you would be more comfortable with it, but for now we'll stick with this one as it's a better choice for beginners), should prove to be a both powerful & incredibly affordable solution at disposal. After all, the software layer beneath either the smartphone or the desktop computer/laptop is completely free of charge.

If that hopefully sparked any further curiosity on your end, let us together have a look at how the installation procedure of UBPorts to a Google Pixel 3A device should go for you and many others (successfully) too.


## Installation procedure I: Device case subject: Google Pixel 3A - installation of UBPorts. Installation steps overview

Assuming that you own the same device or you want to get a brief idea of how this works, let's recap everything that we will need to make it through the very happy end:

Prerequisites:
* Working android device that is compatible and available on the supported devices list that can be found on the UBPorts website.

* Any operating system (whether Mac OS, Windows, Linux-based distribution etc.) that allows you to deploy terminal/command prompt/PowerShell commands without other accessibility errors and so on.

* Installed *ADB and fastboot tools & their according drivers, which will essentially allow us to connect our phone via USB cable and deploy the required commands, whether manual or/and through an automatic process. As stated via **[linuxpip.org](https://linuxpip.org) - "ADB is a powerful command-line tool that provides access to a Unix shell, letting you communicate with your Android device from a client machine. Using ADB, you can install apps, copy files, run shell commands, and debug apps, among other things right from your computer without touching the actual device. Fastboot is the name of three different things: a protocol, a bootloader mode and a program that runs on the computer, all of which let you communicate with your Android device. Usually, fastboot is used to re-flash the system partitions inside the Android device."** Each OS has a slightly different way of getting these tools up and running, but I can assure you that the installation steps are pretty straightforward and their overall functionality will be the same, despite running on different environments.

* A simple & working USB cable that allows for proper connections between your main desktop/laptop and the phone itself.

* Backing up personal files & other related data, if necessary and you're doing that on your main daily driver. The steps will involve deleting everything, so if you have anything to save, either via offline storage or cloud, make sure to do it before.

### Getting ADB & fastboot tools ready on Ubuntu (or other Debian-based distributions):
Sadly, I won't be covering this part for other systems (mainly because Windows has installers available and MacOS comes preloaded with ADB compatibility), so if you took the hint of the direction I am leaning towards to, allow me to show a summary of how to get these tools up and running on Linux (Ubuntu):

First, let us make sure everything is properly updated & upgraded on our system. Run the following:

 `sudo apt get update`
`sudo apt upgrade` 

[insert 1.png + 2.png here]

If everything got upgraded successfully (make sure to write 'y' as in 'yes' when running the latter command), we continue with the installation of the tools themselves:

`sudo apt install android-tools-adb android-tools-fastboot -y`

[insert 3.png here]

We can see if everything got installed successfully by checking out the installed version. If the terminal shows it accordingly & is being recognized by the system, we're good to go! You can do that by writing `adb version` via the terminal:

[insert 4.png here]

The adb server which allows the connectivity between your device and desktop computer/laptop typically is available automatically, but in case it might not start by itself, you can always start first by running this command: `sudo adb start-server`. At last, whenever required, we can kill the connection through `sudo adb kill-server`.

Whenever you'll be connecting your phone in ADB mode (which is done via enabling the developer mode on your android device & allowing ADB-type connections), you can check the status of whether your phone is properly connected to the computer via `adb devices`. If that one works as well, congratulations, you got everything else set up :)!

### Summary on how this "surgery" is going to go for Google Pixel 3A
Just to better understand what we'll be doing, I have tried summarizing the steps down below so we can have a better overview before actually taking the steps themselves. Note that all this information is available on the sites that we will be relying on, mainly UBPorts and the developing repository for this device, which also has the codename [*sargo*](https://developers.google.com/android/images#sargo), and then I will be showing in detail each step taken for getting Ubuntu Touch properly ported on our device.

1. **Preparatory step: we need to first revert to factory image **PQ3B.190801.002** before continuing to the actual steps. This means that we will be unlocking the bootloader and flash the stock factory image via Google's official method before actually proceeding to the rest of the steps that are solely made for installing Ubuntu Touch. In other words, do NOT do that with the current version of Android that you have on your current google pixel device.

2. We will be using UBports Installer on our computer which will do most of the stuff automatically, without too many complications. Make sure to select the package that is made exactly for our device codename.

3. Plug in our device while following the given instructions. After that, the installer will once again do most of the job.

4. Enjoy!

Let us take it in-depth, one by one:

### 1. Preparatory step.
Head over [this link](https://developers.google.com/android/images#sargo) and search for the factory image code titled **PQ3B.190801.002**. This was one of the initial versions Google Pixel 3A devices came from the factory when the phone was released, and the reason we're getting it is that Ubuntu Touch development was based on that practical software version, therefore we need to have it running on our phone as a foundation to the ported alternative OS. 

[insert 1.jpg from 2nd folder here]

If you look closely, be aware that the same factory version is available for its bigger brother, 3A XL, and we do NOT want that one. They're different, just like the rest of humans are...hah...Anyway, like in the screenshot above, there's a hyperlink next to the factory version which reads as *Flash*. Click on that one.

Now, before we jump more into it, sadly, I don't like saying this, but please **make sure that you are running a Chromium-based version of your internet browser**. If you dislike Chrome(like I do), go ahead and look for Chromium or Brave Browser. These options are based on Chrome's main source code but are not as intrusive as the original Google's developed browser is. As the flashing automatic process is still provided by Google, we have no choice but to stick with either any Chromium-based browser, until we get the factory version on our phones. Meanwhile, take a look at the screenshot below, this is what's currently running on my Google Pixel 3A before flashing so that you'll be able to see the difference at the end when getting the factory one on the phone itself.

[insert iPhone picture 1.jpg here]

It says that I'm running the latest Google officially provided software version, Android 12, with the latest security patch.
Also, now that you're on the settings menu too, head over to the Build Number (at the end of the menu) and tap on it a couple of times, until you see: *You are now a developer*.

After that, head over back to the system, and you should see the Developer options as a new menu feature to press on. Do that. Look for *OEM Unlocking*, enable it, as well as *USB debugging* and *Disable authorization timeout*. Enable all these and reboot your phone.

Now go grab that juicy (I should reconsider my vocabulary) USB cable and connect it to your computer. You will be getting 1-2 prompts about authorizing ADB connectivity with your computer on your phone, make sure to allow that, and you will be good to go. To make sure you're connected with your device, head over to your computer's terminal (whichever one you have) and type `adb devices`. If it's all done correctly, your pixel phone should be recognized, just like here: 

[insert 3.jpg from 2nd folder here]

In case you didn't notice, my first command sent back the fact that the device is *UNAUTHORIZED*, mainly because I got the prompt of allowing USB debugging connections on my phone, right after I wrote the command. After allowing it, the connection was successfully made.

At this point, we're going to run two simple commands which will allow us to directly unlock the bootloader for pixel 3A. It's the most "manual" part of this process. So head over to the terminal and type the following:

 `adb reboot bootloader`

Your phone is going to shut down by itself and turn on back with a sketchy "hackerish" type of menu, where there are two keywords to look for. First, it should say in red *Fastboot mode*, second, the *Device state* should be marked in green as *locked*. Go back to your terminal and write this command:

`fastboot flashing unlock` You can see the commands that I have written on my terminal below as well:

[insert 6.png from 2nd folder here]

Your phone(actually Google itself) is going to ask you if you want to risk unlocking the bootloader blablabla...Gibberish! But don't rush too fast, make sure you press on either the volume buttons so that the option that is right next to the power button will display *Unlock the bootloader*. Then you can let the magic happen. If everything went well, you should see your phone being booted with the *unlocked* (on a red text) right at the same *Device state*. Now you can go ahead and boot your phone back into the system. You might be getting Google's last attempt to make you realize how much you've sinned for daring to go out of their ecosystem with some pseudo-security warning, but don't worry, we know what we're doing. Oh, and by the way, your phone should have also wiped most of the data, so as I stated before, make sure to have taken a backup before this if needed. Here's also the screenshot of the bootloader stating that is unlocked:

[insert iPhone 2nd/3rd picture here]

#### Just quickly skip through the phone's usual configuration process, and now, very important, make sure to turn USB debugging mode and the rest of the required options back again! This is essential to keep in mind, as the phone's previous settings also got reset!

Good, we mainly turned the engine on, let's open the Chromium-based browser that I was talking about earlier, head over to the link above again and click on the *Flash* hyperlink. 

[insert 4.png from 2nd folder here]

Before running the browser flashing suite, please remember to send your phone back to the bootloader state again. In case you're confused about this, just run again the following command:

 `adb reboot bootloader`

To make everything simpler for you, go ahead and watch this video, it is the best way I had at my disposal to showcase how convenient the installation process gets once using the browser-based flashing tool:

[insert video1.mp4+video2.mp4 sau ce morti lui format are here]

Overall, make sure your device is well connected to your computer, follow the steps shown in the video, and let the installer do the rest. You don't need to touch anything else on your device until it's all installed and ready to go. If, for some reason, the USB connection drops suddenly, usually after the firmware is downloaded, try refreshing the browser or even testing with another one, **as it turns out not every Chromium-based browser is compatible with the flashing tool from Google**.

After the installer is finished, as displayed in the video, do not mind that it displays the flash has failed, it's simply because the connection was cut as we're running a clean factory firmware now, which also forces another reset of the settings we have enabled before, including the USB debugging mode. Nothing to worry about :).

As of now, this proved to be the more "sophisticated" part of this whole installation guide. Now we can simply jump to the more enjoyable and most satisfying part of all :D!


## Installation procedure II-III-IV. Installing Ubuntu Touch on our freshly flashed and unlocked Google Pixel 3A

Head over [Ubuntu Touch for Google Pixel 3A support website](https://devices.ubuntu-touch.io/device/sargo/) once again and download the installer from their downloads section, depending on what OS you're running on your desktop/laptop. As I've been using Ubuntu while writing this guide, I will go with the snap package as it's the fastest, but the Debian package or Appimage would have worked perfectly fine too.

[insert 7.png from 2nd folder here]
[insert 8.png from 2nd folder here]

As usual, do make sure you have enabled developer mode (we've had our data wiped out on the device after the flashing process again), as well as the USB debugging mode & ADB timeout option. Once that's done, I hope the following quick video is also going to be enough of a showcase for the final installation step process:

[insert video3.mp4 sau ce morti lui format are here]

If everything worked as expected on your side, congratulations, you have a complete Ubuntu powerhouse directly under your old (and possibly rusty) pixel device. You did it! You became most vendors' worst nightmare :)!


## Conclusions (I): Recommendations of an ecosystem alternative by combining UB Touch's functionality and Ubuntu on personal desktop computers

That was an extensive and authentic journey, wasn't it? Especially if you embarked yourself without having many of the prerequisites to be able to do all the steps casually. But all this doesn't matter anymore, as the final result is still the same. We have a fully functional smartphone, with all the features it has previously had via the factory's OS, just that everything finally seems to be more under our control. It is exactly how all users should feel about their phones! Full coverage over privacy controls and data that is shared, without any sketchy, hidden, confusing terms that obturate our understanding of the background processes. 

Hoping that the title is not misleading in any way, by the idea of an "ecosystem", and should be understood as options that we usually have in the current market. It is not to compare with those that offer a 100% type of unified experience, at the cost of owning the required devices from every single vendor. While this can still be achieved via the open-source path, we won't be able to touch the same functionality & won't turn out to be that practical or comfortable at the first glance for every type of user. That being said, my point was to prove something different.

While I was writing out this guide, although I stated here and there, but I wasn't fully clear, all the resources that I used for making this project were 100% open-source. I relied solely on Ubuntu OS, used an open-source app to write my notes, relied on an open-source app for creating tree maps to better structure my ideas, and presented exclusive open-source, free (and privacy-oriented, of course!) alternatives that were designed with the idea to replace as much as possible the functionality of currently most widely used solutions on a smartphone. 

At the same time, if, let's say, I had already had the Ubuntu Touch at my disposal before starting all of this, I could have easily relied on it with the daily tasks, and it is also worth mentioning that in terms of this OS's functionality, you will be noticing that there's a full operating terminal at your disposal, meaning that lots of the things that are accessible to be done through it (and implicitly via a Linux based distro) can be achieved inside the phone's environment! This is incredibly useful, especially if you are learning to become more "proficient" with Linux itself, meaning that many of the things learnt and done on the computer can be applied in the same manner on your phone. 

Although it may sound more complex at the beginning, this is how I chose to perceive the idea of creating our ecosystem, free from all the application and data processing clutter, that you do not personally choose to subscribe to by your direct consent, but it's rather enforced by the currently available vendors on the market. With that, I wish you a wonderful journey ahead and I truly hope that this approach could be considered convenient enough for the typical user (highly depending on what type we are talking about and what preferences every one of us has in terms of using a modern smartphone) to stay productive, be fully connected and armed in the digital world, without having to bother about the obnoxious expense of having our personal data and privacy played with.


## Conclusions (II) Overview of a list of popular app alternatives that are privacy-oriented and available to use.

Not to repeat myself, but as I was taking all the notes for this project, I did come across one distinct issue, which was either related to what my final objective meant when desiring to achieve a full privacy-oriented and functional smartphone, as well as the limitations that there are, sadly (but depending on each region, and I will explain in a few moments why) when comparing it with what features we currently have available by using the vendor provided operating system(s).

**The first problem**: 
As I have been exclusively focusing on the whole installation process of having Ubuntu Touch working on a chosen smartphone (the Google Pixel 3a), and it is true, I did state the restricted list of devices that are compatible for doing this, there's another issue that, in my humble opinion, has its root cause on a more social/cultural field that there is to be tackled on. And that is, in simpler terms, each area/region (a country would be the best example to be taken) has built its social habits that can be observed via a statistical approach on what, as a vast majority, smartphone devices consumers tend to buy, which by default translates as what applications they are using at a larger scale and under which conditions these are used to aid daily tasks, either for essential or recreational purposes (but there can be more case scenarios), through the help of modern phones themselves.

Take this as an example: 
In Romania, **Whatsapp* is by far one of the most popular communication apps that are running on various vendor-sold devices. It got so popular that a few years up to nowadays, it started to come installed by default with the factory operating system, meaning that Whatsapp, in this case, is not to be considered a standard app that you can download at your personal choice via Google Play store (remember that we're talking only about Android, as Apple powered devices did not take this approach, although the final result just comes under a different form, so it's the same outcome at the end of the day), but it became and still is the essential application that is used as a current substitute for phone calls, plus other integrated popular features for a quick, efficient and stupid-proof communication (including photo sharing, voice messages, video calls etc.). Do you want to know the other alternative in the winner list? Sure thing! We have **Messenger** (still provided by Meta) and **Instagram** (what a surprise, this is also provided by...Meta). So we're pretty much talking about the same company, same privacy policy, data processing etc., just that it's well-hidden under different app form factors. 

Of course, people are not to be blamed for this choice, Whatsapp mainly turned out of luck to be the most popular used app as it was seldom seen as an intrusive alternative for modern digital communication, and it was one of the least, if not the only viable option available for the general public to be used. And if that's taken through a social approach, people who do not possess much technical knowledge about the back-end processes, simply regard it as the *thing* that is used to talk to their relatives, friends, lovers etc. via voice or video calls. Of course, we have the social media functionality too, but I won't get much into that, as it targets the same concept. Even authorities here are relying on Whatsapp-based communication. What would be the reason for that? Well, there would be too many to attack, but a **poor digital infrastructure combined with a lack of digital-based research and domestic/local innovations in the tech field make more than sufficient of a mixture to end up with social and even cultural phenomena as this one**. 

By knowing this, if we were to imagine a scenario in which all phones would suddenly be running Ubuntu Touch (or other similar alternatives), as this particular OS alternative does not come with Whatsapp by default (and by the way, you can replace this app with just any other that are to be found in the similar case scenario), all the habits, activities, tasks that people were relying on Whatsapp to better or fully accomplish via its functionality would pretty much be harshly affected, if not even impossible to fulfil. And by adding more examples to the cart, you will be noticing that, in fact, **such an alternative OS starts to lose its initial meaning, as it drops its ability to replace the currently provided features by vendors, ending up actually...not to be considered an alternative anymore. Or at least, not a good enough one**. 

**The second problem**: 
This doesn't necessarily have to be separated from the first point, but the concept of a *PPDEP* (something I have also mentioned earlier) might end up sounding misleading for the general public, mainly due to its lack of the highly requested "straightforwardness" that people nowadays tend to look up for in, honestly, anything, along with the compromise of requiring to change specific habits that were solely relying on what individuals (from their respective targeted region) were initially using until now. This can be seen in many other situations, specifically if we take the whole OS battle that's been actively discussed on the internet for the past years. It is about the never-ending story of compulsively comparing which one is better or the best. One of the most popular examples would be the fight between Microsoft Windows, Apple's Mac OS and Linux-based distributions as to which one should be regarded as the finest operating system for **every single individual**. Not only that the questions that are being constantly raised are absurd, but there's no single answer to provide for such a dilemma. 

But to better reiterate my main idea, be aware that a regular person that just uses their computer for playing games, will hardly, if not never, trade his Windows-based siesta of opening a game via Steam's platform (a platform designed for digital games & digital items merchandise) through a few clicks over more complicated steps that have to be done for doing the same things on a Linux-based machine. If the game is not even compatible with the latter, then it's simply game over for Linux. This discussion can be broadened to many other examples, but what is to be remembered is that there's currently no easy peasy label for a precise approach or guide that is based on fully open-source and non-intrusive solutions that can completely replace what's been and is provided by the official, specialized vendors in this technical area. 

**What we should be looking for, instead, or put in other terms, what our approach should aim for, is the achievement of at least partially replacing some popular, but toxic/intrusive(or any other labels that you want) applications that prove not to be beneficial for the public, with alternatives that can bring almost same functionality on the table, at the least expense in terms of compromises**. 

That being said, if, in this case, Ubuntu Touch (as this one was my choice to be presented as a reliable alternative for most essential functions of a modern smartphone), or any other similar OS alternatives, proves not to be enough for you, the reader, or for any other given user(s), what other choices do we have at disposal for making all this process worth our time and resources?

Well, by approaching Android-based operating systems and devices yet again, if you scroll up back to the section where I showcased the list of available and reliable privacy-focused alternatives, some of them are still AOSP based, without having to rely on Google-based services, and that can still offer the same functionality and practicality at a high percentage. **In other words, it's still not a full replacement, but the compromise is quite low**.

Depending on what alternative you would like to further dig into or if you only would like to try/test some applications and see how well they can blend with the daily habits that require you to rely on your phone (meaning that you do not have to replace your current OS, you just have to install the apps which are easily available via either Google Play store or third-party, but safe application stores and repositories), I have taken my time to compile a more comprehensive list of alternative apps that should be able to replace what you're currently running on your device, without having to worry about too much hassle in terms of their installation process (which is pretty straightforward), or the overall usage. You can check it out right here:

[LIST OF ALTERNATIVE APPS DOCUMENT]

Also, as a bonus for reaching with your reading so far, to better strengthen my focus on the concept of relying on open-source software for heavy-duty tasks, here's the tree map that I was able to create via an application called **[Minder](https://github.com/phase1geo/Minder)**. 

I had no prior experience with either the concept or the software itself, but it still allowed me to dissect my thoughts and select the most important ideas that ultimately allowed me to compile this guide. It's quite clear that at this point everything made towards this project was done solely using **Ubuntu OS** (had it up and running on my secondary computer), plus a few other apps that I used to have everything finished (I will be adding them in the references section).


## Final words

It's mesmerizing how tackling one particular subject can be extended to such a scale, therefore there are for sure a lot of things that can be researched separately, which sadly, cannot be done via this brief guide. Instead, with the risk of repeating similar things that I have stated at the beginning of the project, I have intended overall to offer you, the readers, **an open invitation to a clearer understanding of the current modern smartphone phenomena, as well as providing a starting point for alternatives which can helpown personal to improve our daily activities, without the unpleasant costs of providing our personal information, including the cases where it's not done via our own consent**. The reality is that no perfect or official alternative can compete with the functionality that is being provided by other big vendors and which requires even wider costs to sustain it, but it does not necessarily mean that our lives should be fully dependent on what whatever merchant has to offer on the table. If we're able to see above that, then we can consider it as a proper right step into a more viable path (or more) that is available for us.

I truly wish that all this information has proven to be useful to you and that it allowed you to nurture a more objective perspective on the subject. Until next time, good luck with your journey on how to make the digital mobile world a safer space for all of you :)!

List of open-source tools that were used for compiling the whole project & references:
