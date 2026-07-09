# List of Commodore 8 Bit Development Tools - Assemblers

This is is going to be the start of a list of useful links to various game libraries and game render engines. If anyone adds some gems, then they will be added to this post, so people don't have to go through every post.

**NOTE:** Many of these sites linked here, have not been fully checked or validated for what contents they offer, and possibly in the future they may also be broken. Anyone using the links should remain vigilant to protect themselves from malicious software and sites through the use of internet security software and good judgement by not falling prey to sites that require the specific entry of personal information. The accuracy of the descriptions may also not be correct, and should be in many cases considered a work-in-progress.
If they don't appear to be what is advertised, or look suspicious.
Then PM an administrator so they can be removed, or updated with the correct information.  
**So use these links and any associated software from these sites at your own risk!**  

## Table of contents

* [64tass](#64tass-header)
* [ACME Cross-Assembler](#acme-cross-assembler-header)
* [Asm6502](#asm6502-header)
* [Kick Assembler](#kick-assembler-header)
* [Ophis](#Ophis-header)
* [Retro Assembler](#retro-assembler-header)
* [Turbo Macro Pro X (TMPx)](#-tmpx-header)
* [WLA DX](#wls-dx-header)
* [XA (xa65)](#xa-header)

---

<a id="64tass-header"></a>

## 64tass

**Official URL**
https://sourceforge.net/projects/tass64/

**Category**
Assembler

**Host Platforms**

* Windows
* Linux
* macOS

**Verified Commodore Targets**

* C64
* C128
* VIC-20
* PET
* Plus/4
* C16

**Overview**  
64tass is a high-performance cross-assembler for the 6502 family of processors widely used in Commodore development. It is designed for modern cross-development workflows and is particularly valued for its powerful macro system, flexible expression evaluation, and ability to generate highly structured assembly projects. It is often used in both demo and game development due to its balance between performance and readability.

**Development Features**

* Advanced macro system
* Expression evaluation engine
* Structured assembly support
* Multiple output formats
* Symbol management
* Modular source organisation

**Supported File Formats**

* PRG
* Binary output
* Object-style builds

**Integration**

* Relaunch64
* VICE
* External build systems

**Primary Purpose**
High-performance 6502 cross-assembly

---

<a id="acme-cross-assembler-header"></a>

## ACME Cross-Assembler

**Official URL**
https://sourceforge.net/projects/acme-crossass/

**Source Code**
https://sourceforge.net/p/acme-crossass/code-0/HEAD/tree/

**Category**
Assembler

**Host Platforms**

* Windows
* Linux
* macOS

**Verified Commodore Targets**

* C64
* C128
* VIC-20
* PET
* Plus/4
* C16

**Overview**  
ACME is a mature and widely adopted cross-assembler for 6502-family systems. It has been used extensively in Commodore demoscene and game development for decades. ACME focuses on simplicity and reliability while still offering powerful macro and conditional assembly features, making it suitable for both small projects and large structured codebases.

**Development Features**

* Macro support
* Conditional assembly
* Label management
* Modular source structure
* Cross-platform CLI workflow

**Supported File Formats**

* PRG
* Binary output

**Integration**

* VICE emulator
* IDEs such as VS64 and WUDSN

**Primary Purpose**
General-purpose 6502 assembly development

---

<a id="asm6502-header"></a>

## Asm6502

**Official URL**
https://github.com/boeckmann/asm6502

**Category**
Assembler

**Host Platforms**

* Windows
* Linux
* macOS

**Verified Commodore Targets**

* C64
* C128
* VIC-20
* PET

**Overview**  
Asm6502 is a modern lightweight assembler implementation for 6502-based systems. It is designed with simplicity and portability in mind, making it suitable for integration into modern build pipelines and custom tooling systems. While not as feature-heavy as larger assemblers, it provides a clean and straightforward assembly workflow.

**Development Features**

* Lightweight CLI tool
* Cross-platform execution
* Symbol support
* Basic macro functionality
* Easy toolchain integration

**Supported File Formats**

* PRG
* Binary output

**Integration**

* Custom build systems
* IDE wrappers
* Emulator pipelines

**Primary Purpose**
Lightweight 6502 assembly compilation

---

<a id="lick-assembler-header"></a>

## Kick Assembler

**Official URL**
https://theweb.dk/KickAssembler/

**Category**
Assembler

**Host Platforms**

* Windows
* Linux
* macOS

**Verified Commodore Targets**

* C64
* C128
* VIC-20

**Overview**  
Kick Assembler is one of the most widely used modern assemblers for Commodore development. Built on Java, it combines traditional assembly syntax with a powerful macro and scripting language that enables highly structured and reusable code. It is especially popular in game and demo development due to its integration with asset pipelines and its ability to support complex build logic inside assembly projects.

**Development Features**

* Java-based execution environment
* Advanced macro system
* Built-in scripting language
* Structured assembly programming
* Asset pipeline integration
* Conditional compilation
* Extensive standard library features

**Supported File Formats**

* PRG
* Assembly source
* Binary output

**Integration**

* VICE emulator
* Relaunch64
* VS64
* External Java toolchains

**Primary Purpose**
Feature-rich 6502 assembly development

---

<a id="ophis-header"></a>

## Ophis

**Official URL**
https://michaelcmartin.github.io/Ophis/

**Source Code**
https://github.com/michaelcmartin/Ophis

**Category**
Assembler

**Host Platforms**

* Windows
* Linux
* macOS

**Verified Commodore Targets**

* C64
* C128
* VIC-20
* PET

**Overview**  
Ophis is a minimalist cross-assembler for 6502-family processors designed with clarity and portability as its main goals. It prioritises simplicity of syntax and predictable behaviour, making it suitable for educational use, experimental development, and small-scale Commodore projects where full macro-heavy toolchains are unnecessary.

**Development Features**

* Minimal syntax design
* Portable implementation
* Clean assembly model
* Macro support (basic)
* Cross-platform CLI tool

**Supported File Formats**

* PRG
* Binary output

**Integration**

* VICE emulator
* Simple build pipelines

**Primary Purpose**
Simple and portable 6502 assembly

---

<a id="retro-assembler-header"></a>

## Retro Assembler

**Official URL**
https://enginedesigns.net/retroassembler

**Category**
Assembler

**Host Platforms**

* Windows
* Linux
* macOS

**Verified Commodore Targets**

* C64
* C128
* VIC-20
* PET
* Plus/4
* C16

**Overview**  
Retro Assembler is a modern multi-target assembly tool designed for retro computing development across multiple 8-bit platforms. It provides a contemporary development experience with modern diagnostics, structured project management, and support for multiple CPU architectures. It is particularly suited for developers targeting more than one retro platform simultaneously.

**Development Features**

* Multi-platform assembly support
* Modern diagnostic output
* Structured project system
* Macro support
* Cross-platform CLI tools
* Multi-CPU targeting

**Supported File Formats**

* PRG
* Binary output

**Integration**

* External IDEs
* Emulator pipelines

**Primary Purpose**
Multi-platform 6502 assembly development

---

<a id="tmpx-header"></a>

## Turbo Macro Pro X (TMPx)

**Official URL**
https://turbo.style64.org/

**Category**
Assembler

**Host Platforms**

* Windows
* Linux
* macOS

**Verified Commodore Targets**

* C64

**Overview**  
Turbo Macro Pro X is a modern cross-platform reimplementation of the classic Turbo Macro Pro assembler environment originally used directly on Commodore hardware. TMPx allows developers to use TMP-style workflows on modern systems, preserving compatibility with legacy development styles while enabling modern tooling integration.

**Development Features**

* TMP-compatible syntax
* Macro assembly system
* Cross-platform execution
* Legacy workflow support
* Modern toolchain integration

**Supported File Formats**

* PRG
* Assembly source

**Integration**

* VICE emulator
* Retro workflow pipelines

**Primary Purpose**
Legacy-compatible Commodore assembly workflow

---

<a id="wla-dx-header"></a>

## WLA DX

**Official URL**
https://github.com/vhelin/wla-dx

**Category**
Assembler

**Host Platforms**

* Windows
* Linux
* macOS

**Verified Commodore Targets**

* C64
* C128
* VIC-20
* PET
* Plus/4
* C16

**Overview**  
WLA DX is a multi-architecture assembler suite supporting several CPU families including the 6502 used in Commodore systems. It includes a powerful linker system, macro capabilities, and modular build support, making it suitable for large-scale projects and cross-platform retro development.

**Development Features**

* Multi-CPU assembler suite
* Integrated linker system
* Macro system
* Modular builds
* Cross-platform CLI
* Library support

**Supported File Formats**

* PRG
* Binary output
* Object files

**Integration**

* VICE emulator
* Multi-tool build systems

**Primary Purpose**
Multi-architecture assembly development

---

<a id="xa-header"></a>

## XA (xa65)

**Official URL**
https://github.com/fachat/xa65

**Category**
Assembler

**Host Platforms**

* Windows
* Linux
* macOS

**Verified Commodore Targets**

* C64
* C128
* VIC-20
* PET
* Plus/4
* C16

**Overview**  
XA is a long-established and widely used cross-assembler for 6502-family processors. It is known for its stability and portability and remains a reliable choice for Commodore development. XA focuses on providing a straightforward assembly workflow without excessive abstraction, making it suitable for both legacy and modern development pipelines.

**Development Features**

* Stable cross-assembler design
* Macro support
* Conditional assembly
* Cross-platform CLI
* Symbol handling

**Supported File Formats**

* PRG
* Binary output

**Integration**

* VICE emulator
* IDE integrations

**Primary Purpose**
Stable 6502 cross-assembly
