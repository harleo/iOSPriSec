![iOSPriSec](https://cdn.rawgit.com/harleo/assets-repo/5f922f40/iOSPriSec/iosprisec_github_repo_logo.svg)  

📱 Useful tips on how to maximize and balance security and privacy on iOS  

## Preface

This guide will focus on the security and privacy aspects of the iOS platform. While Apple takes great interest in those aspects for both, their devices and its customers, it is important to go through additional steps because Apple gives you a great amount of options.

For more information on how Apple handles security and privacy, visit:
[https://www.apple.com/business/docs/iOS_Security_Guide.pdf](https://www.apple.com/business/docs/iOS_Security_Guide.pdf)  
[https://www.apple.com/lae/privacy/approach-to-privacy/](https://www.apple.com/lae/privacy/approach-to-privacy/)

---

### Contents
[1. Introduction](#1-introduction)
[2. Apple ID](#2-apple-id)
⋅⋅⋅ [2.1 Name, Phone Numbers, Email](#21-name-phone-numbers-email)
⋅⋅⋅ [2.2 Password & Security](#22-password--security)
⋅⋅⋅ [2.3 iCloud](#23-icloud)
⋅⋅⋅ [2.4 iTunes & App Store](#24-itunes--app-store)
[3. General](#3-general)
⋅⋅⋅ [3.1 Software Update](#31-software-update)
⋅⋅⋅ [3.2 AirDrop](#32-airdrop)
⋅⋅⋅ [3.3 Accessibility](#33-accessibility)
⋅⋅⋅⋅⋅⋅ [3.3.1 Face ID & Attention](#331-face-id--attention)
[4. Siri & Search](#4-siri--search)
[5. Touch ID/Face ID & Passcode](#5-touch-idface-id--passcode)
[6. Emergency SOS](#6-emergency-sos)
[7. Privacy](#7-privacy)
⋅⋅⋅ [7.1 Location Services](#71-location-services)
⋅⋅⋅⋅⋅⋅ [7.1.1 System Services](#711-system-services)
⋅⋅⋅⋅⋅⋅⋅⋅⋅ [7.1.1.1 Significant Locations](#7111-significant-locations)
⋅⋅⋅ [7.2 Analytics](#72-analytics)
⋅⋅⋅ [7.3 Advertising](#73-advertising)
[8. Phone](#8-phone)
⋅⋅⋅ [8.1 Show My Caller ID](#81-show-my-caller-id)
⋅⋅⋅ [8.2 SIM PIN](#82-sim-pin)
[9. Safari](#9-safari)
⋅⋅⋅ [9.1 Search Engine](#91-search-engine)

#### 1. Introduction
Nowadays words like privacy and security have been getting more relevant as ever before. This means that taking additional steps on how your devices interact and handle data with third parties is very important.

The devices—and third parties—you use, generate a large digital footprint of you every day, which you might be unaware of. Since that data belongs to you, I believe it should be yours.

Being naturally curious I've been tweaking settings on essentially every device I own. While I've been doing this for years for family and friends, I was under the assumption that everybody else was doing this. But I was wrong. The problem that I've been observing is that most of the people don't even give a second thought about going into the settings, they just want to use the device. What is shocking, is that even people in computer science related fields are subject to not tweaking settings while they should be doing it.

So I decided to do a short writeup to help you take the necessary steps on iOS (as much as you can do with the options that are provided).

#### 2. Apple ID
When opening the settings app on iOS, you should see your name associated with the Apple ID of your device at the very top of the list. Tap on it and you should also see the email associated with it, as well as a wide variety of options regarding your account.

##### 2.1 Name, Phone Numbers, Email
Choosing whether to put your real or fake name here is a controversial topic in of itself. If you happen to use any additional Apple services connected to this Apple ID, your name will obviously be associated with them.

Under the 'SUBSCRIPTIONS' section disable 'Announcements' and 'Apps, music, films and more'. This will help you get rid of marketing emails associated with the email addresses under the 'CONTACTABLE AT' section.

##### 2.2 Password & Security
Now, I want to educate you on how important it is to use a strong password for your Apple ID (and any service really), so please, if you use a weak password change it to something more complex. Depending on which services you are using, those might restrict you to their password requirements. This is not ideal because different services have different password requirements in order to function with their backend.

If you are unsure on how to create a good password, do read over some of those
links (the first one being most relevant because it's Apple's):
[https://support.apple.com/en-gb/HT201303](https://support.apple.com/en-gb/HT201303)  
[https://support.microsoft.com/en-us/help/4026406/microsoft-account-create-a-strong-password](https://support.microsoft.com/en-us/help/4026406/microsoft-account-create-a-strong-password)  
[https://support.google.com/accounts/answer/32040?hl=en](https://support.google.com/accounts/answer/32040?hl=en)  

Moving on you should definitely enable 'Two-Factor Authentication'. If you log into a new Apple device or their online services such as iCloud and use the same Apple ID, it will ask you for a code from one of your trusted devices in order to validate your identity.

##### 2.3 iCloud
The iCloud service is a way for you to store things like photos and other data from apps in order to offload storage or backup data to the cloud. Depending on whether you want that data on your device to be synced with other Apple devices you own, you can take the appropriate settings. If you want to take things a little bit further, and you want to know where and how that data gets stored, you can read about it in the 'iOS Security Guide—White Paper' on page 53 onwards here: [https://www.apple.com/business/docs/iOS_Security_Guide.pdf](https://www.apple.com/business/docs/iOS_Security_Guide.pdf).

Something important to note is that Apple recently announced that it is partly storing iCloud data in Google datacenters, which isn't a surprise, because it has also been storing data on other services like AWS, Amazon's cloud service. You can read more about it here: [https://arstechnica.com/gadgets/2018/02/your-apple-icloud-data-is-now-stored-on-google-servers-surprised/](https://arstechnica.com/gadgets/2018/02/your-apple-icloud-data-is-now-stored-on-google-servers-surprised/)

An interesting setting further down is the 'Find My iPhone'/'Find My iPad' feature. If your device happens to get stolen, you will be able to perform certain actions from the iCloud website, such as wipe, play a sound or put it in lost mode. Apart from that you will also be able to see the location of the device.

Way at the bottom there are 'Look Me Up' and 'Share My Location'. If you wish to do either of those as described in their respective settings, you can do so.

##### 2.4 iTunes & App Store
This section mostly contains things you can set to your liking, depending on your mobile data plan and its monthly data cap.

#### 3. General

##### 3.1 Software Update
This should be an obvious thing to do. Please keep your devices up to date. They not only provide new features, but most importantly security updates.

##### 3.2 AirDrop
AirDrop should be turned off ideally, or only for contacts. This will prevent other people to see your device in certain proximity (although this will also happen with Bluetooth turned on).

##### 3.3 Accessibility
##### 3.3.1 Face ID & Attention
Currently Face ID is only available on the iPhone X. If you use Face ID in the first place, enable the setting 'Require Attention for Face ID' which will make sure that you are actively looking at the device, with your eyes open, before attempting to unlock.

#### 4. Siri & Search
Depending on if you intend to use Siri, there are certain things to look out for. For example 'Allow Siri When Locked' will make Siri accessible by someone else while you're not around. Siri will perform certain tasks, such as send messages on your behalf, create calendar entries or set timers (more on this in section 5.).

#### 5. Touch ID/Face ID & Passcode
This is another controversial topic. Should you use Touch ID/Face ID for the sake of convenience or a strong alphanumerical passcode? Again, this is up to you. But note that in an event of a violent act towards you, it will be easier to get into your device by a simple touch or face unlock than providing a passcode. Also in the event of you travelling to the U.S., cases have shown that a border patrol officer is allowed to demand that you unlock your device by Touch ID but not by passcode. If you want to read more about this topic, here is an excellent in-depth guide by the Electronic Frontier Foundation: [https://www.eff.org/wp/digital-privacy-us-border-2017](https://www.eff.org/wp/digital-privacy-us-border-2017).

Under the 'ALLOW ACCESS WHEN LOCKED' section you can fine tune things to your liking, ideally as few accessible features as possible.

There is a rather interesting option all the way at the bottom. If you or someone else fails to unlock your device after 10 tries, it will wipe completely. Now the implication should be that the time between you interacting with your device one time and another time should be less than an hour. This is because if someone were to fail to attempt to unlock your device 9 times, a delay between unlocking attempts will be added up, and with 9 tries this delay is an hour. Depending on how sensitive the data on your device is, you would want to take the appropriate choice.

#### 6. Emergency SOS
Introduced in iOS 11, a feature in an event of an emergency, where if you were to hold the lock button and one of the volume buttons long enough, emergency services will be called from your device. While this feature has saved numerous lives since its introduction it is important to know that this includes Medical ID, a feature you can enable if you wish to do so. Medical ID is a feature where someone can look at basic information such as name, weight, height, emergency contacts (you can curate them) etc. while your device is locked. This is intended for instances where a medical professional can quickly gain information about you on-site, should you be unable to communicate.

#### 7. Privacy
##### 7.1 Location Services
The location services section is important to look at because you can either turn them off completely or fine tune them to allow specific apps to access your location data. Do so accordingly.

##### 7.1.1 System Services
Disable 'Location-Based Alerts' (else Apple might give you app recommendations based on your location), 'Location-Based Apple Ads' and 'Location-Based Suggestions', the rest is up to you.

In the section 'PRODUCT IMPROVEMENT' disable all four settings, because those will continuously use your location data in order to improve things like Apple Maps traffic data.

Way at the bottom is a setting you can enable in order for you to see an icon in your statusbar, whenever a service requests your location. This does just that, it's just a piece of interesting information for you to see.

If you want to read more about location services, visit:
[https://support.apple.com/en-us/HT207056](https://support.apple.com/en-us/HT207056)

##### 7.1.1.1 Significant Locations
This section will enable your device to remember important places based on your location in order to serve you location based information. You would want to disable this.

##### 7.2 Analytics
Disable 'Share iPhone Analytics'/'Share iPhone & Watch Analytics'/'Share iPad Analytics' and 'Share iCloud Analytics'. Normally this would help send daily diagnostic data to Apple in order for them to improve their services, but since this could include sensitive data such as locations, you would want to disable it.

If you wish to enable it, please read the two highlighted links inside that setting page, in order for you to evaluate their importance.

##### 7.3 Advertising
Enable 'Limit Ad Tracking' and tap on 'Reset Advertising Identifier...'. Now as noted below that setting, this might still mean that you will be served ads, but not as relevant anymore, which means it's less specifically tailored towards your interests.

#### 8. Phone
##### 8.1 Show My Caller ID
Here you will be able to hide your phone number from being displayed on the receiver's phone. Please note that this will most likely not hide it if you try to prank call emergency services.

##### 8.2 SIM PIN
If you do not already have a SIM PIN set, this would add an extra layer of security for your SIM card.

#### 9. Safari
This section will only apply to you if you actively use Safari as your iOS browser of choice. If you don't, you should start using Brave (see more here: [https://brave.com](https://brave.com)).

Disable 'Search Engine Suggestions', 'Safari Suggestions', and 'Preload Top Hit'. Those settings will be either synced (end-to-end encrypted) with your other Apple devices, or anonymized and send to Apple for analysis. See the highlighted link in that section, if you want to read more.

Enable 'Block Pop-ups'.

Under section 'PRIVACY & SECURITY' enable 'Prevent Cross-Site Tracking', 'Block All Cookies', 'Ask Websites Not To Track Me' and 'Fraudulent Website Warning'. Note that blocking cookies might restrict some features on websites. Continuing disable 'Camera & Microphone Access' and 'Check for Apple Pay'.

Also, please do yourself a favour and tap on 'Clear History and Website Data' once in a while (make sure you don't have any important tabs open, those will be deleted).

##### 9.1 Search Engine
If you wish to use a search engine that respects your privacy, please use DuckDuckGo as the default. DuckDuckGo will even allow you to proxy your search request by adding '!g' in front of your query to Google, in order to get Google's search result. For more information on why you should use it, visit: [https://duckduckgo.com/privacy](https://duckduckgo.com/privacy)

---

## Closing
Congratulations, you made it!
This should conclude this guide on how to take the necessary steps in order to improve security and privacy of your iOS device.

If you would like to help family or friends, share this guide!

[> Tweet It](http://twitter.com/share?text=Useful+tips+on+how+to+maximize+and+balance+security+and+privacy+on+iOS&url=https://github.com/harleo/iOSPriSec/blob/master/README.md)

---

by [@_harleo](https://twitter.com/_harleo)

_iOS version as of writeup: 11.2.6 (15D100)_

_12th of March 2018_
