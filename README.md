# GTAVFlags
![Version](https://img.shields.io/badge/Version-1.2-green.svg) ![License](https://img.shields.io/badge/License-WTFPL%20v2-blue.svg)

This repo hosts a JSON file that my GTA V handling-related tools use for decoding flags. This is just so I don't have to update each tool individually if flags are discovered or changed.

For an end-user utility to manipulate flags, [use my flag tool](https://github.com/adam10603/GTA5VehicleFlagTool).

The JSON's structure is backwards-compatible with [IKT's version](https://github.com/E66666666/GTAVHandlingInfo), just to make it easy to switch between them.

Note that this version contains additional properties compared to IKT's. I added an `author` property for easier distinction, as well as a `bit` property to each flag. The `bit` properties shouldn't be needed in code, it's only there for human readers.

The reason I'm hosting my own version is because I want to be able to directly edit flag names and descriptions without having to go through pull requests, and also to exclude some things I might not find accurate.

## Version history

* v1.2
  * Initial release. Starting at 1.2, since I pulled the previously hard coded flag definitions from my flag tool at version 1.2. The version numbers will be decoupled from this point though.