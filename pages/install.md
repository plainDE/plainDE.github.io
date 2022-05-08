---
title: "Install"
layout: default
filename: install.md
--- 

## On Arch Linux (or based on it)

Install `plainde-meta` AUR package.

## On any other linux distro

Install dependencies: qt6-base noto-fonts-emoji polkit ttf-opensans make alsa-utils kwindowsystem

  
```sh
git clone https://github.com/plainDE/plainInstaller
cd plainInstaller
chmod +x installer.sh
./installer.sh
```

# Run plainPanel

Now you can add plainPanel to your OpenBox/FluxBox/... autostart and enjoy!
```
plainPanel
```

**Note**. Use setxkbmap to change your keyboard layout.
