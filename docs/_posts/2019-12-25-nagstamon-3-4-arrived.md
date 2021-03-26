---
layout: post
title: Nagstamon 3.4 arrived
date: 2019-12-25 23:30:00
categories: releases
permalink: /nagstamon-3-4-arrived
---

Finally a new stable version of Nagstamon is available. Its main changes were almost completely contributed by its community – thank you for all the [pull requests](https://github.com/HenriWahl/Nagstamon/pulls?q=is%3Apr+is%3Aclosed)!  
Among the most notable improvements is the new feature of multiple hosts and services selection which makes applying actions on them even faster:

![Selection of multiple items](/assets/images/nagstamon_multiple_selection.png)

The mostly complete list of changes looks like this:

* added multiple item selection and actions execution
* added notification for OK state
* added darkmode for macOS
* added option to copy service to clipboard
* added support for custom CA cert for Sensu/Uchiwa
* added support for IcingaWeb2 expire time
* added server encoding detection
* updated components
* fixed crash when selecting downtime on down host
* fixed settings filenames troubles by url-encoding them
* fixed pyinstaller onefile issues on macOS
* fixed Kerberos issues on macOS
* fixed Cinnamon systray/popup issue
* Centreon fixes 
* Checkmk fixes
* IcingaWeb2 fixes
* Monitos4x fixes
* op5Monitor fixes
* Sensu fixes


Wishing you a Merry Christmas and a Happy New Year.


