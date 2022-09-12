# GTA V Flags
![Version](https://img.shields.io/badge/Version-1.51-green.svg) ![License](https://img.shields.io/badge/License-MIT-blue.svg)

This repo hosts a JSON file that my GTA V handling-related tools use for decoding flags. This is just so I don't have to update each tool individually if flags are discovered or changed.

## Access the file here: [`flags.json`](https://raw.githubusercontent.com/adam10603/GTAVFlags/main/flags.json)

For an end-user utility to manipulate flags, [use my flag tool](https://github.com/adam10603/GTA5VehicleFlagTool).

The JSON's structure is backwards-compatible with [IKT's version](https://github.com/E66666666/GTAVHandlingInfo), just to make switching between them easy. There are some differences with my version though:
* There's an extra `author` property for easier distinction.
* Each flag has a `bit` property added. This is for human readers, it shouldn't be needed in code.
* Unofficial flag names deliberately have a different format from Rockstar's flag naming.
* Prefixes such as `HF_` are not used here.

## Version history

* v1.2
  * Initial release. Starting at 1.2, since I pulled the previously hard coded flag definitions from my flag tool at version 1.2. The version numbers will be decoupled from this point though.
* v1.3
  * Started to add some descriptions.
* v1.4
  * Changed the descriptions of handling flags `(1<<20)` and `(1<<21)` after re-testing.
  * Renamed handling flag `(1<<23)` to `Offroad ability 3` and changed its description after re-testing.
* v1.41
  * Minor rewording of descriptions added in v1.4.
* v1.5
  * Added a name for advanced flag `(1<<23)`.
  * Added a name and description for advanced flag `(1<<29)`.
  * Changed the name and description of advanced flag `(1<<16)` to reflect the changes in the Criminal Enterprises update.
* v1.51
  * Updated the descriptions of handling flags `(1<<20)` and `(1<<21)` after more testing.
* v1.52
  * Added a name and description for advanced flag `(1<<21)`.