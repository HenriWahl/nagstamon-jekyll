---
layout: page
show_in_header: false
title: About
permalink: /
---

![Nagstamon as floating statusbar](/assets/images/index_1.png)

**Nagstamon** is a status monitor for the desktop. It comes with these **key features**:

* connects to multiple **monitoring servers**
* resides in **systray**, as a **floating statusbar** or **fullscreen** at the **desktop**
* showing a brief summary of critical, warning, unknown, unreachable and down hosts and services
* **pops up** a detailed **status overview** when being touched by the mouse pointer
* **connections** to displayed hosts and services are easily established by **context menu**
* **actions** can be triggered via SSH, RDP, VNC or any self defined connection
* users can be **notified** by sound and flashing window
* hosts and services can be **filtered** by category and regular expressions

![Nagstamon popup](/assets/images/index_2.png)

It is inspired by [Nagios Checker for Firefox](https://web.archive.org/web/20151105174526/https://addons.mozilla.org/de/firefox/addon/nagios-checker/) – just without an open Firefox window all the time to monitor the network.

Nagstamon is released under the [GPLv2](http://www.gnu.org/licenses/gpl-2.0.html) and free to use and modify.

Nagstamon is written in Python 3 and uses the Qt 5/6 GUI toolkit which makes it very portable. It has been tested successfully on latest Ubuntu, Debian, Fedora, Windows, NetBSD, OpenBSD, FreeBSD and macOS.
It works at least with GNOME, KDE, Windows and macOS desktops.

Successfully tested monitors include:

* [Nagios](https://www.nagios.org/) 1.x, 2.x, 3.x and 4.x
* [Icinga](https://www.icinga.org/) 1.2+ and 2.3+
* [Opsview](https://www.opsview.org/) 5+
* [Centreon](https://www.centreon.com/) 2.3+
* [Op5 Monitor/Ninja](https://www.op5.com/) 7+
* [Checkmk](https://checkmk.de/) 1.1.10+
* [Thruk](https://www.thruk.org/) 1.5.0+
* [Zabbix](https://www.zabbix.com) 2.2+
* [Monitos](https://www.monitos.de/) 4.4+
* [Prometheus](https://prometheus.io/)

Experimentally supported monitors:

* [Livestatus](https://docs.checkmk.com/latest/en/livestatus.html)
* [Monitos3](https://www.monitos.de/)
* [Sensu](https://sensu.io/)
* [SNAG-View 3](https://www.snag-view.de/)
* [Zenoss](https://zenoss.com/)

## Contact

If you find any problems please open an issue at [Nagstamon issues page at GitHub](https://github.com/HenriWahl/Nagstamon/issues).
Alternatively use mail address [contact@nagstamon.de](mailto:contact@nagstamon.de).
