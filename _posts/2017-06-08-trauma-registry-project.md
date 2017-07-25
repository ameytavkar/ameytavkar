---
title: "Trauma Registry iOS App"
layout: post
date: 2017-06-08
tag: [mobile app development, iOS Development, swift, realm, synchronization, offline database, tesseract ocr]
image: http://ameytavkar.github.io/ameytavkar/assets/images/trauma-icon.png
headerImage: true
projects: true
hidden: true # don't count this post in blog pagination
description: "A medical registry app to enable the surgeons registered under the medical society to collect and collate special cases for research purposes"
category: project
author: ameytavkar
externalLink: false
---

![Screenshot](http://ameytavkar.github.io/ameytavkar/assets/images/trauma-screenshots.jpg)

<hr />
#### Apple Appstore Link - [Trauma Registry App](https://itunes.apple.com/in/app/trauma-registry/id1150440354?mt=8)
<hr />

The client wanted to build a mobile based registry for their client's medical society. This app is specifically targeted towards surgeons who are always on the go but want to collate data for their researches.

I worked with them to build a offline first mobile app which enabled the surgeons to enter data regardless of the network availability. Behind the scenes there was a synchronization engine built to work seamless with local realm database and the server. This synchornization engine took care of uploading and download any records that were created on app or on the server. It would also sync the records, even if the app was in background, so the surgeons would not have to do clerical work of always opening the app and syncing the records.

There is a deep search functionality integrated in the app, so the surgeon can type in any keyword and the app will display the matching results in form of a list.

OCR (Optical Character Recognition) was another interesting feature that was required in the app. As the app is heavy on the data entry part, to ease the clerical job of entering the data, the surgeon could use the OCR functionality to scan the documents and the data would be prefilled in the required fields. This functionality reduced their data entry time to great extent.

Development wise an open source ocr engine called [Tesseract OCR](https://github.com/tesseract-ocr/) was used. This engine is written in C++ and was integrated into our Swift code.

I built the sync engine which enabled the surgeons to seamlessly synchronize the data so that without worring about network availability.

The application was heavily form based. I helped them redesign the forms by interating and re-iterating it with the surgeons which resulted into a better user experience for the surgeons which in turn increased the number of active users.

I helped the client setup the Apple developer account and worked with them to publish the app onto the Appstore. In the process we also made the app IPv6 compliant as this is one of the major requirements for an app to be submitted to the Appstore.
