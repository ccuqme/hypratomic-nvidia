### This repository has been archived.

### New image built from the [main uBlue image](https://github.com/ublue-os/main) can be found here on [ccuqme/ublue-hyperland](https://github.com/ccuqme/ublue-hyprland/).

This repo can be used as a example for using the [uBlue Starting Point](https://github.com/ublue-os/startingpoint) to create your personal Hyprland image.

# HyprAtomic

HyprAtomic is a custom uBlue image built with Hyprland. This image is not officially affiliated with uBlue or Fedora and is intended for personal use.

## Features

This image includes:

  * [uBlue Starting Point](https://github.com/ublue-os/startingpoint)
  * Hyprland
  * Waybar
  * Thunar
  * GDB
  * Btop
  * Cliphist
  * Qalculate
  * Fastfetch
  * Lite-xl
  * Android utilities (android-file-transfer, android-tools, and android udev rules)
  * Custom yafti configuration and first-time setup (with optional Flatpak apps)

For the full list of included components, please refer to [recipe.yml](recipe.yml) and [yafti.yml](usr/share/ublue-os/firstboot/yafti.yml).

## Prerequisites

This image is designed for Nvidia. For AMD/Intel, please use the [HyprAtomic](https://github.com/ccuqme/hypratomic) build.

## Usage

**Note**: Please back up your `.config` directory before running the following command. This operation carries certain risks and should be executed at your own discretion.

```bash
rpm-ostree rebase ostree-unverified-registry:ghcr.io/ccuqme/hypratomic-nvidia:latest
```

For more information on the features offered by uBlue, please refer to the [uBlue Starting Point](https://github.com/ublue-os/startingpoint) and [main uBlue image](https://github.com/ublue-os/main) documentation.

## License

This project is licensed under Apache-2.0.

#### Credits
* [gerblesh/uBlue-Hyprland](https://github.com/gerblesh/uBlue-Hyprland) - Where I got most of the configuration
* [JoshM-Yoru/dotfiles](https://github.com/JoshM-Yoru/dotfiles) - Where I got the Waybar theme
