# List of Commodore 8 Bit Development Tools - Cross-Compilers & High-Level Languages

This is is going to be the start of a list of useful links to various tools for programming Commodore 8 Bit home computers. If anyone adds some gems, then they will be added to this post, so people don't have to go through every post.

**NOTE:** Many of these sites linked here, have not been fully checked or validated for what contents they offer, and possibly in the future they may also be broken. Anyone using the links should remain vigilant to protect themselves from malicious software and sites through the use of internet security software and good judgement by not falling prey to sites that require the specific entry of personal information. The accuracy of the descriptions may also not be correct, and should be in many cases considered a work-in-progress.
If they don't appear to be what is advertised, or look suspicious.
Then PM an administrator so they can be removed, or updated with the correct information.  
**So use these links and any associated software from these sites at your own risk!**  

## Table of contents

* [cc65](#cc65-header)
* [KickC](#kickc-header)
* [Millfork](#millfork-header)
* [Oscar64](#oscar64-header)
* [Prog8](#prog8-header)
* [TRSE (Turbo Rascal Syntax Error)](#trse-header)
* [ugBASIC](#ugbasic-header)
* [XC=BASIC 3](#xcbasic-3-header)

---

<a id="cc65-header"></a>

## cc65

**Official URL**
https://cc65.github.io/

**Source Code**
https://github.com/cc65/cc65

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
* CBM-II

**Overview**  
cc65 is a complete cross-development suite for 6502-based systems. It provides a full C compiler, assembler, linker, and runtime library system designed for producing efficient machine code for Commodore and related 8-bit systems. It is one of the most mature and widely used toolchains for C development on the Commodore platform and is frequently used in production-level homebrew games and utilities.

**Development Features**

* ANSI C compiler
* Integrated macro assembler
* Linker and librarian tools
* Runtime libraries for C64 hardware
* Large ecosystem of examples
* Optimised 6502 code generation

**Integration**

* VICE emulator
* Custom build systems
* IDE wrappers (VS64, WUDSN)

**Primary Purpose**  
C-based Commodore 8-bit development

---

<a id="kickc-header"></a>

## KickC

**Official URL**
https://gitlab.com/camelot/kickc

**Host Platforms**

* Windows
* Linux
* macOS

**Verified Commodore Targets**

* C64
* C128
* VIC-20
* Plus/4
* C16
* MEGA65

**Overview**  
KickC is an optimising compiler that translates a subset of the C language into highly efficient 6502 assembly code. It is designed specifically for performance-critical Commodore 64 software such as games and demos. Unlike general-purpose C compilers, KickC is heavily tuned for predictable memory layouts and tight CPU constraints of 8-bit machines.

**Development Features**

* Optimising C-to-assembly pipeline
* Inline assembly support
* Tight memory control
* Kick Assembler integration
* Fast build iteration cycles

**Integration**

* Kick Assembler
* VICE emulator
* Relaunch64

**Primary Purpose**  
High-performance C development for Commodore systems

---

<a id="millfork-header"></a>

## Millfork

**Official URL**
https://github.com/KarolS/millfork

**Host Platforms**

* Windows
* Linux
* macOS

**Verified Commodore Targets**

* C64
* C128
* PET
* Plus/4
* C16
* CBM-II

**Overview**  
Millfork is a high-level language designed specifically for 8-bit computers. It blends structured programming concepts with low-level control, allowing developers to write portable code that compiles into highly optimised 6502 machine code. It is particularly focused on game development and embedded-style programming where performance and determinism are essential.

**Development Features**

* Structured language design
* Strong static typing
* Inline assembly support
* Optimising compiler backend
* Cross-platform retro targeting

**Integration**

* 64tass / ACME (via assembly output)
* VICE emulator
* External build pipelines

**Primary Purpose**  
Structured high-level programming for 8-bit systems

---

<a id="oscar64-header"></a>

## Oscar64

**Official URL**
https://github.com/drmortalwombat/oscar64

**Host Platforms**

* Windows
* Linux
* macOS

**Verified Commodore Targets**

* C64
* C128
* MEGA65

**Overview**  
Oscar64 is a modern optimising C compiler specifically designed for Commodore 64-class hardware. It produces highly efficient 6502 assembly output and includes a modern toolchain pipeline with debugging output and intermediate representations. It is particularly suited for larger structured projects such as games, BBS software, and system utilities.

**Development Features**

* Optimising compiler backend
* Modern C support
* Assembly output generation
* Debug symbols and maps
* Efficient register allocation strategies

**Integration**

* VICE emulator
* External assemblers
* Modern IDE workflows

**Primary Purpose**  
High-performance C development for Commodore systems

---

<a id="prog8-header"></a>

## Prog8

**Official URL**
https://github.com/irmen/prog8

**Host Platforms**

* Windows
* Linux
* macOS

**Verified Commodore Targets**

* C64
* C128
* PET

**Overview**  
Prog8 is a modern compiled language designed for 6502-based systems. It provides a balance between structured high-level programming and low-level control, enabling developers to write portable and efficient code across multiple 8-bit platforms. It includes its own compiler pipeline, runtime library system, and configurable target backends.

**Development Features**

* Multi-target compiler backend
* Structured programming language
* Memory layout control
* Built-in standard libraries
* Configurable system targets

**Integration**

* VICE emulator
* Assembly toolchains
* Custom build systems

**Primary Purpose**  
Portable high-level 6502 development

---

<a id="trse-header"></a>

## TRSE (Turbo Rascal Syntax Error)

**Official URL**
https://lemonspawn.com/turbo-rascal-syntax-error/

**Source Code**
https://github.com/leuat/TRSE

**Host Platforms**

* Windows
* Linux
* macOS

**Verified Commodore Targets**

* C64
* C128
* VIC-20
* Plus/4
* C16
* PET
* MEGA65

**Overview**  
TRSE is a complete integrated development environment and compiler for a Pascal-inspired language targeting retro computers. It combines an editor, compiler, asset pipeline, and runtime tooling in a single environment. It is especially popular for demo and game development due to its built-in graphics tooling and tight integration with Commodore hardware constraints.

**Development Features**

* Pascal-like structured language
* Integrated IDE and compiler
* Graphics and sprite tooling
* Inline assembly support
* Multi-target build system

**Integration**

* VICE emulator
* Internal toolchain system
* External asset pipelines

**Primary Purpose**  
All-in-one structured retro development environment

---

<a id="ugbasic-header"></a>

## ugBASIC

**Official URL**
https://ugbasic.iwashere.eu/

**Host Platforms**

* Windows
* Linux
* macOS

**Verified Commodore Targets**

* C64
* C128
* VIC-20
* Plus/4
* C16
* PET
* CBM-II
* MEGA65

**Overview**  
ugBASIC is a modern cross-compiled BASIC dialect designed for multiple retro systems. It translates high-level BASIC-style code into efficient machine code for 8-bit systems. It is designed for accessibility while still allowing advanced users to access hardware-level features when required.

**Development Features**

* Cross-platform BASIC dialect
* Multi-system compilation
* Graphics and sound libraries
* Hardware abstraction layer
* Structured programming support

**Integration**

* VICE emulator
* External build pipelines
* Asset conversion tools

**Primary Purpose**  
Portable BASIC development across retro systems

---

<a id="xcbasic-3-header"></a>

## XC=BASIC 3

**Official URL**
https://xc-basic.net/

**Source Code**
https://github.com/neilsf/xc-basic3

**Host Platforms**

* Windows
* Linux
* macOS

**Verified Commodore Targets**

* C64
* C128
* VIC-20
* Plus/4
* C16
* PET
* MEGA65

**Overview**  
XC=BASIC 3 is a modern compiler that converts BASIC-style source code into optimised native machine code for Commodore systems. It is designed to retain BASIC’s simplicity while producing performance comparable to hand-written assembly in many cases. It is commonly used for games, utilities, and educational software.

**Development Features**

* BASIC-to-native compilation
* Optimised machine code output
* Structured BASIC extensions
* Hardware access functions
* Cross-platform tooling

**Integration**

* VICE emulator
* Asset pipelines
* External IDEs

**Primary Purpose**  
High-performance BASIC development for Commodore systems

[Back to index](index.md)
