---
layout: post
title: Why are iOS apps abnormally larger than Android apps?
subtitle: iOS vs Android
tags: [iOS, Android, Technology]
image: "/img/android-vs-ios.jpg"
share-img: "/img/android-vs-ios.jpg"
---
If you've ever wandered around the app stores of Android devices and Apple devices, the insane size of iOS apps shouldn't be a new revelation to you.
Let's take a table for comparison.

| App | iOS Size | Android Size |
| :------ |:--- | :--- |
| WhatsApp | 237 MB | 23 MB |
| Uber | 332 MB | 61 MB |
| Instagram | 112 MB | 29 MB |
| Twitter | 113 MB | 17 MB |
| PUBG | 2.4 GB | 1.7 GB |
| Facebook | 231 MB | 52 MB |
| Gmail | 176 MB | 14 MB |
| LinkedIn | 167 MB | 25 MB |
| Chrome | 66.8 MB | 34 MB |

iOS apps are not only larger in size, they are getting larger day by day! These apps not only reduce your data plan significantly but they also eat up a noteworthy chunk of your device's memory.
<center>
<h2>iOS vs Android</h2>
<img src="/img/android_vs_ios.png">
</center>

The contributing factor to the large size of iOS apps is the constant addition of new features and updates. But, Android apps also receive updates, right? Let's find out the reasons given by iOS developers for the insane size of iOS Apps:

- ***SWIFT requirements:***<br> 
Swift is a general-purpose, multi-paradigm, compiled programming language developed by Apple Inc. for iOS, iPadOS, macOS, watchOS, tvOS, Linux, and z/OS. The requirements of Swift are considered as a major contributing factor to the size of iOS apps. For the successful creation and implementation of these apps, developers are required to wad the apps with numerous libraries and runtime libraries. These libraries, reportedly, make iOS apps heavier (and secure as well).<br>
On the other hand, Android's language "Kotlin" integrates directly into the existing Andorid infrastructure and doesn't need these kind of support libraries.<br>
The catch here is, Swift can help to easily add new features to apps while Kotlin cannot radically change the underlying infrastructure.

- ***Repitition in App Codes:***<br>
A single team does work on the entire app. Different functionalities are given to different teams for implementation. Due to this, there is a likelihood of functionality or component repitition when these components are compiled. This unfortunately leads to image files and databases occuring at multiple places in the same app, and hence an increase in the app size.

- ***Use of Multiple Assets:***<br> 
Androids apps use a single set of assets in their codes. Assets are the buttons, images, icons, etc. present in the app. In contrast, iOS apps make use of multiple versions and architectures so that the apps can fit on different screen sizes on iPhones and iPads. The existence of these multiple versions of assets in iOS apps greatly impacts their storage footprints. 
