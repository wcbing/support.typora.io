---
layout: post
title: Typora on Windows
author: typora.io
category: basic
tags: [Windows]
typora-root-url: ../../
typora-copy-images-to: ../../media/windows
---

This document shows some “native” features on Windows platform that you may use on your PC environment.

* Outline
{:toc}
### Install without Administer Privilege

If you do not have administer privilege on Windows, you can still run `typora-setup.exe`  and click "Install for current user only" to install it without admin privilege.

### Advanced Install

You can append the following command arguments for `typora-setup.exe` when installing Typora:

**/SILENT, /VERYSILENT** Instructs Setup to be silent or very silent. When Setup is silent the wizard and the background window are not displayed but the installation progress window is. When a setup is very silent the installation progress window is not displayed. 

**/ALLUSERS** Instructs Setup to install in administrative install mode. Only has an effect when the [Setup] section directive PrivilegesRequiredOverridesAllowed allows the commandline override.

**/CURRENTUSER** Instructs Setup to install in non administrative install mode. Only has an effect when the [Setup] section directive PrivilegesRequiredOverridesAllowed allows the commandline override.

Full supported command line arguments for installer.exe are listed [here](https://jrsoftware.org/ishelp/index.php?topic=setupcmdline).

### JumpList

Typora supports the [jump list](https://www.dummies.com/computers/operating-systems/windows-10/how-to-use-taskbar-jump-lists-in-windows-10/) on Windows, which includes quick actions (new file), recent files and recent folders. You can also pin the most used folders or files for quick access.

![Screenshot 2020-12-08 232339](/media/windows/Screenshot 2020-12-08 232339.png)

### Command Line

If Typora is set as the default Markdown editor, when in cmd.exe, typing `.\example.md` or `start example.md` will open this Markdown file.

If you add `typora.exe` in your  `PATH`, you can also use `typora .` or `typora example.md` to open the current folder or target file in Typora.

You can find more details [here](https://support.typora.io/Use-Typora-From-Shell-or-cmd/).

### New Markdown File from Context Menu

[Reference](https://gist.github.com/alexdevero/a079e3fc24adf759a26b4b5318921dc4)

You can click the following button in Typora's preferences panel and wait for a while or log out of your Windows.

<img src="/media/new-1.8/Snipaste_2023-12-14_18-22-51.png" alt="Snipaste_2023-12-14_18-22-51" style="zoom:50%;" />

### Pin Window

You can keep a Typora window in front of all other windows by clicking `View` → `Always on Top` from the menu bar. If you are using the unity style, you can click and hold the “maximize” icon and select the pin icon below it.

You can also [add a shortcut key](https://support.typora.io/Shortcut-Keys/#windows--linux) to `Always on Top`, then trigger it by hot keys.

<img src="/media/windows/Screenshot 2020-12-08 234643.png" alt="Screenshot 2020-12-08 234643" style="zoom:50%;border:1px solid grey" />

### Dark Mode

Typora supports dark mode on Windows 10, you can simply choose a dark theme under dark mode.

Or, you can set separate themes for light mode and dark mode. When the system’s color scheme changes, the corresponding theme you chose will be applied.

<img src="/media/windows/Screenshot 2020-12-08 234125.png" alt="Screenshot 2020-12-08 234125" style="zoom:38%;" />

You can find more details [here](http://support.typora.io/Dark-Mode/).

