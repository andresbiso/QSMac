# QSMac (QuickStartMac)

**QSMac is a modified fork of [linuxify](https://github.com/fabiomaia/linuxify)**

## Overview

- QSMac "linuxifies" mac os by installing all the GNU/Linux utilities replacements for the BSD utilities installed by default.
- QSMac lets you do the following (as stated by --help argument):
    - install: install GNU/Linux utilities
    - uninstall: uninstall GNU/Linux utilities
    - info: show info on GNU/Linux utilities
    - config: enter qsmac config

## Requirements

- Bash or bash compatible shell (e.g. zsh, etc.)

- [Homebrew](https://github.com/Homebrew/brew) (on macOS or [Linux](https://docs.brew.sh/Homebrew-on-Linux)) for installing dependencies.

## Usage

```
./qsmac install
```

## Notes

- QSMac can safely uninstall all GNU/Linux utilities.
- In case of having already installed all packages, you can run ``` ./QSMac config ``` to set everything up.

## Copyright

Copyright (c) 2020 Andrés Biso. See [LICENSE](https://github.com/andresbiso/QSMac/blob/master/LICENSE) for details.

