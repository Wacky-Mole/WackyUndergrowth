# WackyUndergrowth

A Valheim mod that allows plants to grow beneath roofs and other covered structures.

## Features

- Removes the open-sky requirement for `Plant` instances.
- Plants treat `HaveRoof()` as `false`, so a roof does not prevent their growth.
- Does not change cultivated-ground, biome, temperature, grow-space, or other plant requirements.

## Installation

1. Install BepInEx for Valheim.
2. Copy `WackyUndergrowth.dll` to `BepInEx/plugins`.
3. Start Valheim.

Install the mod on both the server and all clients for consistent behavior in multiplayer.

## Compatibility

The mod patches Valheim's `Plant.HaveRoof()` method with Harmony. It is intended for the Valheim version referenced by this project.



For questions or suggestions please join discord channel: [Odin Plus Team](https://discord.gg/odinplus) or my discord at [Wolf Den](https://discord.gg/uPjjH8y52j)

Support me at https://www.buymeacoffee.com/WackyMole  or https://ko-fi.com/wackymole

<a href="https://www.buymeacoffee.com/WackyMole" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 60px !important;width: 217px !important;" ></a>

<a href='https://ko-fi.com/H2H6LL5GA' target='_blank'><img height='36' style='border:0px;height:36px;' src='https://storage.ko-fi.com/cdn/kofi3.png?v=3' border='0' alt='Buy Me a Coffee at ko-fi.com' /></a>

<img src="https://wackymole.com/hosts/bmc_qr.png" width="100"/>