# QSMac (QuickStartMac)
*Start fresh after a clean installation of mac os*

# Overview

QSMac is a fork of [linuxify](https://github.com/fabiomaia/linuxify).

It uses [Homebrew](https://brew.sh/) to install all apps and packages so it needs to be installed first for QSMac to work.

The repo is divided into two parts:
1. Brewfile: This file was created with [homebrew bundle](https://github.com/Homebrew/homebrew-bundle) and it has a backup of all my installed apps and packages.
2. QSMac:
    - This file "linuxifies" mac os by installing all the GNU/Linux utilities replacements for the BSD utilities installed by default.
    - QSMac lets you do the following (as stated by --help argument):
        - install: install GNU/Linux utilities
        - uninstall: uninstall GNU/Linux utilities
        - info: show info on GNU/Linux utilities
        - config: add qsmac to shell config file

# Relevant Clarifications

- Brewfile already contains all packages that can be installed with QSMac.
- QSMac can safely uninstall all GNU/Linux utilities.
- In case of already having installed all packages through Brewfile you can run ``` ./QSMac config ``` to set everything up.

