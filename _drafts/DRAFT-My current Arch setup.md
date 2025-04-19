---
layout: post
title: "My current Arch setup"
---

## Intro

First of all, beware that this is not a super secure setup but an improvement over the average begginner installation. My objective is to use the available resources in my machine to improve a little bit the security of my setup while avoiding having to input multiple passwords before being able to use my computer.

My ideal would be to use Secureboot with my own keys that sign the boot process binaries up to the unlocking of the hard disk. If everything goes well, the encrypted hard disk should be unlocked via the TPM. This way I should be able to reach the login screen without having to input any password unless the device has been tampered with.

This setup will probably still be vulnerable to multiple attacks given the amount of software currently running in our devices ([even software we have no control over...](https://en.wikipedia.org/wiki/Intel_Active_Management_Technology)). At least the setup will deter attackers with basic knowledge about Linux systems and will require quite a bit more effort to break.

I will be commenting my usual installation procedure but for those who just want the setup files you can find them in the [archlinux-setup TODO](TODO) in my profile.

## Prepare the installation medium

I recommend you follow the first steps of the Archlinux installation guide on how to [acquire an installation image](https://wiki.archlinux.org/title/installation_guide#Acquire_an_installation_image), [verify it's signature](https://wiki.archlinux.org/title/installation_guide#Verify_signature) and [preparing the installation medium](https://wiki.archlinux.org/title/installation_guide#Prepare_an_installation_medium).

Once this is done it is time to properly configure the boot environment.

## Configuring UEFI

