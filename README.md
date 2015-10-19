# radbeacon-flasher

# USAGE

On a mac you should not need to pass any options in to flash the default
firmware to the beacon. The firmware will be automatically downloaded. Use
the `-w` option to "watch" for the beacon to be plugged in and continue
flashing beacon.

For full usage run with `--help` option:

  radbeacon-flasher --help

# PREREQUISITES

This script requires both rbcomser and dfu-util.

rbcomser can be installed from source: [ble112-usb-comm](https://github.com/RadiusNetworks/ble112-usb-comm).


dfu-util can be found in most package managers:

```
  brew install dfu-util         ; # On Mac
  sudo apt-get install dfu-util ; # On Ubuntu
```
