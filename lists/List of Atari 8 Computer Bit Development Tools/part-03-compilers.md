# List of Atari 8 Computer Bit Development Tools - Cross-Compilers & High-Level Languages

This is is going to be the start of a list of useful links to various tools for programming Atari 8 Bit home computers. If anyone adds some gems, then they will be added to this post, so people don't have to go through every post.

**NOTE:** Many of these sites linked here, have not been fully checked or validated for what contents they offer, and possibly in the future they may also be broken. Anyone using the links should remain vigilant to protect themselves from malicious software and sites through the use of internet security software and good judgement by not falling prey to sites that require the specific entry of personal information. The accuracy of the descriptions may also not be correct, and should be in many cases considered a work-in-progress.
If they don't appear to be what is advertised, or look suspicious.
Then PM an administrator so they can be removed, or updated with the correct information.  
**So use these links and any associated software from these sites at your own risk!**  

## Table of Contents

* [cc65](#cc65-header)
* [FastBasic](#fastbasic-header)
* [Mad Pascal](#mad-pascal-header)
* [vbcc](#vbcc-header)

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

**Verified Target Systems**

* Atari 8-bit Family

**Overview**
cc65 is a complete cross-development toolchain for 6502-based systems, including the Atari 8-bit family. It provides a C compiler, macro assembler, linker, librarian, runtime libraries, and supporting utilities within a single integrated toolchain. The Atari target includes startup code, linker configurations, runtime libraries, and platform-specific APIs for developing applications, games, and utilities.

The modular architecture allows projects to combine C and assembly language, making cc65 suitable for both small utilities and large multi-module software projects. It integrates well with modern editors, IDEs, automated build systems, and emulators.

**Development Features**

* ANSI C compiler
* Complete 6502 development toolchain
* Integrated macro assembler
* Linker and librarian
* Runtime libraries
* Atari-specific startup code
* Configurable linker scripts
* Mixed C and assembly development
* Multi-module project support
* Cross-platform command-line tools

**Supported File Formats**

* .ASM
* .C
* .CFG
* .H
* .INC
* .LIB
* .O65
* .OBJ
* .S
* .XEX

**Integration**

* Assemblers

  * ca65 (toolchain component)
* Integrated Development Environments

  * WUDSN IDE
* Emulators

  * Altirra
  * Atari800
* External Tools

  * Make
  * CMake

**Primary Purpose**
Complete C cross-development toolchain for the Atari 8-bit family.

---

<a id="fastbasic-header"></a>

## FastBasic

**Official URL**
https://github.com/dmsc/fastbasic

**Host Platforms**

* Windows
* Linux
* macOS

**Verified Target Systems**

* Atari 8-bit Family

**Overview**
FastBasic is a modern BASIC compiler and development environment designed specifically for the Atari 8-bit family. It combines a streamlined BASIC language with a highly optimising compiler to produce compact, high-performance native executables. FastBasic is intended as a practical alternative to Atari BASIC for modern cross-development and is particularly well suited to games, utilities, and educational software.

The project includes its own compiler, runtime library, examples, documentation, and command-line development tools, making it a complete standalone development environment.

**Development Features**

* Modern BASIC language
* Native code compiler
* Optimised runtime library
* Structured programming constructs
* Integer and floating-point support
* Command-line compiler
* Extensive examples
* Comprehensive documentation
* Cross-platform development

**Supported File Formats**

* .BAS
* .FB
* .INC
* .XEX

**Integration**

* Integrated Development Environments

  * WUDSN IDE
* Emulators

  * Altirra
  * Atari800
* External Tools

  * Make

**Primary Purpose**
Modern BASIC compiler and development environment for the Atari 8-bit family.

---

<a id="mad-pascal-header"></a>

## Mad Pascal

**Official URL**
https://mads.atari8.info/madpascal/

**Host Platforms**

* Windows
* Linux
* macOS

**Verified Target Systems**

* Atari 8-bit Family

**Overview**
Mad Pascal is a Pascal compiler developed specifically for Atari 8-bit cross-development. It provides a modern Pascal language implementation together with an extensive runtime library, graphics and sound support, and integration with the MADS assembler. The compiler is widely used for creating games, demos, and utilities, offering an approachable language while maintaining excellent performance and close integration with Atari hardware.

**Development Features**

* Pascal compiler
* Extensive runtime library
* Graphics and sound units
* Structured programming
* Strong type checking
* Multi-unit projects
* Integration with MADS
* Command-line compiler
* Example projects

**Supported File Formats**

* .ASM
* .INC
* .PAS
* .PP
* .XEX

**Integration**

* Assemblers

  * MADS
* Integrated Development Environments

  * WUDSN IDE
* Emulators

  * Altirra
  * Atari800

**Primary Purpose**
Pascal cross-compiler and runtime library for Atari 8-bit software development.

---

<a id="vbcc-header"></a>

## vbcc

**Official URL**
http://www.compilers.de/vbcc.html

**Host Platforms**

* Windows
* Linux
* macOS

**Verified Target Systems**

* Atari 8-bit Family

**Overview**
vbcc is a portable ANSI C compiler supporting numerous processor architectures and retro computing platforms. Through its Atari 8-bit backend and supporting runtime environment, it enables the development of efficient native applications while offering a standards-oriented alternative to other C toolchains. Its emphasis on optimisation and portability makes it suitable for advanced cross-development projects.

**Development Features**

* ANSI C compiler
* Optimising code generator
* Multiple CPU backends
* Modular architecture
* Command-line toolchain
* Cross-platform operation
* Library support
* Configurable build workflow

**Supported File Formats**

* .ASM
* .C
* .H
* .LIB
* .OBJ
* .XEX

**Integration**

* External Tools

  * Make
  * CMake
* Emulators

  * Altirra
  * Atari800

**Primary Purpose**
Portable ANSI C cross-compiler supporting Atari 8-bit software development.

[Back to index](index.md)