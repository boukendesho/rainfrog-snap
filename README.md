## rainfrog-snap
[![rainfrog](https://snapcraft.io/rainfrog/badge.svg)](https://snapcraft.io/rainfrog)

## Upstream
[![rainfrog](https://img.shields.io/github/v/release/achristmascarl/rainfrog?logo=github)](https://github.com/rainfrog/rainfrog)

rainfrog is a database tool for the terminal.
  
### Authors

This snap is maintained by me, and is not affiliated with the upstream project in any way. If you encounter any issues, please kindly report it here.

[![Get it from the Snap Store](https://snapcraft.io/static/images/badges/en/snap-store-black.svg)](https://snapcraft.io/rainfrog)

## Requirements

[Snap installed](https://snapcraft.io/docs/installing-snapd)

## Install

```bash
$ sudo snap install rainfrog
```
## Config file path

The config directory is different in snap rainfrog.

`/home/$USER/snap/rainfrog/common/`

Example:
```bash
$ cat /home/$USER/snap/rainfrog/common/rainfrog_config.toml
[settings]
mouse_mode = true
data_compact_columns = true
data_row_spacer = false
...
```

[Config File Example](https://github.com/achristmascarl/rainfrog/blob/main/.config/rainfrog_config.toml)

## Log file path

The config directory is different in snap rainfrog.

`/home/$USER/snap/rainfrog/current/.local/share/rainfrog/rainfrog.log`

## Doc

see: [Official Docs](https://github.com/achristmascarl/rainfrog?tab=readme-ov-file#usage)



