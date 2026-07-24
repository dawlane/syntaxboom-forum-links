# List of Atari 8 Computer Bit Development Tools - Emulators

This is is going to be the start of a list of useful links to various tools for programming Atari 8 Bit home computers. If anyone adds some gems, then they will be added to this post, so people don't have to go through every post.

**NOTE:** Many of these sites linked here, have not been fully checked or validated for what contents they offer, and possibly in the future they may also be broken. Anyone using the links should remain vigilant to protect themselves from malicious software and sites through the use of internet security software and good judgement by not falling prey to sites that require the specific entry of personal information. The accuracy of the descriptions may also not be correct, and should be in many cases considered a work-in-progress.
If they don't appear to be what is advertised, or look suspicious.
Then PM an administrator so they can be removed, or updated with the correct information.  
**So use these links and any associated software from these sites at your own risk!**  

## Table of Contents

- [Altirra](#altirra-header)
- [AltirraSDL](#altirrasdl-header)
- [Atari++](#atari-header)
- [Atari800](#atari800-header)

---

<a id="altirra-header"></a>

## Altirra

**Official URL**
https://www.virtualdub.org/altirra.html

**Host Platforms**

- Windows

**Verified Target Systems**

- Atari 400
- Atari 800
- Atari 1200XL
- Atari 600XL
- Atari 800XL
- Atari 65XE
- Atari 130XE
- Atari XE Game System

**Overview**  
Altirra is widely regarded as the reference emulator for the Atari 8-bit family. It provides exceptionally accurate hardware emulation together with one of the most comprehensive integrated debugging environments available for any retro computer platform. Designed for both software development and hardware research, it emulates the complete Atari hardware environment, including CPU, ANTIC, GTIA, POKEY, PIA, storage devices, cartridges, peripherals, and numerous hardware expansions.

The emulator is particularly valued by developers for its advanced debugger, hardware inspection tools, execution tracing, profiling facilities, symbol loading, and breakpoint system. These capabilities make Altirra an indispensable development and testing platform for modern Atari 8-bit software.

**Development Features**

- Cycle-accurate emulation
- High compatibility
- Integrated machine language monitor
- Source-level debugging
- Symbol file support
- Conditional breakpoints
- Memory breakpoints
- Execution tracing
- CPU profiling
- Hardware register inspection
- Memory viewer
- Disassembler
- Cartridge emulation
- Disk drive emulation
- Printer and peripheral emulation
- Save states
- Command-line support

**Supported File Formats**

- .ATR
- .ATX
- .BIN
- .CAR
- .CAS
- .COM
- .ROM
- .SAP
- .XEX

**Debugging Features**

- Source-level debugger
- Breakpoints
- Watchpoints
- Memory inspector
- Disassembler
- CPU state inspection
- Symbol loading
- Execution history
- Performance profiler

**Integration**

- Integrated Development Environments
  - ATasm Altirra Bridge
  - WUDSN IDE
- Assemblers
  - ATasm
  - MADS
- Cross-Compilers & High-Level Languages
  - cc65
  - FastBasic
  - Mad Pascal

**Primary Purpose**  
High-accuracy Atari 8-bit emulator with professional debugging facilities for software development.

---

<a id="altirrasdl-header"></a>

## AltirraSDL

**Official URL**
https://github.com/ilmenit/AltirraSDL

**Host Platforms**

- Windows
- Linux
- macOS
- Android
- Web

**Verified Target Systems**

- Atari 400
- Atari 800
- Atari 1200XL
- Atari 600XL
- Atari 800XL
- Atari 65XE
- Atari 130XE
- Atari XE Game System

**Overview**  
AltirraSDL is the official cross-platform port of the Altirra emulator, developed by Ilmenit in cooperation with Altirra author Avery Lee. It combines Altirra's highly accurate emulation core with a modern SDL3 and Dear ImGui user interface, allowing the emulator to run natively on Linux, macOS, Windows, Android, and in modern web browsers through WebAssembly.

The project aims to provide feature parity with the Windows version of Altirra while making its advanced debugging capabilities available on additional operating systems. Although still under active development, it already includes comprehensive hardware emulation, an advanced multi-window debugger, configurable hardware profiles, shader support, and broad media compatibility, making it a significant addition to the Atari development ecosystem. :contentReference[oaicite:0]{index=0}

**Development Features**

- Cross-platform implementation
- SDL3 user interface
- Dear ImGui interface
- High-accuracy Altirra emulation core
- Multi-window debugger
- Source-level debugging
- Breakpoints
- Memory inspection
- Disassembler
- Cartridge emulation
- Disk drive emulation
- Cassette emulation
- Shader support
- Save states
- WebAssembly build

**Supported File Formats**

- .ATR
- .ATX
- .BIN
- .CAR
- .CAS
- .COM
- .ROM
- .SAP
- .XEX

**Debugging Features**

- Source-level debugger
- Breakpoints
- Watchpoints
- Memory viewer
- CPU state inspection
- Disassembler
- Symbol loading

**Integration**

- Assemblers
  - ATasm
  - MADS
- Cross-Compilers & High-Level Languages
  - cc65
  - FastBasic
  - Mad Pascal

**Primary Purpose**  
Cross-platform port of the Altirra emulator providing high-accuracy Atari 8-bit emulation and advanced debugging facilities. :contentReference[oaicite:1]{index=1}

---

<a id="atari-header"></a>

## Atari++

**Official URL**
http://www.xl-project.com/

**Host Platforms**

- Windows
- Linux
- macOS

**Verified Target Systems**

- Atari 400
- Atari 800
- Atari 1200XL
- Atari 600XL
- Atari 800XL
- Atari 65XE
- Atari 130XE
- Atari XE Game System

**Overview**  
Atari++ is a portable Atari 8-bit emulator focused on accurate hardware emulation and portability across multiple operating systems. It supports a broad range of Atari computer models, storage devices, cartridge formats, and peripheral hardware while providing a machine language monitor suitable for software development and debugging.

The emulator is frequently used as a secondary verification platform alongside Altirra to ensure software compatibility across different emulator implementations.

**Development Features**

- High compatibility
- Portable implementation
- Built-in machine language monitor
- Cartridge emulation
- Disk drive emulation
- Tape emulation
- Save states
- Configurable hardware
- Command-line operation

**Supported File Formats**

- .ATR
- .ATX
- .CAR
- .CAS
- .ROM
- .XEX

**Debugging Features**

- Machine language monitor
- Memory inspection
- CPU register inspection
- Disassembler

**Integration**

- Assemblers
  - MADS
  - ATasm
- Cross-Compilers & High-Level Languages
  - cc65
  - FastBasic
  - Mad Pascal

**Primary Purpose**  
Cross-platform Atari 8-bit emulator for software development and compatibility testing.

---

<a id="atari800-header"></a>

## Atari800

**Official URL**
https://atari800.github.io/

**Source Code**
https://github.com/atari800/atari800

**Host Platforms**

- Windows
- Linux
- macOS
- Android

**Verified Target Systems**

- Atari 400
- Atari 800
- Atari 1200XL
- Atari 600XL
- Atari 800XL
- Atari 65XE
- Atari 130XE
- Atari XE Game System

**Overview**  
Atari800 is the longest continuously maintained open-source emulator for the Atari 8-bit family. It provides accurate emulation of Atari home computers and the Atari 5200 console while remaining highly portable across numerous operating systems. It is widely used for software development, automated testing, preservation projects, and everyday emulation. :contentReference[oaicite:2]{index=2}

**Development Features**

- Portable emulator
- SDL2 support
- Command-line operation
- Built-in machine language monitor
- Cartridge emulation
- Disk drive emulation
- Cassette support
- Save states
- Multiple hardware configurations
- Joystick and peripheral emulation

**Supported File Formats**

- .ATR
- .ATX
- .CAR
- .CAS
- .COM
- .ROM
- .SAP
- .XEX

**Debugging Features**

- Machine language monitor
- CPU register inspection
- Memory viewer
- Disassembler

**Integration**

- Integrated Development Environments
  - WUDSN IDE
- Assemblers
  - ATasm
  - MADS
- Cross-Compilers & High-Level Languages
  - cc65
  - FastBasic
  - Mad Pascal

**Primary Purpose**  
Portable open-source Atari 8-bit emulator for software development, testing, and preservation.

[Back to index](index.md)