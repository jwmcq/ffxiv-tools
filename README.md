
# My shitty fork

This is forked from [a very helpful repo](https://github.com/valarnin/ffxiv-tools), and I have ripped out a lot of the very sensible code for managing older versions of Proton, made it more compatible with a Lutris Wine install, and also added compatability for using [XIVLauncher](https://github.com/goatcorp/FFXIVQuickLauncher) instead of the official launcher.

Basically, if you're on a fresh install, run `wine --version`, and get a number bigger than '5.2' then it should work. Don't @ me though. 

Follow the guide linked below - just ignore all the Steam/Proton parts. 

# FFXIV Tools
Tools for installing and configuring FFXIV and ACT on Linux

# Usage

Download or clone the repo

Run `./setup.sh` to do a full setup

Run `./setup-stage1.sh` to set up an FFXIV environment

Run `./setup-stage2.sh` to set up Proton for ACT support

See the [Guide](Guide.md) for the full guide
