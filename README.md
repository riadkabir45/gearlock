# Introduction

GearLock is a dynamically written bash program focused in performance with the intension of making modifications in android-x86 easier.

It is also intended to replace the need of tradional custom-recovery softwares for android-x86 which are found in mobile phones.

GearLock was made in a totally different prespective unlike tradional custom-recovery softwares for mobile phones.

GearLock and everything within it are standalone programs and does not need to rely on android system.

It can be used both GUI and TTY in an user-friendly manner, including advanced cli usage.

# Features

I mainly post updates at https://supreme-gamers.com/r/gearlock-custom-recovery-replacement-for-android-x86.40

So, check there.

This repo is only used for development and issue tracking.

# Pre-baked GearLock

GearLock is being proudly integrated in the following reputated distros:

* BlissOS-x86
* PhoenixOS DarkMatter

If you're working on a remarkable distro and want to bring gearlock into it then you're welcome :)

# Development and Contriburing

Feel free to create a fork and help make this project even better.

If you want to build gearlock then all you gotta do is running the following command:

```bash
git clone https://github.com/AXIM0S/gearlock && cd gearlock && chmod +x makeme && ./makeme
```

Then you should find the outputs at `out/build_installer_out`

For working over sources for the core files, take a look at `core/` and `core/_external_bin/`

You might have noticed that there are prebuilt binaries in the repository but not their source code.

I would need to setup a complete build system for them, what I've been doing was hand-comping them.

I will need a lot of free time to accomplish this since I'm a student, but you can surely expect this in the furture.

# Additional Links

* GearLock Dev-Kit: https://github.com/AXIM0S/gearlock-dev-kit
* GearLock core-pkg: https://github.com/AXIM0S/gearlock-core-pkg
* GearLock mesa-pkg: https://github.com/AXIM0S/gearlock-core-pkg
* GearLock kernel-pkg: https://github.com/AXIM0S/gearlock-kernel-pkg
* GearLock Integration with distro: https://gitlab.com/AXIM0S/vendor-gearlock

# Credits and thanks

Here I'm trying to list all of the remarkable works by others which has been used to enrich GearLock.

Without their openminded hardwork over years GearLock wouldn't have been the same.

* The great legendary GNU communtiy for their free and opensource softwares.
> https://www.gnu.org/software
* Igor Pavlov (p7zip)
> http://p7zip.sourceforge.net
* mcmilk (p7zip zstd plugin)
> https://github.com/mcmilk/7-Zip-zstd
* Jack Palevich (Terminal Emulator)
> https://github.com/jackpal/Android-Terminal-Emulator
* Roumen Petrov (Better Terminal Emulator, Termoneplus)
> https://gitlab.com/termapps/termoneplus

* @hmtheboy154 (Contibutor)
* @SGNight (Contibutor)
* Mido Fayad (Contibutor & Donator)
* Ahmad Moemen (Contibutor)
* Diaz (Donator)
* rk (Donator)
