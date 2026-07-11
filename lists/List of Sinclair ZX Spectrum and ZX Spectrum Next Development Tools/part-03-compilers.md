# List of Sinclair ZX Spectrum and ZX Spectrum Next Development Tools

## Cross-Compilers & High-Level Languages

This is is going to be the start of a list of useful links to various tools for programming Sinclair ZX Spectrum and ZX Spectrum Next Development home computers. If anyone adds some gems, then they will be added to this post, so people don't have to go through every post.

**NOTE:** Many of these sites linked here, have not been fully checked or validated for what contents they offer, and possibly in the future they may also be broken. Anyone using the links should remain vigilant to protect themselves from malicious software and sites through the use of internet security software and good judgement by not falling prey to sites that require the specific entry of personal information. The accuracy of the descriptions may also not be correct, and should be in many cases considered a work-in-progress.
If they don't appear to be what is advertised, or look suspicious.
Then PM an administrator so they can be removed, or updated with the correct information.  
**So use these links and any associated software from these sites at your own risk!**  

## Table of Contents

- [Boriel BASIC](#boriel-basic-header)
- [SDCC](#sdcc-header)
- [Turbo Rascal Syntax Error (TRSE)](#turbo-rascal-syntax-error-trse-header)
- [ugBASIC](#ugbasic-header)
- [z88dk](#z88dk-header)

---

<a id="boriel-basic-header"></a>

## Boriel BASIC

**Official URL**
https://zxbasic.readthedocs.io/

**Source Code**
https://github.com/boriel-basic/zxbasic

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
Boriel BASIC is a modern compiled BASIC language designed specifically for Z80-based systems, with the Sinclair ZX Spectrum family being one of its primary targets. Unlike the original Sinclair BASIC interpreter, Boriel BASIC compiles source code into efficient native machine code, allowing developers to create significantly larger and faster applications while retaining the accessibility and readability associated with BASIC programming.

The compiler supports structured programming, procedures, functions, inline assembly language and numerous language extensions intended for modern retro-computing development. It has become one of the most widely adopted high-level languages for ZX Spectrum and ZX Spectrum Next projects, providing a productive alternative to pure assembly language development while still allowing low-level optimisation when required.

**Development Features**

- Native code compilation
- Structured BASIC language
- Functions and procedures
- Modular source organisation
- Inline Z80 assembly
- Optimisation support
- Command-line compilation
- ZX Spectrum Next support
- Integrated library system
- Cross-platform toolchain

**Supported File Formats**

- `.bas`
- `.bi`
- `.asm`
- `.tap`
- `.tzx`
- `.sna`

**Integration**

- **Assemblers**
  - Integrated assembler support
  - SjASMPlus workflows
- **Compilers**
  - Boriel BASIC compiler
- **Emulators**
  - Compatible with all major ZX Spectrum emulators
- **Frameworks & SDKs**
  - Boriel BASIC standard libraries
- **External tools**
  - Boriel Basic IDE

**Primary Purpose**  
A compiled BASIC language and cross-compiler for developing native ZX Spectrum and ZX Spectrum Next software.  

---

<a id="sdcc-header"></a>

## SDCC

**Official URL**
https://sdcc.sourceforge.net/

**Source Code**
https://sourceforge.net/p/sdcc/code/

**Host Platforms**

- Windows
- Linux
- macOS

**Verified ZX Spectrum or ZX Spectrum Next Targets**

- ZX Spectrum 48K
- ZX Spectrum 128K
- ZX Spectrum +2
- ZX Spectrum +2A/+2B
- ZX Spectrum +3
- ZX Spectrum Next

**Overview**  
SDCC (Small Device C Compiler) is an open-source ANSI C compiler targeting a variety of small processors, including the Z80 family used by Sinclair ZX Spectrum systems. Within the Spectrum development ecosystem, SDCC is most commonly encountered as the underlying C compiler used by z88dk, although it can also be used independently as part of custom toolchains.

The compiler provides modern C language support, code optimisation capabilities and extensive tooling suitable for professional software development practices. It enables developers to write portable C code while targeting constrained retro hardware environments.

**Development Features**

- ANSI C compiler
- Z80 backend
- Optimising code generation
- Linker integration
- Library support
- Debug information generation
- Command-line operation
- Cross-platform support
- Multi-target architecture support

**Supported File Formats**

- `.c`
- `.h`
- `.asm`
- `.rel`
- `.lib`
- `.ihx`
- `.bin`

**Integration**

- **Assemblers**
  - SjASMPlus
  - PASMO
- **Compilers**
  - SDCC compiler backend
- **Emulators**
  - Compatible with ZX Spectrum emulator workflows
- **Frameworks & SDKs**
  - z88dk
- **External tools**
  - Automated build systems

**Primary Purpose**  
A portable ANSI C compiler providing Z80 code generation for Sinclair ZX Spectrum development toolchains.  

---

<a id="turbo-rascal-syntax-error-trse-header"></a>

## Turbo Rascal Syntax Error (TRSE)

**Official URL**
https://lemonspawn.com/turbo-rascal-syntax-error-expected-but-begin/

**Source Code**
https://github.com/leuat/TRSE

**Host Platforms**

- Windows
- Linux
- macOS

**Verified ZX Spectrum or ZX Spectrum Next Targets**

- ZX Spectrum 48K
- ZX Spectrum 128K
- ZX Spectrum +2
- ZX Spectrum +2A/+2B
- ZX Spectrum +3
- ZX Spectrum Next

**Overview**  
Turbo Rascal Syntax Error (TRSE) is a cross-platform development environment and Pascal-inspired programming language for retro-computer development. It supports multiple classic systems, including the Sinclair ZX Spectrum family, through a unified language, asset pipeline and project workflow.

TRSE is designed to make retro game and application development more approachable while still generating efficient native code. It includes integrated project management, graphics conversion facilities, music support and platform-specific tooling, enabling developers to build complete ZX Spectrum software projects from a single environment.

**Development Features**

- Pascal-inspired language
- Native code generation
- Multi-platform retro targeting
- Project management
- Integrated editor
- Asset conversion tools
- Sprite handling
- Build automation
- ZX Spectrum Next support
- Integrated development workflow

**Supported File Formats**

- `.ras`
- `.asm`
- `.tap`
- `.tzx`
- `.bin`
- `.nex`

**Integration**

- **Assemblers**
  - SjASMPlus
- **Compilers**
  - Built-in TRSE compiler
- **Emulators**
  - Emulator launch integration
- **Frameworks & SDKs**
  - TRSE runtime libraries
- **External tools**
  - Asset conversion pipeline

**Primary Purpose**  
A high-level retro-development language and toolchain for creating ZX Spectrum and ZX Spectrum Next software.  

---

<a id="ugbasic-header"></a>

## ugBASIC

**Official URL**
https://ugbasic.iwashere.eu/

**Source Code**
https://github.com/spotlessmind1975/ugbasic

**Host Platforms**

- Windows
- Linux
- macOS

**Verified ZX Spectrum or ZX Spectrum Next Targets**

- ZX Spectrum 48K
- ZX Spectrum 128K
- ZX Spectrum +2
- ZX Spectrum +2A/+2B
- ZX Spectrum +3

**Overview**  
ugBASIC is a modern open-source BASIC compiler designed for a wide range of retro-computing platforms. It provides a unified programming language that allows developers to target multiple classic systems, including the Sinclair ZX Spectrum family, from a single codebase.

The language includes numerous extensions aimed at game and multimedia development, providing built-in facilities for graphics, sprites, sound and input handling. By abstracting many platform-specific details, ugBASIC enables rapid development while still generating native machine code suitable for resource-constrained hardware.

**Development Features**

- Compiled BASIC language
- Native machine code generation
- Structured programming
- Graphics commands
- Sound commands
- Input handling
- Multi-platform targeting
- Build automation
- Cross-platform operation
- Retro game development focus

**Supported File Formats**

- `.bas`
- `.asm`
- `.tap`
- `.tzx`
- `.bin`

**Integration**

- **Assemblers**
  - Internal assembler workflow
- **Compilers**
  - ugBASIC compiler
- **Emulators**
  - Compatible with ZX Spectrum emulators
- **Frameworks & SDKs**
  - ugBASIC runtime libraries
- **External tools**
  - Automated build workflows

**Primary Purpose**  
A cross-platform compiled BASIC language for creating native software on Sinclair ZX Spectrum systems and other retro computers.  

---

<a id="z88dk-header"></a>

## z88dk

**Official URL**
https://www.z88dk.org/

**Source Code**
https://github.com/z88dk/z88dk

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
z88dk is the most comprehensive and widely adopted C development kit for Z80-based systems. It provides a complete cross-development environment containing compilers, assemblers, linkers, libraries and utilities for numerous retro platforms, with particularly strong support for the Sinclair ZX Spectrum family.

The toolkit enables developers to create ZX Spectrum software primarily in C while retaining access to assembly language optimisation where required. Extensive platform libraries, mature tooling and active maintenance have made z88dk a cornerstone of modern Spectrum software development. It supports both classic Spectrum machines and the ZX Spectrum Next, making it suitable for projects ranging from simple utilities to large-scale commercial-quality games.

**Development Features**

- ANSI C development environment
- Multiple compiler backends
- Extensive runtime libraries
- Linker support
- Assembly language integration
- Optimisation support
- Build automation
- Platform abstraction libraries
- ZX Spectrum Next support
- Large project support

**Supported File Formats**

- `.c`
- `.h`
- `.asm`
- `.lib`
- `.rel`
- `.tap`
- `.tzx`
- `.sna`
- `.nex`

**Integration**

- **Assemblers**
  - SjASMPlus
  - PASMO
- **Compilers**
  - SDCC
  - SCCZ80
- **Emulators**
  - CSpect
  - Fuse
  - ZEsarUX
- **Frameworks & SDKs**
  - z88dk runtime libraries
- **External tools**
  - Makefiles
  - Continuous integration systems

**Primary Purpose**  
A complete C-based cross-development toolkit for building software across the Sinclair ZX Spectrum family and ZX Spectrum Next.

[Back to index](index.md)
