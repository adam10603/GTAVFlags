# GTA V Flags
![Version](https://img.shields.io/badge/Version-1.53-green.svg) ![License](https://img.shields.io/badge/License-MIT-blue.svg)

This repo hosts a JSON file that my GTA V handling-related tools use for decoding flags. This is just so I don't have to update each tool individually if flags are discovered or changed.

## Access the file here: [`flags.json`](https://raw.githubusercontent.com/adam10603/GTAVFlags/main/flags.json)

For an end-user utility to manipulate flags, [use my flag tool](https://github.com/adam10603/GTA5VehicleFlagTool).

The JSON's structure is backwards-compatible with [IKT's version](https://github.com/E66666666/GTAVHandlingInfo), just to make switching between them easy. There are some differences with my version though:
* There's an extra `author` property for easier distinction.
* Each flag has a `bit` property added. This is for human readers, it shouldn't be needed in code.
* Unofficial flag names deliberately have a different format from Rockstar's flag naming.
* Prefixes such as `HF_` are not used here.