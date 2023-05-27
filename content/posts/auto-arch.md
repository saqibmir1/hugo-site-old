---
title: "Auto Arch"
date: 2022-04-02T19:31:13+05:30
draft: false 
---

**Auto Arch is a shell script i made to install a fully functional arch system including all the software i use**

## Introduction

Just a few bash scripts to install Arch Linux, a desktop environment, all the software i use, and some tweaks.

### How to use
Run these commands on the initial prompt:

```
git clone https://github.com/saqibmir1
cd auto-arch
./install
```

### How it works

There are five scripts in total: install.sh, which installs the base arch; chroot.sh, which configures system in chroot env; kde.sh, which installs kde and other software packages; and finally postinstall.sh, which offers optional softwares installation options like office suite, steam etc. and does some tweaks too.

Only the install.sh is required (which is downloaded using curl). Other scripts will be downloaded automatically.

### What it does

- installs arch linux
- installs kde
- installs software that i use on daily basis
- does some kde tweaking and configuration
- deploys my dotfiles

**Github Link** to [Auto-Arch](https://github.com/saqibmir1/auto-arch)

**Thanks**

[Saqib Mir](https://saqibmir1.github.io) , [Reply To](mailto:mirsaquib3737@gmail.com)




