---
layout: post
title: How to solve trouble with self-signed certificates
date: 2017-09-13 17:30:26
categories: hints
permalink: /how-to-solve-trouble-with-self-signed-certificates
---

Since latest version 3.0 Nagstamon checks the validity of the monitor server’s certificate as default. This check can be disabled, but many users will see an **error message** in their Nagstamon status window when first starting:


![](/assets/images/Bildschirmfoto-vom-2017-09-13-17-24-38.png)


Pressing the **‘Fix error’-button** will show up the server’s settings dialog.


Here the problem can be kind of semi-solved by simply **ignoring** it:


![](/assets/images/fix_tls_ignore.png)


Way more secure is giving Nagstamon the certificate of the used **certification authority**. Please make sure it comes in **Base-64 encoded PEM** format:


![](/assets/images/Bildschirmfoto-vom-2017-09-13-17-39-09.png)


As result of these settings Nagstamon will tell you as before what’s wrong:


![](/assets/images/Bildschirmfoto-vom-2017-09-13-17-34-46.png)


