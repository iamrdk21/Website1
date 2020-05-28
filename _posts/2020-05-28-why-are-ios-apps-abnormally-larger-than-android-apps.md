---
layout: post
title: Why are iOS apps abnormally larger than Android apps?
subtitle: iOS vs Android
tags: [iOS, Android, Technology]
image: "/img/android-vs-ios.jpg"
share-img: "/img/android-vs-ios.jpg"
---
Fed with up with his Android smartphone, recently, my friend switched over to iOS and got himself an iPhone 8. While setting up his iPhone and installing various apps, he was astounded by the sheer size of iOS apps. The differences in the app sizes are overwhelming.

Let's take a table for comparison.

| App | iOS Size | Android Size |
| :------ |:--- | :--- |
| WhatsApp | 237 MB | 23 MB |
| Instagram | 112 MB | 29 MB |
| Twitter | 113 MB | 17 MB |
| Facebook | 231 MB | 52 MB |
| Gmail | 176 MB | 14 MB |
| LinkedIn | 167 MB | 25 MB |
| Chrome | 66.8 MB | 34 MB |
<center>
<h2>iOS vs Android</h2>
<img src="/img/apple-vs-android.png">
</center>
The two major reasons for the insane size of iOS Apps are:

- ***iOS:*** Distributed as native code that runs directly on the CPU. Apple includes different copies of the app's code for different CPU architectures. The app code, images, data files, etc. are all added to the app bundle, which overall increases it's responsiveness. Simply put, the size listed on the App Store includes all the versions of the app's code but fortunately enough, each device only downloads it's copy of the code.<br>
***Android:*** Distributed as CPU-indpendent "bytecode" that's converted to device's native code at runtime. More portable, but adds overhead.

- ***iOS:*** Include several different versions of their artwork-2x and 3x resolution, P3 color spaces and sRGB. Again, each device downloads only it's own art work but the App Store includes all the versions.<br>
***Android:*** Typically, they do not have so many versions of the artwork.

So the upshot here is:

iOS apps have tonnes of assets added to almost every app present on the App Store. While using iOS, you need not worry about the quid pro quo regarding the assets but while using Android you need to be careful about it. In general, iOS apps would be containing the additional data, causing the bulkiness, but the Android apps just lock their opening screens to the bundle and leave the rest of the work to the **Content Delivery Networks**, thus making it more or less pure code.  
