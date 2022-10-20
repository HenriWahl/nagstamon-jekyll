---
layout: post
title: Nagstamon 3.10 out
date: 2022-xx-xx 23:51:34
categories: news
permalink: /nagstamon-3-10-out
---

The current testing release 3.9-20221011 has many changes with made it more mature in the last months.
It does not much left on its way to stable 3.10. release.


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

Some hints:

- newer IcingaWeb installations might need switching to IcingaDBWeb server mode in Nagstamon
- multiscreen setups now access screens by name and not by number as before