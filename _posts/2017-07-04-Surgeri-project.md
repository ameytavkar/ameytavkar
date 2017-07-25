---
title: "SURGERi iOS App"
layout: post
date: 2017-07-04
tag: [startup, mvp, mobile app development, iOS Development, swift, core data, encryption, synchronization, offline database]
image: https://ameytavkar.github.io/ameytavkar/assets/images/surgeri-icon.png
headerImage: true
projects: true
hidden: true # don't count this post in blog pagination
description: "A specialized medical app targeted towards surgeons to collate and analyze their data in a never before fashion."
category: project
author: ameytavkar
externalLink: false
---

![Screenshot](https://ameytavkar.github.io/ameytavkar/assets/images/surgeri-screenshots.jpg)

<hr />
#### Apple Appstore Link - [SURGERi App](https://itunes.apple.com/in/app/surgeri/id1141836471?mt=8)
<hr />

The client had an idea and wanted to build their platform from scratch. The platform was targeted specifically to surgeons for collatating and digitizing their data. I worked with the client to build their iOS apps as well as engineered the apps to work in offline environment. 

I built the sync engine which enabled the surgeons to seamlessly synchronize the data so that without worring about network availability.

The application was heavily form based. I helped them redesign the forms by interating and re-iterating it with the surgeons which resulted into a better user experience for the surgeons which in turn increased the number of active users.

Development wise these forms were built using UITableviews and custom table cells to keep the look and feel as native as possible. This resulted in easy on-boarding for the surgeons who are not that tech-savvy.

I also built the cryptography modules using libraries such as SQLCipher and some propriety encryption algorithms. This helped them to have HIPAA compliant iOS apps which are mandatory in the US.

I helped the client setup the Apple developer account and worked with them to publish the app onto the Appstore. In the process we also made the app IPv6 compliant as this is one of the major requirements for an app to be submitted to the Appstore.
