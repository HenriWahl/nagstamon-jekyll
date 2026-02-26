---
layout: page
title: Download
permalink: /download
---

To support Nagstamon development or donate just have a look at **[contribution](/contribution)**.

## Stable release

Get the latest stable release **3.18.0** from **[GitHub stable release](https://github.com/HenriWahl/Nagstamon/releases/tag/v3.18.0)**.

## Latest development version

Get the latest binaries created automatically by [GitHub Actions](https://github.com/features/actions). Download from **[GitHub latest release](https://github.com/HenriWahl/Nagstamon/releases/tag/latest)**.

## Download from repositories

### Chocolatey

If you are using the great [Chocolatey](https://chocolatey.org) you can install Nagstamon easily via:

```shell
choco install nagstamon
```

### Winget

If you are using [Winget](https://learn.microsoft.com/en-us/windows/package-manager/winget/) you can install Nagstamon
easily via:

```shell
winget install -e --id HenriWahl.Nagstamon
```

### Homebrew

If you are using [Homebrew](https://brew.sh) you can install Nagstamon easily via:

```shell
brew install --cask nagstamon
```

### Debian

If you are using any [Debian](https://www.debian.org)-based distro like [Ubuntu](https://www.ubuntu.com) you can install Nagstamon from their official repo:

```shell
apt install nagstamon
```

**Note:** the move to Qt6 made Ubuntu versions older than 20.04 not work anymore.

Whichever version you want to use - first you need to add the GPG key:

```shell
curl -o /etc/apt/trusted.gpg.d/nagstamon.asc https://nagstamon.de/repo/debian/latest/key.gpg
```

If you want the **stable** release of Nagstamon you can add its Debian repository and GPG key to you sources:

```shell
echo "deb https://nagstamon.de/repo/debian/stable /" > /etc/apt/sources.list.d/nagstamon.list
```

If you want the **latest** release of Nagstamon you can add its Debian repository and GPG key to you sources:

```shell
echo "deb https://nagstamon.de/repo/debian/latest /" > /etc/apt/sources.list.d/nagstamon.list
```

To finally **install** just do the apt mantra:

```shell
apt -y update
apt install nagstamon
```

### Fedora

The **stable** release for Fedora is available via Nagstamon repository - just throw [https://nagstamon.de/repo/fedora/nagstamon.repo](https://nagstamon.de/repo/fedora/nagstamon.repo) into _/etc/yum.repos.d_:

```shell
curl -o /etc/yum.repos.d/nagstamon.repo https://nagstamon.de/repo/fedora/nagstamon.repo
```

The **latest** release for Fedora is available too via Nagstamon repository - just throw [https://nagstamon.de/repo/fedora/nagstamon-latest.repo](https://nagstamon.de/repo/fedora/nagstamon-latest.repo) into _/etc/yum.repos.d_:

```shell
curl -o /etc/yum.repos.d/nagstamon-latest.repo https://nagstamon.de/repo/fedora/nagstamon-latest.repo
```

Both versions simply get installed by:

```shell
dnf install nagstamon
```

### RedHat Linux 

The **stable** release for RedHat Linux is available via Nagstamon repository - just throw [https://nagstamon.de/repo/rhel/nagstamon.repo](https://nagstamon.de/repo/fedora/nagstamon.repo) into _/etc/yum.repos.d_:

```shell
curl -o /etc/yum.repos.d/nagstamon.repo https://nagstamon.de/repo/rhel/nagstamon.repo
```

The **latest** release for RedHat Linux is available too via Nagstamon repository - just throw [https://nagstamon.de/repo/rhel/nagstamon-latest.repo](https://nagstamon.de/repo/fedora/nagstamon-latest.repo) into _/etc/yum.repos.d_:

```shell
wget https://nagstamon.de/repo/rhel/nagstamon-latest.repo -O /etc/yum.repos.d/nagstamon-latest.repo
```

Both versions simply get installed by:

```shell
dnf install nagstamon
```

### Flatpak from flathub.org

The **stable** release is available at  [https://flathub.org/apps/de.nagstamon.nagstamon](https://flathub.org/apps/de.nagstamon.nagstamon).

If your system already knows the flathub.org repository for flatpaks, then simply install by

```shell
flatpak install de.nagstamon.nagstamon
```