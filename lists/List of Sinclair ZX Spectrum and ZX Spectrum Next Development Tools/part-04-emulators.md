# List of Sinclair ZX Spectrum and ZX Spectrum Next Development Tools

## Emulators

This is is going to be the start of a list of useful links to various tools for programming Sinclair ZX Spectrum and ZX Spectrum Next Development home computers. If anyone adds some gems, then they will be added to this post, so people don't have to go through every post.

**NOTE:** Many of these sites linked here, have not been fully checked or validated for what contents they offer, and possibly in the future they may also be broken. Anyone using the links should remain vigilant to protect themselves from malicious software and sites through the use of internet security software and good judgement by not falling prey to sites that require the specific entry of personal information. The accuracy of the descriptions may also not be correct, and should be in many cases considered a work-in-progress.
If they don't appear to be what is advertised, or look suspicious.
Then PM an administrator so they can be removed, or updated with the correct information.  
**So use these links and any associated software from these sites at your own risk!**  

## Table of Contents

- [CSpect](#cspect-header)
- [EightyOne](#eightyone-header)
- [FBZX](#fbzx-header)
- [Fuse](#fuse-header)
- [Retro Virtual Machine](#retro-virtual-machine-header)
- [Speccy](#speccy-header)
- [Speculator](#speculator-header)
- [Xspeccy](#xspeccy-header)
- [ZEsarUX](#zesarux-header)
- [ZX Spectrum 4 .net](#zx-spectrum-4-net-header)
- [ZXSP](#zxsp-header)

---

<a id="cspect-header"></a>

## CSpect

**Official URL**
https://mdf200.itch.io/cspect

**Host Platforms**

- Windows

**Verified ZX Spectrum or ZX Spectrum Next Targets**

- ZX Spectrum Next

**Overview**  
CSpect is the reference development emulator for the ZX Spectrum Next and is widely used throughout the Next development community. It provides highly accurate emulation of ZX Spectrum Next hardware while exposing extensive debugging and development facilities that make it particularly suitable for software creation rather than simply software playback.

The emulator is closely aligned with the evolving ZX Spectrum Next platform and supports modern development workflows involving assembly language, C, Boriel BASIC and other toolchains. Direct integration with popular assemblers and IDEs has made CSpect one of the most important tools in the ZX Spectrum Next ecosystem.

**Development Features**

- ZX Spectrum Next emulation
- NEX file support
- Integrated debugging
- Symbol file support
- Breakpoint support
- Memory inspection
- Register inspection
- Source-level debugging integration
- Scriptable launch options
- Development-oriented workflow

**Supported File Formats**

- `.nex`
- `.tap`
- `.tzx`
- `.sna`
- `.z80`
- `.sym`

**Debugging Features**

- Breakpoints
- Memory viewer
- Register viewer
- Disassembly view
- Symbol-aware debugging
- Execution tracing

**Integration**

- **Assemblers**
  - SjASMPlus
- **Compilers**
  - z88dk
  - Boriel BASIC
- **Frameworks & SDKs**
  - FASE
  - Rage1
  - Mike Dailly's ZX Spectrum Next ASM Framework
- **External tools**
  - Klive IDE
  - Build automation systems

**Primary Purpose**  
A development-focused emulator providing ZX Spectrum Next emulation, testing and debugging facilities.  

---

<a id="eightyone-header"></a>

## EightyOne

**Official URL**
https://sourceforge.net/projects/eightyone-sinclair-emulator/

**Host Platforms**

- Windows

**Verified ZX Spectrum or ZX Spectrum Next Targets**

- ZX Spectrum 16K
- ZX Spectrum 48K
- ZX Spectrum 128K
- ZX Spectrum +2
- ZX Spectrum +2A/+2B
- ZX Spectrum +3

**Overview**  
EightyOne is a comprehensive Sinclair computer emulator supporting a wide range of Sinclair hardware platforms. It provides extensive machine coverage and numerous developer-oriented facilities that make it useful both for software preservation and software development.

The emulator is particularly valuable when testing software compatibility across multiple Sinclair machine variants, allowing developers to validate behaviour on different hardware configurations without requiring physical systems.

**Development Features**

- Multiple Sinclair machine support
- Snapshot management
- Tape support
- Disk support
- Hardware configuration options
- Development-oriented execution controls

**Supported File Formats**

- `.tap`
- `.tzx`
- `.sna`
- `.z80`
- `.dsk`

**Debugging Features**

- Breakpoints
- Memory inspection
- Register inspection
- Execution control
- Disassembly tools

**Integration**

- **Assemblers**
  - Compatible with external assembler workflows
- **Compilers**
  - Compatible with external compiler workflows
- **Emulators**
  - Standalone emulator
- **External tools**
  - Snapshot-based testing workflows

**Primary Purpose**  
A multi-system Sinclair emulator used for software testing, compatibility validation and development.  

---

<a id="fbzx-header"></a>

## FBZX

**Official URL**
https://www.rastersoft.com/programas/fbzx.html

**Host Platforms**

- Linux
- Windows

**Verified ZX Spectrum or ZX Spectrum Next Targets**

- ZX Spectrum 16K
- ZX Spectrum 48K
- ZX Spectrum 128K
- ZX Spectrum +2
- ZX Spectrum +2A/+2B
- ZX Spectrum +3

**Overview**  
FBZX is a cross-platform Sinclair ZX Spectrum emulator focused on usability, compatibility and performance. It supports a broad range of Spectrum models and storage formats, making it suitable for both software users and developers.

Its lightweight design and straightforward interface make it useful for quickly testing builds during development cycles while maintaining compatibility with common Spectrum software formats.

**Development Features**

- Multiple Spectrum model support
- Tape emulation
- Snapshot support
- Disk support
- Fast loading options
- Machine configuration support

**Supported File Formats**

- `.tap`
- `.tzx`
- `.sna`
- `.z80`
- `.dsk`

**Debugging Features**

- Basic machine state inspection
- Snapshot-based testing
- Execution control

**Integration**

- **Assemblers**
  - Compatible with generated outputs
- **Compilers**
  - Compatible with generated outputs
- **External tools**
  - Automated testing workflows

**Primary Purpose**  
A lightweight cross-platform ZX Spectrum emulator for software testing and execution.  

---

<a id="fuse-header"></a>

## Fuse

**Official URL**
https://fuse-emulator.sourceforge.net/

**Source Code**
https://sourceforge.net/p/fuse-emulator/code/

**Host Platforms**

- Windows
- Linux
- macOS

**Verified ZX Spectrum or ZX Spectrum Next Targets**

- ZX Spectrum 16K
- ZX Spectrum 48K
- ZX Spectrum 128K
- ZX Spectrum +2
- ZX Spectrum +2A/+2B
- ZX Spectrum +3

**Overview**  
Fuse (Free Unix Spectrum Emulator) is one of the most mature and widely used ZX Spectrum emulators available. It supports a broad range of Spectrum hardware models and provides accurate emulation combined with useful development and debugging facilities.

Its availability across major operating systems and strong reputation for compatibility have made it a common testing platform for developers creating software intended to run across the classic Sinclair ZX Spectrum family.

**Development Features**

- Cross-platform support
- Multiple Spectrum model emulation
- Tape and disk emulation
- Snapshot support
- Hardware configuration support
- Development-friendly command-line options

**Supported File Formats**

- `.tap`
- `.tzx`
- `.sna`
- `.z80`
- `.dsk`

**Debugging Features**

- Monitor interface
- Memory inspection
- Register inspection
- Breakpoints
- Execution control

**Integration**

- **Assemblers**
  - SjASMPlus
  - PASMO
- **Compilers**
  - z88dk
  - Boriel BASIC
- **External tools**
  - Automated build and test workflows

**Primary Purpose**  
A highly compatible cross-platform emulator for testing and debugging classic ZX Spectrum software.  

---

<a id="retro-virtual-machine-header"></a>

## Retro Virtual Machine

**Official URL**
https://www.retrovirtualmachine.org/

**Host Platforms**

- Windows
- macOS

**Verified ZX Spectrum or ZX Spectrum Next Targets**

- ZX Spectrum 16K
- ZX Spectrum 48K
- ZX Spectrum 128K
- ZX Spectrum +2
- ZX Spectrum +2A/+2B
- ZX Spectrum +3

**Overview**  
Retro Virtual Machine is a modern emulator platform supporting several classic computer systems, including the Sinclair ZX Spectrum family. It places strong emphasis on user experience, machine management and presentation while still providing features useful for software development and testing.

Its machine management facilities and polished interface make it attractive for developers who frequently switch between multiple machine configurations and testing environments.

**Development Features**

- Multi-machine management
- Snapshot support
- Tape support
- Disk support
- Configurable machine profiles
- Modern user interface

**Supported File Formats**

- `.tap`
- `.tzx`
- `.sna`
- `.z80`
- `.dsk`

**Debugging Features**

- Machine state inspection
- Snapshot testing
- Execution control

**Integration**

- **Assemblers**
  - Compatible with generated binaries
- **Compilers**
  - Compatible with generated binaries
- **External tools**
  - Testing workflows

**Primary Purpose**  
A modern emulator environment for running and testing ZX Spectrum software on contemporary systems.  

---

<a id="speccy-header"></a>

## Speccy

**Official URL**
https://fms.komkon.org/Speccy/

**Host Platforms**

- Windows
- Linux
- Android

**Verified ZX Spectrum or ZX Spectrum Next Targets**

- ZX Spectrum 16K
- ZX Spectrum 48K
- ZX Spectrum 128K
- ZX Spectrum +2
- ZX Spectrum +2A/+2B
- ZX Spectrum +3

**Overview**  
Speccy is a long-running ZX Spectrum emulator developed by Marat Fayzullin. It provides support for multiple Spectrum models and formats while maintaining portability across a variety of operating systems.

The emulator is often used as a secondary validation platform during development to ensure software compatibility across different emulator implementations.

**Development Features**

- Multiple machine support
- Tape support
- Snapshot support
- Portable implementation
- Cross-platform availability

**Supported File Formats**

- `.tap`
- `.tzx`
- `.sna`
- `.z80`

**Debugging Features**

- Memory inspection
- Register inspection
- Execution control

**Integration**

- **Assemblers**
  - Compatible with assembler outputs
- **Compilers**
  - Compatible with compiler outputs
- **External tools**
  - Testing workflows

**Primary Purpose**  
A portable ZX Spectrum emulator for software execution, testing and compatibility validation.  

---

<a id="speculator-header"></a>

## Speculator

**Official URL**
https://www.spectaculator.com/

**Host Platforms**

- Windows

**Verified ZX Spectrum or ZX Spectrum Next Targets**

- ZX Spectrum 16K
- ZX Spectrum 48K
- ZX Spectrum 128K
- ZX Spectrum +2
- ZX Spectrum +2A/+2B
- ZX Spectrum +3

**Overview**  
Speculator is a long-established commercial ZX Spectrum emulator for Microsoft Windows. It focuses on accurate emulation, usability and compatibility across the classic Sinclair ZX Spectrum family. Over many years it has been used by both enthusiasts and developers as a reliable platform for testing software without requiring original hardware.

The emulator supports a wide range of Spectrum models and media formats, making it useful for validating software behaviour across different machine configurations. Its mature implementation and extensive compatibility make it a valuable secondary testing platform alongside other popular emulators.

**Development Features**

- Multiple Spectrum model emulation
- Tape support
- Snapshot support
- Disk support
- Hardware configuration options
- High compatibility focus
- Save state management
- Configurable machine settings

**Supported File Formats**

- `.tap`
- `.tzx`
- `.sna`
- `.z80`
- `.dsk`

**Debugging Features**

- Snapshot-based testing
- Execution control
- Machine state inspection

**Integration**

- **Assemblers**
  - Compatible with generated assembler outputs
- **Compilers**
  - Compatible with generated compiler outputs
- **External tools**
  - Emulator-driven testing workflows

**Primary Purpose**  
A commercial ZX Spectrum emulator focused on compatibility testing and software execution across the classic Sinclair Spectrum family.  

---

<a id="xspeccy-header"></a>

## Xspeccy

**Official URL**
https://github.com/samstyle/Xpeccy

**Host Platforms**

- Windows
- Linux

**Verified ZX Spectrum or ZX Spectrum Next Targets**

- ZX Spectrum 16K
- ZX Spectrum 48K
- ZX Spectrum 128K
- ZX Spectrum +2
- ZX Spectrum +2A/+2B
- ZX Spectrum +3

**Overview**  
Xspeccy (Xpeccy) is an actively maintained emulator supporting numerous Z80-based systems, including the Sinclair ZX Spectrum family. It provides a flexible emulation environment and extensive machine configuration options, making it useful for developers testing software under varying hardware conditions.

The emulator supports a wide variety of storage formats and machine variants, enabling compatibility testing across different Spectrum generations. Its continuing development and open-source nature make it a useful platform for modern Spectrum development workflows.

**Development Features**

- Multi-system emulation
- Multiple Spectrum model support
- Tape support
- Disk support
- Snapshot support
- Hardware configuration controls
- Cross-platform operation
- Open-source development

**Supported File Formats**

- `.tap`
- `.tzx`
- `.sna`
- `.z80`
- `.dsk`

**Debugging Features**

- Memory inspection
- Register inspection
- Execution controls
- Machine state monitoring

**Integration**

- **Assemblers**
  - Compatible with assembler outputs
- **Compilers**
  - Compatible with compiler outputs
- **External tools**
  - Emulator-based testing workflows

**Primary Purpose**  
A flexible open-source emulator for testing and running software across multiple ZX Spectrum hardware variants.  

---

<a id="zesarux-header"></a>

## ZEsarUX

**Official URL**
https://github.com/chernandezba/zesarux

**Host Platforms**

- Windows
- Linux
- macOS

**Verified ZX Spectrum or ZX Spectrum Next Targets**

- ZX Spectrum 16K
- ZX Spectrum 48K
- ZX Spectrum 128K
- ZX Spectrum +2
- ZX Spectrum +2A/+2B
- ZX Spectrum +3
- ZX Spectrum Next

**Overview**  
ZEsarUX is one of the most feature-rich emulators available for the Sinclair ZX Spectrum ecosystem. It supports numerous Spectrum models and related systems while providing extensive debugging, inspection and development facilities. The emulator is particularly popular among advanced developers due to its powerful diagnostic capabilities.

Beyond traditional emulation, ZEsarUX includes facilities intended specifically for software creation, debugging and hardware investigation. Its broad platform support and deep feature set make it a valuable complement to development-focused tools such as CSpect.

**Development Features**

- Multi-system emulation
- ZX Spectrum Next support
- Tape support
- Disk support
- Snapshot support
- Advanced machine configuration
- Symbol loading
- Developer-oriented tooling

**Supported File Formats**

- `.tap`
- `.tzx`
- `.sna`
- `.z80`
- `.dsk`
- `.nex`

**Debugging Features**

- Breakpoints
- Memory viewer
- Register viewer
- Disassembler
- Execution tracing
- Symbol support
- Machine state inspection
- Remote debugging facilities

**Integration**

- **Assemblers**
  - SjASMPlus
- **Compilers**
  - z88dk
  - Boriel BASIC
- **Frameworks & SDKs**
  - Compatible with Spectrum and Next frameworks
- **External tools**
  - Automated debugging workflows

**Primary Purpose**  
A feature-rich emulator and debugging environment for ZX Spectrum and ZX Spectrum Next software development.  

---

<a id="zx-spectrum-4-net-header"></a>

## ZX Spectrum 4 .net

**Official URL**
https://www.zxspectrum4.net/emulator.php

**Host Platforms**

- Windows

**Verified ZX Spectrum or ZX Spectrum Next Targets**

- ZX Spectrum 16K
- ZX Spectrum 48K
- ZX Spectrum 128K
- ZX Spectrum +2
- ZX Spectrum +2A/+2B
- ZX Spectrum +3

**Overview**  
ZX Spectrum 4 .net is a Windows-based Sinclair ZX Spectrum emulator designed to provide broad compatibility with classic Spectrum software. It supports multiple machine models and common Spectrum media formats while offering a straightforward environment for software execution and testing.

The emulator is useful as an additional compatibility-testing platform when validating software across different emulator implementations and machine configurations.

**Development Features**

- Multiple Spectrum model support
- Tape support
- Snapshot support
- Hardware configuration controls
- Save state support
- Windows integration

**Supported File Formats**

- `.tap`
- `.tzx`
- `.sna`
- `.z80`

**Debugging Features**

- Snapshot testing
- Machine state inspection
- Execution control

**Integration**

- **Assemblers**
  - Compatible with assembler-generated software
- **Compilers**
  - Compatible with compiler-generated software
- **External tools**
  - Testing and validation workflows

**Primary Purpose**  
A Windows-based ZX Spectrum emulator for software execution, validation and compatibility testing.  

---

<a id="zxsp-header"></a>

## ZXSP

**Official URL**
https://k1.spdns.de/Develop/Projects/zxsp/

**Host Platforms**

- macOS
- Linux

**Verified ZX Spectrum or ZX Spectrum Next Targets**

- ZX Spectrum 16K
- ZX Spectrum 48K
- ZX Spectrum 128K
- ZX Spectrum +2
- ZX Spectrum +2A/+2B
- ZX Spectrum +3

**Overview**  
ZXSP is a Sinclair ZX Spectrum emulator developed by the author of several well-known Spectrum development utilities. It focuses on accurate emulation of classic Spectrum hardware while providing useful facilities for software testing and validation.

The emulator is particularly notable within macOS-based Spectrum development environments, where it serves as a native testing platform for developers creating software for classic Sinclair systems.

**Development Features**

- Classic Spectrum emulation
- Tape support
- Snapshot support
- Hardware configuration options
- Native desktop integration
- Multiple machine support

**Supported File Formats**

- `.tap`
- `.tzx`
- `.sna`
- `.z80`

**Debugging Features**

- Machine state inspection
- Execution control
- Snapshot-based testing

**Integration**

- **Assemblers**
  - Compatible with generated assembler outputs
- **Compilers**
  - Compatible with generated compiler outputs
- **External tools**
  - Testing workflows

**Primary Purpose**  
A native desktop emulator for running and validating classic Sinclair ZX Spectrum software.

[Back to index](index.md)
