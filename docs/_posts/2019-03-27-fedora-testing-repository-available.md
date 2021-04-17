---
layout: post
title: Fedora testing repository available
date: 2019-03-27 11:19:02
categories: releases
permalink: /fedora-testing-repository-available
---

According to [https://bugzilla.redhat.com/show_bug.cgi?id=1466709](https://bugzilla.redhat.com/show_bug.cgi?id=1466709) Nagstamon for Fedora is still stuck on version 1.0. To allow Fedora users to get updates automatically there is now a small repository available via [/files/repo/fedora/nagstamon-testing.repo](/files/repo/fedora/nagstamon-testing.repo).


Get it like:

`wget /repo/fedora/nagstamon-testing.repo --output-document=/etc/yum.repos.d/nagstamon-testing.repo`

`dnf install nagstamon`

This repository currently is not GPG signed – just before someone is asking.


