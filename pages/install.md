---
title: "Install"
layout: default
filename: install.md
--- 

### AUR

Install [plainde-meta](https://aur.archlinux.org/packages/plainde-meta) package

### Manual installation

Install dependencies: qt6-base noto-fonts-emoji polkit ttf-opensans make alsa-utils kwindowsystem

After installing dependencies run

```sh
curl -fsSL plainde.org/inst | sh
```

If you don't have `sudo` on your system, run as root

```sh
curl -fsSL plainde.org/instRoot | sh
```

## Run plainPanel

Now you can add plainPanel to your OpenBox/FluxBox/... autostart and enjoy!<br>

```
plainPanel
```
