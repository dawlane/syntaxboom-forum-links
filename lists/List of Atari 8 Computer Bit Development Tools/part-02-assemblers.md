# List of Atari 8 Computer Bit Development Tools - Assemblers

This is is going to be the start of a list of useful links to various tools for programming Atari 8 Bit home computers. If anyone adds some gems, then they will be added to this post, so people don't have to go through every post.

**NOTE:** Many of these sites linked here, have not been fully checked or validated for what contents they offer, and possibly in the future they may also be broken. Anyone using the links should remain vigilant to protect themselves from malicious software and sites through the use of internet security software and good judgement by not falling prey to sites that require the specific entry of personal information. The accuracy of the descriptions may also not be correct, and should be in many cases considered a work-in-progress.
If they don't appear to be what is advertised, or look suspicious.
Then PM an administrator so they can be removed, or updated with the correct information.  
**So use these links and any associated software from these sites at your own risk!**  

## Table of Contents

- [64tass](#64tass-header)
- [ACME](#acme-header)
- [ATasm](#atasm-header)
- [DASM](#dasm-header)
- [Kick Assembler](#kick-assembler-header)
- [MADS](#mads-header)
- [XASM](#xasm-header)

---

<a id="64tass-header"></a>

## 64tass

**Official URL**
https://sourceforge.net/projects/tass64/

**Source Code**
https://github.com/irmen/64tass

**Host Platforms**

- Windows
- Linux
- macOS

**Verified Target Systems**

- Atari 8-bit Family

**Overview**  
64tass is a mature, cross-platform macro assembler supporting the MOS 6502, 65C02, 65816, and related processors. Although originally developed within the Commodore community, it is a fully capable multi-platform assembler suitable for Atari 8-bit software development. Its powerful macro language, expression evaluator, relocatable code support, and extensive directive set make it well suited to modern cross-development workflows ranging from small utilities to large multi-module applications.

**Development Features**

- Multi-pass assembler
- Powerful macro language
- Structured conditional assembly
- Local and anonymous labels
- Relocatable object generation
- Repeat and loop directives
- Binary inclusion
- Comprehensive expression evaluator
- Listing generation
- Symbol export

**Supported File Formats**

- .ASM
- .BIN
- .INC
- .LST
- .OBJ
- .XEX

**Integration**

- Integrated Development Environments
  - WUDSN IDE
- External Tools
  - Make
  - CMake
  - Custom build systems

**Primary Purpose**  
Multi-platform 6502 macro assembler suitable for Atari 8-bit cross-development.

---

<a id="acme-header"></a>

## ACME

**Official URL**
https://sourceforge.net/projects/acme-crossass/

**Source Code**
https://github.com/meonwax/acme

**Host Platforms**

- Windows
- Linux
- macOS

**Verified Target Systems**

- Atari 8-bit Family

**Overview**  
ACME is a portable cross-assembler supporting numerous 6502-based systems, including the Atari 8-bit family. It provides a flexible macro language, efficient command-line workflow, and a rich set of directives that make it suitable for both hobbyist and professional cross-development projects. ACME integrates easily into automated build environments and modern development workflows.

**Development Features**

- Multi-pass assembly
- Macro support
- Conditional assembly
- Local labels
- Binary inclusion
- Symbol export
- Include files
- Listing generation
- Cross-platform command-line operation

**Supported File Formats**

- .ASM
- .BIN
- .INC
- .LST
- .XEX

**Integration**

- Integrated Development Environments
  - WUDSN IDE
- External Tools
  - Make
  - CMake
  - Custom build systems

**Primary Purpose**  
General-purpose multi-platform 6502 cross-assembler supporting Atari 8-bit software development.

---

<a id="atasm-header"></a>

## ATasm

**Official URL**
https://github.com/robmcmullen/atasm

**Host Platforms**

- Windows
- Linux
- macOS

**Verified Target Systems**

- Atari 8-bit Family

**Overview**  
ATasm is an open-source cross-assembler developed specifically for Atari 8-bit software development. It is highly compatible with Atari MAC/65 source code, making it an excellent choice for both maintaining legacy projects and creating new software. Its straightforward command-line interface and compatibility with modern editors and build systems have made it one of the most widely used Atari-specific assemblers.

**Development Features**

- MAC/65-compatible syntax
- Multi-pass assembly
- Macro support
- Conditional assembly
- Local labels
- Include files
- Listing generation
- Symbol export
- Native Atari executable generation

**Supported File Formats**

- .ASM
- .LST
- .MAC
- .XEX

**Integration**

- Integrated Development Environments
  - ATasm Altirra Bridge
- Emulators
  - Altirra
  - Atari800

**Primary Purpose**  
Atari-specific cross-assembler with strong compatibility with the MAC/65 assembler.

---

<a id="dasm-header"></a>

## DASM

**Official URL**
https://dasm-assembler.github.io/

**Source Code**
https://github.com/dasm-assembler/dasm

**Host Platforms**

- Windows
- Linux
- macOS

**Verified Target Systems**

- Atari 8-bit Family

**Overview**  
DASM is a long-established macro assembler supporting numerous 6502-based computer and console platforms. Its portability, mature macro language, and scriptable command-line interface make it suitable for Atari 8-bit cross-development projects. DASM is particularly popular in projects requiring automated build pipelines and cross-platform compatibility.

**Development Features**

- Multi-pass assembly
- Macro language
- Conditional assembly
- Local labels
- Include files
- Binary inclusion
- Listing generation
- Symbol generation
- Cross-platform command-line interface

**Supported File Formats**

- .ASM
- .BIN
- .INC
- .LST
- .XEX

**Integration**

- External Tools
  - Make
  - CMake
  - Custom build systems

**Primary Purpose**  
Multi-platform macro assembler supporting Atari 8-bit software development.

---

<a id="kick-assembler-header"></a>

## Kick Assembler

**Official URL**
http://theweb.dk/KickAssembler/

**Host Platforms**

- Windows
- Linux
- macOS

**Verified Target Systems**

- Atari 8-bit Family

**Overview**  
Kick Assembler is a modern Java-based macro assembler featuring an advanced scripting language, sophisticated expression handling, and extensive compile-time programming capabilities. Although widely associated with Commodore development, it is capable of generating software for Atari 8-bit systems and is suitable for developers requiring highly automated build processes and advanced code generation techniques.

**Development Features**

- Java-based cross-platform operation
- Advanced scripting language
- Compile-time functions
- Powerful macro language
- Conditional assembly
- Binary inclusion
- Namespace support
- Symbol export
- Listing generation

**Supported File Formats**

- .ASM
- .BIN
- .INC
- .LST
- .XEX

**Integration**

- External Tools
  - Make
  - Gradle
  - Custom build systems

**Primary Purpose**  
Advanced multi-platform macro assembler with an integrated scripting language suitable for Atari 8-bit development.

---

<a id="mads-header"></a>

## MADS

**Official URL**
https://mads.atari8.info/

**Host Platforms**

- Windows
- Linux
- macOS

**Verified Target Systems**

- Atari 8-bit Family

**Overview**  
MADS is one of the most feature-rich and widely used assemblers for Atari 8-bit software development. Designed specifically for the Atari platform, it offers structured assembly language constructs, an advanced macro language, extensive directive support, and facilities for large multi-file projects. MADS has become a standard tool within the Atari development community and integrates with many modern Atari development workflows.

**Development Features**

- Advanced macro language
- Structured programming directives
- Local labels
- Conditional assembly
- Repeat blocks
- Multi-file project support
- Include files
- Listing generation
- Symbol export
- Extensive directive library

**Supported File Formats**

- .ASM
- .INC
- .LST
- .XEX

**Integration**

- Integrated Development Environments
  - WUDSN IDE
  - ATasm Altirra Bridge
- Emulators
  - Altirra
  - Atari800

**Primary Purpose**  
Feature-rich Atari 8-bit cross-assembler for modern assembly language development.

---

<a id="xasm-header"></a>

## XASM

**Official URL**
https://github.com/pfusik/xasm

**Host Platforms**

- Windows
- Linux
- macOS

**Verified Target Systems**

- Atari 8-bit Family

**Overview**  
XASM is a lightweight, portable cross-assembler supporting Atari 8-bit software development. It provides a simple command-line interface, macro support, and integration with modern automated build systems. Its minimal design makes it well suited for developers preferring streamlined cross-development workflows.

**Development Features**

- Cross-platform command-line operation
- Macro support
- Conditional assembly
- Include files
- Symbol generation
- Listing generation
- Lightweight design

**Supported File Formats**

- .ASM
- .LST
- .XEX

**Integration**

- Integrated Development Environments
  - WUDSN IDE
- External Tools
  - Make
  - CMake
  - Custom build systems

**Primary Purpose**  
Lightweight cross-assembler supporting Atari 8-bit software development.

[Back to index](index.md)
