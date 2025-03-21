<!--
  SPDX-FileCopyrightText: 2021-2022 Mikhail Zolotukhin <mail@gikari.com>
  SPDX-FileCopyrightText: 2018-2019 Eon S. Jeon <esjeon@hyunmu.am>
  SPDX-License-Identifier: MIT
-->

<div align="center">

# 🌈 Bismuth 🌈

#### Making tiling window management easy. On KDE Plasma.

[![wayland: supported](https://img.shields.io/badge/Wayland-Ready-blue?style=for-the-badge&logo=kde)](https://community.kde.org/KWin/Wayland)
[![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/Bismuth-Forge/bismuth?color=red&logo=github&style=for-the-badge)](https://github.com/Bismuth-Forge/bismuth/releases/latest)
[![Matrix](https://img.shields.io/matrix/bi:kde.org?label=Chat&server_fqdn=kde.modular.im&logo=matrix&style=for-the-badge)](https://matrix.to/#/#bi:kde.org)
[![Open Collective backers and sponsors](https://img.shields.io/opencollective/all/bismuth?label=Donators&logo=opencollective&style=for-the-badge)](https://opencollective.com/bismuth)

![demo](img/rice.png)

Arrange your windows in different grids to minimize the mouse usage.

## 🌟 Features 🌟

### Automatic window tiling

Save your time by automatically managing windows on your screen.

https://user-images.githubusercontent.com/14205339/148453685-f1bcfa46-4952-4b9d-a6f1-d2d75a0b4992.mp4

<br>

### Plasma integration

Power-up your workflow using native Plasma features - Virtual Desktops and
Activities.

https://user-images.githubusercontent.com/14205339/148562411-c9cca82a-c694-4794-b5e4-8fe716ec3d98.mp4

<br>

### Multiple Layouts

Use different layouts in different contexts.

https://user-images.githubusercontent.com/14205339/148564378-1def9350-a871-4f75-ba66-7a59ea1d4680.mp4

</div>

<br>
<br>
<br>

## 🏁 Getting Started

### Requirements

- A Linux distribution with KDE Plasma version 5.20 or higher
- Qt version 5.15 or higher
- KDE Frameworks version 5.78 or higher

You can check if your system matches these requirements by going to System
Settings > About this System.

### Installation

:warning: Distributions' packages are not affiliated with Bismuth developers.
If you encounter any issues with the incorrect installation, you should
contact the package maintainer first.

#### Arch Linux

- [AUR](https://aur.archlinux.org/packages/kwin-bismuth)

#### Debian

- [Volian Repository](https://volian.org/bismuth/)

#### Ubuntu

- [Official Repo](https://launchpad.net/ubuntu/+source/bismuth):

  ```bash
  sudo apt install kwin-bismuth
  ```

- [Volian Repository](https://volian.org/bismuth/)

#### Fedora

- [Official Repo](https://src.fedoraproject.org/rpms/bismuth):

  ```bash
  sudo dnf install bismuth
  ```
  
#### Solus

- [Official Repo](https://dev.getsol.us/source/bismuth)

  ```bash
  sudo eopkg install bismuth
  ```

#### OpenSUSE Tumbleweed

- [KDE Extra Repository](https://build.opensuse.org/package/show/KDE:Extra/bismuth)

#### Gentoo

- [VipreML Overlay](https://github.com/viperML/viperML-overlay/)

#### Void Linux

- [Official Repo](https://voidlinux.pkgs.org/current/voidlinux-main-x86_64/bismuth-3.1.4_1.x86_64.xbps.html)

  ```sh
  sudo xbps-install -S bismuth
  ```

#### From Source

- [See Dev Docs](CONTRIBUTING.md)

If you know a packaging solution for a distribution, that is not in the
list, please open a pull request.

### Usage

🎉 To start using Bismuth enable it in System Settings > Window Management >
Window Tiling. Additionally, you can decorate your windows in a tiling window
manager style (border-only windows) using the window decoration, that comes
with Bismuth. To do so, go to System Settings > Appearance > Window Decorations
and select the Bismuth decoration.

⌨️ You can view the shortcuts in System Settings > Shortcuts > Window Tiling. If
you used Krohnkite before, you can import some of its shortcuts using [the bash
script](contrib/import_krohnkite.sh).

🔧 If you want, you may also make a couple of manual fixes and tweaks to
improve your experience with window tiling. See [Tweaks
section](docs/TWEAKS.md).

### Configuration

You can configure Bismuth in the System Settings > Window Management > Window Tiling.

![Bismuth Configuration Module](img/config.png)

## 🤝 Acknowledgments

This project was made possible because of the hard work of other people on [Krohnkite
KWin Tiling Script](https://github.com/esjeon/krohnkite).
