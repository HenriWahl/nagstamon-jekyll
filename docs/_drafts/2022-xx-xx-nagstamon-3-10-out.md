---
layout: post
title: Nagstamon 3.10 out
date: 2022-xx-xx 23:51:34
categories: news
permalink: /nagstamon-3-10-out
---

Once again there is a new release of Nagstamon. It mostly consists of contributions by the community
and a switch to the latest major release of the underlaying Qt framework.
The results are better support for current monitoring servers and GUI features like higher resolution displays.

Main improvements are:

- switch to Qt6 on most platforms
- updated Centreon
- improved Zabbix
- new IcingaDB support
- Icinga2 fixes
- Prometheus fixes
- Checkmk 2.0 fixes
- show only active monitor servers in menus
- and many more small fixes

Some users might notice some of these changes:

- newer IcingaWeb installations might need switching to IcingaDBWeb server mode in Nagstamon
- multiscreen setups now access screens by name and not by number as before

As always get it at https://nagstamon.de/download.

