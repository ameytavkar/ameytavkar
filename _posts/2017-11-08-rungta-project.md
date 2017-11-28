---
title: "Rungta Academy Registration"
layout: post
date: 2017-11-08
tag: [startup, iPad, iOS Development, swift, realm, synchronization, offline database, AWS, AWSSES]
image: https://ameytavkar.github.io/ameytavkar/assets/images/rungta-ios-icon.png
headerImage: true
projects: true
hidden: true # don't count this post in blog pagination
description: "An iPad app to help visitors in a conference signup in a more modern way."
category: project
author: ameytavkar
externalLink: false
---

![Cover](https://ameytavkar.github.io/ameytavkar/assets/images/rungta-cover-image.jpg)

The client wanted the app to be developed in a very short amount of time as this app was needed to be ready for a big conference. The client wanted the UI of the app to quite simple and functional. One of the main caveats of the conference was limited internet connectivity. To avoid loss of data, the app stores all the data in an offline Realm database and synchronizes whenever there is network connectivity.

The app is completely written in Swift 4 and is compatible from iOS 9 onwards. This is an iPad app, so supporting both the orientations was necessary. Auto layout and sizing classes were used to achieve this.

Interesting part of the experience for the users were, they would immedieately receive an SMS and Email when they would sign up. This helped them with further process. For email Amazon's SES was used. AWSSES SDK was configured and integrated into the project.

I also helped the client to setup testflight accounts and distribute the apps to their employees for testing and validation purposes.
