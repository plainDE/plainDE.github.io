---
title: "Install"
layout: default
filename: install.md
--- 

### AUR

Install [plainde-meta](https://aur.archlinux.org/packages/plainde-meta) package

### Manual installation

Firstly, install the following dependencies:

| Distro | List of dependencies |
|---|---|
| Arch Linux | `qt6-base xorg noto-fonts-emoji polkit ttf-opensans make alsa-utils kwindowsystem python3 xcompmgr`|
| Ubuntu 22.04+ | `g++ qt6-base-dev fonts-noto-color-emoji make alsa-utils libkf5windowsystem-dev python3 xorg xcompmgr libxkbcommon-x11-dev` |

After installing dependencies run

```sh
sh -c "$(curl -fsSL plainde.org/install)"
```

or run this as root

```sh
sh -c "$(curl -fsSL plainde.org/installAsRoot)"
```

This script will install all plainDE components (plainPanel, plainControlCenter, plainAbout)

## Run plainPanel

Now you can add plainPanel (+ xcompmgr, if opacity is needed) to your OpenBox/FluxBox/... autostart and enjoy!

```sh
plainPanel
```
