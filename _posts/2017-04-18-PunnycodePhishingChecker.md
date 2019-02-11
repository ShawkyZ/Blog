---
layout: post
title: "Punnycode Phishing Checker"
description: ""
category: 
tags: [Phishing,Security,Chromeextension]
summary: "Punnycode Phishing Checker Chrome Extension"
crawlertitle: "Punnycode Phishing Checker"
date:   2017-04-18 23:09:47 +0700
categories: posts
author: shawkyz
---
دي chrome extension بسيطة كتبتها بتعرف اذا كان ال website ده مستخدم ال Punycode phishing technique ولا لا. الفكرة اني بجيب ال Url و بجرب اعمله decode ب punycode js library. لو النتيجة اللي طلعت ف الاخر كانت غير ال URL الحالي تبقى دي ممكن تكون فعلا phishing و بتظهر رسالة ف اول الصفحة تقول ده.
شكل الرسالة

![unsafe](/assets/images/unsafe.JPG)
ال extension و ال source code و شرح التحميل 

[https://github.com/ShawkyZ/PunycodePhishingChecker](https://github.com/ShawkyZ/PunycodePhishingChecker)