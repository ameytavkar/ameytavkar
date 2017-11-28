---
title: "Private Signal for iOS"
layout: post
date: 2017-07-12
tag: [mobile app development, iOS development, touchID, sockets, real-time chat, push notification]
image: https://ameytavkar.github.io/ameytavkar/assets/images/signal-ios-icon.png
headerImage: true
projects: true
hidden: true # don't count this post in blog pagination
description: "A secured private messenger for targeted for intra-organization members."
category: project
author: ameytavkar
externalLink: false
---

![Screenshot](https://ameytavkar.github.io/ameytavkar/assets/images/signal-ios-screenshots.jpg)

<hr />
#### GitHub Link - [Signal for iOS](https://github.com/WhisperSystems/Signal-iOS)
<hr />

The client was using a private forked version of Signal iOS App which is an open source private messaging app. They wanted to extend security by adding a passcode to the app.

I worked with the client to build the passcode feature and iterated with a suitable set of use cases such as displaying the passcode screen when the user opens the app from the background or the app is open but inactive for 3 mins and so forth.

Additionally, I also integrated TouchID, which resulted in ease of use for the users. So now they could set the 4-digit passcode, but don't have to enter it every time. They can simply leverage the fingerprint sensor available on the iPhone.

In addition to the security features, the client also wanted to have custom notification tones per contact. I built a menu in the settings page of the contact to select the custom notification tone. I added all the custom sounds in a plist and used the plist as a data source for my menu. This helped the client's developers to easily add/remove custom tones without having to modify the existing code.
