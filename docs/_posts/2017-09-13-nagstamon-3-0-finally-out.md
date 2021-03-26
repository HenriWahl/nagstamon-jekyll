---
layout: post
title: Nagstamon 3.0 finally out
date: 2017-09-13 17:45:53
categories: releases
permalink: /nagstamon-3-0-finally-out
---

During the last year a lot of contributions to Nagstamon contained many improvements and new features – so many, that a new major version number is justified. The changes include:




* added **Kerberos authentification**

* added increased security by taking **TLS** seriously

* added **window mode**

* added large OK label for fullscreen and window mode

* added click-somewhere-to-close-statuswindow mode

* added custom views to Check_MK

* added monitor type Monitos3

* added monitor type SNAG-View 3

* added monitor type Sensu

* switched to pyinstaller



Also several fixes were necessary:




* fixes statuswindow garbage when changing mode

* fixed filename bug

* fixed check for .Xauthority file

* fixes for Centreon

* fixes for Check_MK 1.4.0

* fixes for Zabbix



The new TLS awareness surely will cause some trouble for users with self-signed certificates or those whose CA is not contained in the certificate store coming with Nagstamon. Please see [/how-to-solve-trouble-with-self-signed-certificates/](/how-to-solve-trouble-with-self-signed-certificates/) for details.


Thanks to [all of you](https://github.com/HenriWahl/Nagstamon/graphs/contributors) for contributing code, patience for testing and packages.


Get your free copy at [/download](/download).


