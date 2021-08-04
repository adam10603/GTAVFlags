# GTAVFlags
![Version](https://img.shields.io/badge/Version-1.2-green.svg)

This repo hosts a JSON file that my GTA V handling-related tools use for decoding flags. This is just so I don't have to update each tool individually if flags are discovered or changed.

## Access the file here: [`flags.json`](https://raw.githubusercontent.com/adam10603/GTAVFlags/main/flags.json)

For an end-user utility to manipulate flags, [use my flag tool](https://github.com/adam10603/GTA5VehicleFlagTool).

The JSON's structure is backwards-compatible with [IKT's version](https://github.com/E66666666/GTAVHandlingInfo), just to make it easy to switch between them.

This version contains additional properties compared to IKT's. I added an `author` property for easier distinction, as well as a `bit` property to each flag. The `bit` properties are mostly there for human readers.

## Version history

* v1.2
  * Initial release. Starting at 1.2, since I pulled the previously hard coded flag definitions from my flag tool at version 1.2. The version numbers will be decoupled from this point though.