---
layout: post
title: Happy birthday, Nagstamon!
date: 2018-08-15 00:00:07
categories: anniversaries
permalink: /happy-birthday
---

It is always hard to believe how fast time is passing by… especially if accompanying something from the very beginning. This year’s August 15th is the 10th anniversary of Nagstamon’s first release in 2008 – time to look back…  

![Happy birthday, Nagstamon!](/assets/images/nagstamon_10_cake_web.png)  

The first step for more relaxed monitoring has been the great [Nagios Checker for Firefox plugin](https://addons.mozilla.org/de/firefox/addon/nagios-checker/). It allowed to work without keeping an eye on the mail inbox to see if there where any alerts. But soon the need to watch a Firefox window to see the overall status became irritating too.


Being a user and fan of open source software for years I always wanted to give something back. Adding the need of even more convenience in an admin’s daily work and the wish to create something with Python the time had come for Nagstamon.


The first attempts were made with Linux and a then current GNOME2 desktop which caused the dependency of GTK2 for a while. Only at this platform a statusbar in the systray was possible – a feature which got lost later, but led to the different appearance options Nagstamon offers today, reaching from systray icon to statusbar, window and fullscreen.


![Nagstamon as statusbar in systray on GNOME2 in 2008](/assets/images/nagstamon-statusbar.png)

Pretty soon after the initial release it was also available for Windows due to the existence of PyGTK for this platform. Three years later there was a MacOS port too with lots of compromises due to GTK2.


Also pretty soon, once being used on a daily basis, a lot of improvements where added like context actions, systray icon, multiple monitors, sounds, or regexp filters. When switching from Nagios to Opsview at work in 2010 Nagstamon got support for Opsview too, which was the beginning of opening it for more and more originally Nagios-based monitoring servers.

![Context actions were available early](/assets/images/popup-monitor.png)

More and more people were involved, helping with bug reports, suggestions or code. It turned out to be a win-win situation: as much as users like it, care about and find problems or missing features, as a developer one learns a lot while fixing and implementing. Opening Nagstamon to other servers than Nagios involved even more helpful community members, which led to the vast [number of supported monitors](https://github.com/HenriWahl/Nagstamon/tree/master/Nagstamon/Servers) we have there today. An [incomplete list of contributors](https://github.com/HenriWahl/Nagstamon/graphs/contributors) can be seen at GitHub – incomplete, because some contributed by mail and not all contributors are visible anymore after the move from SourceForge to GitHub in 2012.


With the rise of GNOME3 and its underlaying GTK3 framework the one used by Nagstamon was about to become even more unsupported. It worked really well only on Linux anyway. After releasing version 1.0 in 2014 I started to check alternatives and found out very soon that the successor of GTK2 worked even worse on Windows and MacOS. So the only way out was a complete port to a different framework. Qt5 was then chosen due to its great support of multiple platforms. Once changing almost everything the necessary port to Python3 was the simplest task.


The port to Qt5 took longer than expected and so the shiny version 2.0 came out in 2016 with a lot of framework-related improvements – most notably a more consistent look and feel across all supported platforms.


![](/assets/images/about_2.0.png)


Version 3.0 came out in 2017 adding more community contributed monitor servers and increased security.


![The number of supported monitor servers has grown in the last 10 years…
](/assets/images/monitors.png)

It’s the year 2018 and after 10 years there are still enough [bug reports and feature requests](https://github.com/HenriWahl/Nagstamon/issues). For example some evergreens are the wish for better filters and bulk actions – yes, they will come, someday.  



Due to other pet projects like [dhcpy6d](https://dhcpy6d.de/) and a generally changed focus I find less time to add amazing new features. Anyway I am still very interested in Nagstamon, but I do not think all bugs will ever be fixed and not all requested features will ever be implemented – at least not by me or rather slowly. I am open to any kind of contribution and happy to merge pull requests, so any fellow Nagstamon user is invited to become a fellow developer.


As a conclusion I want to thank all those great people who helped to improve this little project – thanks for inspiring and teaching a lot and last but not least helping with your contribution to facilitate proactive monitoring! Therefore bigger disasters in systems around the world were and will be avoided.


May your Nagstamon always show you a green OK.  



