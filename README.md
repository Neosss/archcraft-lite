<p align="center">
<a href="https://archcraft.io"><img src="https://raw.githubusercontent.com/archcraft-os/archcraft-packages/main/archcraft-artworks/files/logo/png/logo-circle/logo-circle-1.png" height="128" width="128" alt="Archcraft"></a>
</p>

<p align="center">
<a href="https://www.buymeacoffee.com/adi1090x"><img width="32px" src="https://raw.githubusercontent.com/adi1090x/files/master/other/1.png" alt="Buy Me A Coffee"></a>
<a href="https://ko-fi.com/adi1090x"><img width="32px" src="https://raw.githubusercontent.com/adi1090x/files/master/other/2.png" alt="Donate for Archcraft on ko-fi"></a>
<a href="https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=6VETHHYHXESRN"><img width="32px" src="https://raw.githubusercontent.com/adi1090x/files/master/other/3.png" alt="Donate for Archcraft via Paypal"></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Maintained%3F-Yes-green?style=flat-square">
  <img src="https://img.shields.io/github/downloads/archcraft-os/archcraft-lite/total?label=downloads&logo=github&color=blue&style=flat-square">
  <img src="https://img.shields.io/github/stars/archcraft-os/archcraft-lite?style=flat-square">
  <img src="https://img.shields.io/github/issues/archcraft-os/archcraft-lite?color=violet&style=flat-square">
</p>

<p align="center">
A Nothing Version Of Archcraft, For Advanced Users.
</p>

<p align="center">
  <a href="https://archcraft.io" target="_blank"><img alt="home" src="https://img.shields.io/badge/HOME-blue?style=flat-square"></a>
  <a href="https://wiki.archcraft.io" target="_blank"><img alt="wiki" src="https://img.shields.io/badge/WIKI-blue?style=flat-square"></a>
  <a href="https://archcraft.io/gallery" target="_blank"><img alt="screenshots" src="https://img.shields.io/badge/SCREENSHOTS-blue?style=flat-square"></a>
  <a href="https://www.reddit.com/r/archcraft" target="_blank"><img alt="reddit" src="https://img.shields.io/badge/REDDIT-blue?style=flat-square"></a>
  <a href="https://discord.gg/3PzeJ5S7Pu" target="_blank"><img alt="discord" src="https://img.shields.io/badge/DISCORD-blue?style=flat-square"></a>
  <a href="https://t.me/archcraftos" target="_blank"><img alt="telegram" src="https://img.shields.io/badge/TELEGRAM-blue?style=flat-square"></a>
  <a href="https://matrix.to/#/#archcraft:matrix.org" target="_blank"><img alt="matrix" src="https://img.shields.io/badge/MATRIX-blue?style=flat-square"></a>
</p>

![img](images/preview.gif)

## Overview

**Compared to main [Archcraft](https://github.com/archcraft-os/archcraft), You'll not get -**
- Fancy Boot-loader (no grub themes)
- Fancy Boot Splash (no plymouth)
- Fancy Display Manager (themes and stuff)
- Multiple Window Managers and Styles
- Graphical / Calamares Installer
- Fancy Polybars, Rofi themes
- Even a Web Browser

**What you'll get -**
- A Simple Display Manager (`lxdm`)
- Just One Window Manager (`openbox`)
- A Smart and User-friendly shell (`fish`) 
- A Simple Panel (`tint2`)
- A Simple Launcher (`ulauncher`)
- Few Basic Apps (`terminal`, `file manager`, `text editor`)
- Few utilities (`media player`, `screen utilities`, `doc viewer`)
- Few CLI Programs (`vim`, `ranger`, `htop` etc)
- Just A CLI Installer (`abif`)
- And A Sweet Ocean-man...

## Latest Release

- **`ISO`** : [archcraft-lite-2021.11.13-x86_64.iso](https://github.com/archcraft-os/archcraft-lite/releases/download/v21.11/archcraft-lite-2021.11.13-x86_64.iso)
- **`SIG`** : [archcraft-lite-2021.11.13-x86_64.iso.sig](https://github.com/archcraft-os/archcraft-lite/releases/download/v21.11/archcraft-lite-2021.11.13-x86_64.iso.sig)
- **`SHA`** : [archcraft-lite-2021.11.13-x86_64.iso.sha256sum](https://github.com/archcraft-os/archcraft-lite/releases/download/v21.11/archcraft-lite-2021.11.13-x86_64.iso.sha256sum)
`3b9a9a13a5132ad7f8c5e2f369450f65cf7daf2b0979d847b400a598457571ec`
- **`TORRENT`** : [archcraft-lite-2021.11.13-x86_64.iso.torrent](https://github.com/archcraft-os/archcraft-lite/releases/download/v21.11/archcraft-lite-2021.11.13-x86_64.iso.torrent)

## Verify the authenticity of the ISO

- Download the **`ISO`**, **`gpg signature`** and **`sha256sum`** files
- Make sure all the files are present in the same directory (Assuming `~/Downloads`)
- First, Verify the details of the key on keyserver, Open a terminal and run (any one):
```
$ gpg --keyserver hkps://keys.gnupg.net --recv-keys 7DC81F73
$ gpg --keyserver hkps://keyserver.ubuntu.com --recv-keys 7DC81F73
$ gpg --keyserver hkp://pgp.mit.edu --recv-keys 7DC81F73
```

- Then, Open `terminal` in the `~/Downloads` folder and run following command :
```
$ gpg --verify archcraft-lite-2021.11.13-x86_64.iso.sig
```

- Finally, Verify the `sha256sum` by running :
```
$ sha256sum -c archcraft-lite-2021.11.13-x86_64.iso.sha256sum
```

## Screenshots

**`What you get :`**

|Display Manager|Window Manager|
|--|--|
|![img](images/lxdm.png)|![img](images/openbox.png)|

|Basic Applications|Media Player|
|--|--|
|![img](images/apps.png)|![img](images/mplayer.png)|

**`Make it what you want :`**

|Firefox - Code|Gimp - Inkscape|
|--|--|
|![img](images/code.png)|![img](images/gimp.png)|

---
> **`(!) This is a bloated distro. For People...`**
> - who think `X` is a bloat.
> - who think `WM` is a bloat.
> - who think `Terminal` is a bloat.
> - who think `File Manager, Text Editor` is a bloat.

> **`As mentioned above, This is only for ADVANCED and EXPERIENCED users.`**
> **`It's for people who want a distro with a bunch of basic programs, So using that as a base they can craft their Arch.`**

> Default `username` and `password` is **liveuser**.

> Don't forget to hit the **`STAR`** if you like it.
