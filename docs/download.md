---
layout: page
title: Download
permalink: /download
---

## Stable release

Get the latest stable release **3.8.0** from **[GitHub stable release](https://github.com/HenriWahl/Nagstamon/releases/tag/v3.6.0)**.

## Latest development version

Get the latest binaries created automatically by [GitHub Actions](https://github.com/features/actions). Download from **[GitHub latest release](https://github.com/HenriWahl/Nagstamon/releases/tag/latest)**.

## Download from repositories

### Chocolatey

If you are using the great [Chocolatey](https://chocolatey.org) you can install Nagstamon easily via:

```terminal
c:\> choco install nagstamon
```

### Homebrew

If you are using [Homebrew](https://brew.sh) you can install Nagstamon easily via:

```terminal
# brew install --cask nagstamon
```

### Debian

If you are using any [Debian](https://www.debian.org)-based distro like [Ubuntu](https://www.ubuntu.com) you can install Nagstamon from their official repo:

```terminal
# apt install nagstamon
```

### Flatpak

If you are using the shiny Flatpak you can install Nagstamon via:

```terminal
# flatpak install flathub de.ifw_dresden.nagstamon
```

### Fedora

The **stable** release for Fedora is available via Nagstamon repository - just throw [https://nagstamon.de/repo/fedora/nagstamon.repo](https://nagstamon.de/repo/fedora/nagstamon.repo) into _/etc/yum.repos.d_:

```terminal
# wget https://nagstamon.de/repo/fedora/nagstamon.repo -O /etc/yum.repos.d/nagstamon.repo
```

The **latest** release for Fedora is available too via Nagstamon repository - just throw https://nagstamon.de/repo/fedora/nagstamon-latest.repo into /etc/yum.repos.d:

```terminal
# wget https://nagstamon.de/repo/fedora/nagstamon-latest.repo -O /etc/yum.repos.d/nagstamon.repo
```

Both version simply get installed by:

```terminal
# dnf install nagstamon
```

