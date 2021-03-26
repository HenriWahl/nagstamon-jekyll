---
layout: post
title: Nagstamon 2.0 finally out!
date: 2016-08-30 08:20:10
categories: releases
permalink: /nagstamon-2-0-finally-out
---

After a major overhaul Nagstamon is finally available in its 2.0 incarnation. Being formerly formed of Python 2 and GTK 2 it now comes freshly reshaped, made of Python 3 and Qt 5. This technology shift caused the longer absence of any other stable release, but was absolutely necessary to make sure there will be future releases too.

![](/assets/images/about_2.0.png)


These are some new features and fixes:


* Based on Qt 5 it now comes with a better integrated look-and-feel – especially remarkable on MacOS

* Partly simplified design

* Less clutter in setting dialogs

* Runs even on latest Windows and MacOS

* Uses QT 5 multimedia which means native sound on Linux and MacOS

* Uses only SVG graphics – allows changing colors even in systray icon

* Customizable font and font size

* Adjust to dark or light desktop theme

* Action allowing to copy host/service information to clipboard

* Added ‘Archive Event’ action for Check_MK monitors

* Additionally supports IcingaWeb2

* Updated Opsview and Centreon to support latest monitor server versions

* Experimental support for Livestatus and Zenoss

* New build script based on cx-Freeze for Windows and MacOS

* Native 64 bit version for Windows

* No or less memory leaks, especially in Windows

* Make sure only one instance per config is running

* Millions of fixes



Thanks go to everyone helping with code, ideas, time and patience to develop and test new bugs features! 🙂 For details see the GitHub [pull requests](https://github.com/HenriWahl/Nagstamon/pulls?q=is%3Apr+is%3Aclosed) and [issues](https://github.com/HenriWahl/Nagstamon/issues?q=is%3Aissue+is%3Aclosed) sections or the [CREDITS](https://github.com/HenriWahl/Nagstamon/blob/master/Nagstamon/resources/CREDITS) file…


