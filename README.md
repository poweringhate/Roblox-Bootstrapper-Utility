# Roblox Bootstrapper Utility
A vibecoded open-source bootstrapper management utility for Roblox made with python.

Support me (skids need money too):

SOL: 5aDtrSqakrVufTHjvcu4Gr8f4gxYNYTdTgXj5MYGJHxw

LTC: ltc1qsxk8g9uwy2xt648rv5vy00es98wen0chh3tng7

BTC: bc1qxj04m8gfy9sck3paqr5w2qs9v9gggrwudv7ed4

ETH: 0x2ed93145af9b89aad12cb662c0c6d9504d83533b

## Features
This application allows you to easily install Roblox or any selected custom Roblox bootstrapper through a simple CLI.

It automatically installs the latest version of the selected bootstrapper and runs the setup file, it supports multiple bootstrappers and securely pulls only the authentic bootstrappers. (This way you can avoid the fake websites that create fraudulent copies of known bootstrappers, many of which include malware.) 

You can also fully uninstall Roblox and all custom bootstrappers in one key! As well as delete the traces of Roblox and the bootstrappers, since it deletes them from AppData and AppData>Temp.

It supports deleting the registry traces of Roblox and some registry traces for bootstrappers as well.

## Installation
Download the exe from [releases](https://github.com/poweringhate/Roblox-Bootstrapper-Utility/releases).

Alternatively, you can download the python script from the latest release.

Or you can copy it yourself from the [source](https://github.com/poweringhate/Roblox-Bootstrapper-Utility/blob/main/source) and save it as a python file.

You can also convert the python script to an exe file using pyinstaller.

## Command use
- help             - Display all available commands and detailed usage
- install <name>   - Present interactive installation menu or instantly install a specific bootstrapper by name
- uninstall <name> - Present interactive uninstallation menu or instantly uninstall a specific bootstrapper by name
- apps             - Present all installed installations for Roblox and other bootstrappers
- purge            - Completely uninstall Roblox, all custom bootstrappers, registry keys, and residual files

You can use "install" to select a bootstrapper to install, uninstall to select a bootstrapper to uninstall, or run those commands with the name of the program you want to install/uninstall (partial matching is used!).

For example running `install bubblestrap` will directly install bubblestrap rather then presenting the bootstrapper options, which are presented when running `install`.

If you run `install froststrap`, you will be presented with the option of the latest stable release or the latest pre-release.

The command `purge` will uninstall all bootstrappers and wipe their traces.

You can also view all the bootstrapper applications that are installed (including Roblox) by running the command `apps`.

## Bootstrapper Support
- [Roblox (Standard Bootstrapper)](https://www.roblox.com/download)
- [Froststrap](https://github.com/Froststrap/Froststrap) (including pre-releases)
- [Bloxstrap](https://github.com/bloxstraplabs/bloxstrap)
- [Voidstrap](https://github.com/KloBraticc/Voidstrap)
- [Bubblestrap](https://github.com/ItzBloxxy/Bubblestrap)

When a bootstrapper is supported, it means that both installation and uninstallation is supported.

Some exceptions apply, such as for repos that got taken down but are still active bootstrappers.

### Disclaimer for Bootstrapper Support
Though I can confirm that every github repository that the application pulls from are the authentic, genuine bootstrappers (not fake copies), I cannot provide my guarantee that all programs will work as intended, are allowed by Roblox, or will continue to be 'safe' in the future.

It is up to the developers of these bootstrappers to ensure that their program reaches the expectations of its users.

## Why I made this
I wanted a program that will allow me to easily manage my Roblox and custom bootstrapper installations.

Originally, this program was based off another one that was a mac spoofer that I vibecoded, which was combined with the same uninstallation/cleaning logic for Roblox and custom boostrapper installations that is used in this one. 

The purpose of it was to bypass the Roblox ban api/banasync, however with the update of that api that introduced device bans, mac spoofing was no longer enough and required a more technical spoofer. (Such as [ByGoneSpoofer](https://github.com/nitaybl/ByGoneSpoofer).)

The mac spoofer was originally in batch, but then I moved on to to creating a python copy which was significantly better.

## Recommended bootstrapper
My personal recommendation would be Bubblestrap, this is due to their support of multi-instancing.

This is compared to other bootstrappers that have removed the feature (even Froststrap) despite the fact that there has been no recorded bans for using multi-instancing and the feature is quite stable.

However, it is up to you to decide what bootstrapper fits you.

## Will this be updated?
I plan to update this as much as possible to support new bootstrappers and fix the installation if a bootstrapper's repo is deleted.

This repo was recently updated with a full revamp.

<img width="1104" height="615" alt="image" src="https://github.com/user-attachments/assets/284e5441-7f9d-4e56-a80b-e2daddfb8e8f" />

