# QSMac (QuickStartMac)
*Start fresh after a clean installation of mac os*

## Overview

QSMac is a modified fork of [linuxify](https://github.com/fabiomaia/linuxify).

The repo is divided into two parts:
1. Brewfile: This file was created with [homebrew bundle](https://github.com/Homebrew/homebrew-bundle) and it has a backup of all my installed apps and packages.
2. QSMac:
    - This file "linuxifies" mac os by installing all the GNU/Linux utilities replacements for the BSD utilities installed by default.
    - QSMac lets you do the following (as stated by --help argument):
        - install: install GNU/Linux utilities
        - uninstall: uninstall GNU/Linux utilities
        - info: show info on GNU/Linux utilities
        - config: add qsmac to shell config file

## Requirements

- Bash or bash compatible shell (e.g. zsh, etc.)

- [Homebrew Bundle](https://github.com/Homebrew/homebrew-bundle), that makes use of:
    - [Homebrew](https://github.com/Homebrew/brew) (on macOS or [Linux](https://docs.brew.sh/Homebrew-on-Linux)) for installing dependencies.
    - [Homebrew Cask](https://github.com/Homebrew/homebrew-cask) is optional and used for installing Mac applications.
    - [mas-cli](https://github.com/mas-cli/mas) is optional and used for installing Mac App Store applications.

## Usage

1. If using Brewfile, you can easily install all dependencies with:
```
brew bundle
```
2. If using QSMac, you can easily install all dependencies with:
```
./qsmac install
```

## Notes

- Brewfile already contains all packages that can be installed with QSMac.
- QSMac can safely uninstall all GNU/Linux utilities.
- In case of having already installed all packages through Brewfile, you can run ``` ./QSMac config ``` to set everything up.

