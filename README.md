## NOTICE

**THIS IS NOT THE OFFICIAL FIRESTORM REPOSITORY**

This is a fork of Firestorm that has minor quality of life improvements - mainly aimed at the SLPW and other performance based communities. The value to you may vary.

Here are the current changes from the official client:

* mute typoed gestures (/xyx) - don't echo them to local chat
* New RLV command: @gesture=/ will run a gesture through RLV, meaning scripts (and WLV) can trigger gestures (if the gesture command starts with '/')
* new control key "toggle hearfrom" can be bound, works with HUD down. (I use Control-Tab). This lets you toggle hear voice from avatar/camera position without needing the UI up (for streaming).
* display hearfrom location in window title if hotkey is pressed (this lets you see it even when the hud is turned off for streaming)
* Gesture editor has F1-F12 listed first in keys
* Gesture editor removes duplicate sounds from sound list
* Gesture editor adds a button to zero out the hotkeys with a click
* Gesture editor has larger input fields (English only)
* Dump entire gesture list to clipboard (name, trigger and hotkey, plus disabled status)
* Enabled UUID columns in animation explorer
* Right-click inventory to export object names to clipboard

Each change is self-contained in its own branch, to make it easier to pull them out. However, I don't have any intention of going to the work to make properly formatted patches for upstream. If you wish to do so yourself, you have my permission (just let me know so I know to remove my code when I update).

Current version is Firestorm 7.2.4 (80611)

## Official

<img align="left" width="100" height="100" src="doc/firestorm_256.png" alt="Logo of Firestorm viewer"/>

**[Firestorm](https://www.firestormviewer.org) is a free client for 3D virtual worlds such as Second Life and various OpenSim worlds where users can create, connect and chat with others from around the world.**

This repository contains the official source code for the Firestorm viewer.

## Open Source

Firestorm is a third party viewer derived from the official [Second Life](https://github.com/secondlife/viewer) client. The client codebase has been open source since 2007 and is available under the LGPL license.

## Download

Pre-built versions of the viewer releases for Windows, Mac and Linux can be downloaded from the [official website](https://www.firestormviewer.org/choose-your-platform/).

## Build Instructions

Build instructions for each operating system can be found using the links below and in the official [wiki](https://wiki.firestormviewer.org).

- [Windows](doc/building_windows.md)
- [Mac](doc/building_macos.md)
- [Linux](doc/building_linux.md)

> [!NOTE]
> We do not provide support for compiling the viewer or issues resulting from using a self-compiled viewer. However, there is a self-compilers group within Second Life that can be joined to ask questions related to compiling the viewer: [Firestorm Self Compilers](https://tinyurl.com/firestorm-self-compilers)

## Contribute

Help make Firestorm better! You can get involved with improvements by filing bugs and suggesting enhancements via [JIRA](https://jira.firestormviewer.org) or [creating pull requests](CONTRIBUTING.md).

## Community respect

This section is guided by the [TPV Policy](https://secondlife.com/corporate/third-party-viewers) and the [Second Life Code of Conduct](https://github.com/secondlife/viewer?tab=coc-ov-file).

Firestorm code is made available during ongoing development, with the **master** branch representing the current nightly build. Developers and self-compilers are encouraged to work on their own forks and contribute back via pull requests, as detailed in the [contributing guide](CONTRIBUTING.md).

If you intend to use our code for your own viewer beyond personal use, please only use code from official release branches (for example, `Firestorm_7.1.13`), rather than from pre-release/preview or nightly builds.
