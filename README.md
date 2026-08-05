# Roblox-Client-Manager
A vibecoded open-source client manager for Roblox made with python.

## Features
This application allows you to easily install Roblox or any selected custom Roblox bootstrapper through a simple CLI.

It automatically installs the latest version of the selected bootstrapper and runs the setup file, it supports multiple bootstrappers and securely pulls only the authentic bootstrappers. (This way you can avoid the fake websites that create fraudulent copies of known bootstrappers, many of which include malware.) 

You can also fully uninstall Roblox and all custom bootstrappers in one key! As well as delete the traces of Roblox and the bootstrappers, since it deletes them from AppData and AppData>Temp.

It supports deleting the registry traces of Roblox and some registry traces for bootstrappers as well.

## Bootstrapper Support
- [Roblox (Standard Bootstrapper)](https://www.roblox.com/download)
- [Froststrap](https://github.com/Froststrap/Froststrap) (including pre-releases, as per option 3)
- [Bloxstrap](https://github.com/bloxstraplabs/bloxstrap)
- [Voidstrap](https://github.com/KloBraticc/Voidstrap)
- [Bubblestrap](https://github.com/ItzBloxxy/Bubblestrap)

### Disclaimer for Bootstrapper Support
Though I can confirm that every github repository that the application pulls from are the authentic, genuine bootstrappers (not fake copies), I cannot provide my guarantee that all programs will work as intended, are allowed by Roblox, or will continue to be 'safe' in the future.

It is up to the developers of these bootstrappers to ensure that their program reaches the expectations of its users.

## Why I made this
I wanted a program that will allow me to easily manage my Roblox and custom bootstrapper installations.

Originally, this program was based off another one that was a mac spoofer that I vibecoded, which was combined with the same uninstallation/cleaning logic for Roblox and custom boostrapper installations that is used in this one. 

The purpose of it was to bypass the Roblox ban api/banasync, however with the update of that api that introduced device bans, mac spoofing was no longer enough and required a more technical spoofer. (Such as [ByGoneSpoofer](https://github.com/nitaybl/ByGoneSpoofer).)

The mac spoofer was originally in batch, but then I moved on to to creating a python copy which was significantly better.

## Recommended bootstrapper
My personal recommendation would be Froststrap, just due to significant features and strong development. 

However, it is up to you to decide what bootstrapper fits you.

## Will this be updated?
I plan to update this as much as possible to support new bootstrappers and fix the installation if a bootstrapper's repo is deleted.

However, release v1.0.0 stands as an application that handles the most popular bootstrappers and even some lesser known ones.
