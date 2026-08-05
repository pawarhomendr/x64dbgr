# x64dbgr

<img width="100" src="./src/bug_black.png"/>

An open-source Windows binary debugger designed for malware analysis and reverse engineering of executables for which you do not have the source code. It offers a wide range of features and a comprehensive plugin system that allows you to add your own functionality. You can find more information on the blog!

## Screenshots

<!-- TODO: recreate Chinese screenshots -->

![main interface (light)](.github/screenshots/cpu-light.png)

![main interface (dark)](.github/screenshots/cpu-dark.png)

| ![graph](.github/screenshots/graph-light.png) | ![memory map](.github/screenshots/memory-map-light.png) |
| :--: | :--: |

## Installation and Usage

1. Download a snapshot and extract it to a location where your user account has write permissions.
2. _Optional:_ Use `x96dbg.exe` to register a shell extension and add desktop shortcuts.
3. You can now run `x32\x32dbg.exe` to debug a 32-bit executable or `x64\x64dbg.exe` to debug a 64-bit executable. If you are unsure, you can simply run `x96dbg.exe` and select your architecture there.

You can also compile x64dbg yourself in just a few simple steps!

## Contributing

This is a community-driven project, and we welcome pull requests! Please refer to the CONTRIBUTING document for more information. If you have any questions, feel free to contact us or submit an issue. You can check out the "easy issues" list to get started with contributing. ## Credits

- Debugger core powered by TitanEngine Community Edition
- Disassembly engine powered by Zydis
- Assembler powered by XEDParse and asmjit
- Import reconstruction powered by Scylla
- JSON support powered by Jansson
- Database optimization powered by lz4
- Bug icon designed by VisualPharm
- UI icons designed by Fugue
- Website by tr4ceflow

## Developers

- mrexodia
- Sigma
- tr4ceflow
- Dreg
- Nukem
- Herz3h
- torusrxxx

## Code Contributors

You can find a detailed list of GitHub contributors here.

## Special Thanks

- Sigma for developing the initial GUI
- All donors!
- Everyone who submitted an issue!
- Anyone I forgot to add to this list
- Blog post authors
- EXETools community
- Tuts4You community
- ReSharper
- Coverity
- acidflash
- cyberbob
- cypher
- Teddy Rogers
- TEAM DVT
- DMichael
- Artic
- ahmadmansoor
- \_pusher\_
- firelegend
- kao
- sstrato
- kobalicek
- athre0z
- ZehMatt

x64dbgr would not be what it is today without the help of many people and other open-source projects—thank you all!
