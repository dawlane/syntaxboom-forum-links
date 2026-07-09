# List of Amstrad CPC 8 Bit Development Tools - Cross-Compilers & High-Level Languages

This is is going to be the start of a list of useful links to various tools for programming Amstrad CPC 8 Bit home computers. If anyone adds some gems, then they will be added to this post, so people don't have to go through every post.

**NOTE:** Many of these sites linked here, have not been fully checked or validated for what contents they offer, and possibly in the future they may also be broken. Anyone using the links should remain vigilant to protect themselves from malicious software and sites through the use of internet security software and good judgement by not falling prey to sites that require the specific entry of personal information. The accuracy of the descriptions may also not be correct, and should be in many cases considered a work-in-progress.
If they don't appear to be what is advertised, or look suspicious.
Then PM an administrator so they can be removed, or updated with the correct information.  
**So use these links and any associated software from these sites at your own risk!**  

## Table of contents

* [Turbo Rascal Syntax Error (TRSE)](#trse-header)
* [ugBasic](#ugbasic-header)
* [z88dk](#z88dk-header)

---

<a id="trse-header"></a>

# Turbo Rascal Syntax Error (TRSE)

**Official URL**
https://lemonspawn.com/turbo-rascal-syntax-error-expected-but-begin/

**Source Code**
https://github.com/leuat/TRSE

**Host Platforms**

* Windows
* Linux
* macOS

**Verified Amstrad CPC Targets**

* Amstrad CPC 464
* Amstrad CPC 664
* Amstrad CPC 6128

**Overview**  
Turbo Rascal Syntax Error (TRSE) is a modern cross-development environment and Pascal-inspired programming language designed specifically for retro-computer software development. It enables developers to write software in a structured high-level language while generating efficient machine code for a wide range of classic systems, including the Amstrad CPC.

TRSE combines an integrated editor, compiler, project management features, build automation, and platform-specific libraries into a unified development environment. The language incorporates modern programming concepts while remaining suitable for the memory and performance constraints of 8-bit systems.

For CPC development, TRSE provides an alternative to pure assembly language programming by allowing developers to create games, demos, utilities, and educational software with improved readability and maintainability. Performance-critical sections can still be optimised through low-level programming techniques when necessary.

The tool is particularly attractive for developers who prefer structured programming approaches but still require efficient native-code output suitable for original hardware.

**Development Features**  

* Pascal-inspired programming language
* Cross-compilation
* Integrated development environment
* Project management
* Build automation
* Syntax highlighting
* Source navigation
* Native code generation
* Multi-platform targeting
* Resource management
* Library support
* Structured programming constructs
* Modern code editor
* Debugging support
* Asset handling facilities

**Supported File Formats**  

* TRSE source files
* ASM
* BIN
* DSK
* CDT
* SNA
* Project files
* Resource files

**Integration**

* Internal code generation
* External assembler support where applicable
* WinAPE
* Arnold
* ACE-DL
* Retro Virtual Machine

**External Tools**  

* Asset conversion utilities
* Build automation systems
* Source control systems
* Platform-specific deployment tools

**Primary Purpose**  
Provide a structured high-level language and modern development environment for creating Amstrad CPC software.

---

<a id="ugbasic-header"></a>

# ugBASIC

**Official URL**
https://ugbasic.iwashere.eu/

**Source Code**
https://github.com/spotlessmind1975/ugbasic

Cross-Compiler / High-Level Language

**Host Platforms**

* Windows
* Linux
* macOS

**Verified Amstrad CPC Targets**

* Amstrad CPC 464
* Amstrad CPC 664
* Amstrad CPC 6128
* Amstrad CPC Plus range

**Overview**  
ugBASIC is an actively developed open-source cross-compiler that brings a modern implementation of the BASIC programming language to numerous retro-computing platforms, including the Amstrad CPC family.

The language is designed to make 8-bit software development accessible while still generating efficient native code suitable for real hardware. It includes a large collection of platform-aware commands covering graphics, sound, input devices, storage, and memory management.

For Amstrad CPC developers, ugBASIC provides a productive environment for creating games, educational software, utilities, prototypes, and demonstrations without requiring extensive assembly language knowledge. The compiler handles platform-specific implementation details while exposing high-level abstractions tailored to classic hardware.

The project places particular emphasis on portability, allowing software to be adapted across multiple retro-computing systems with relatively small changes to the source code.

**Development Features**  

* BASIC-based programming language
* Cross-compilation
* Native code generation
* Platform abstraction
* Graphics commands
* Sprite handling
* Tile and map support
* Sound programming support
* Input device handling
* File management functions
* Memory management facilities
* Structured programming constructs
* Extensive standard library
* Multi-platform targeting
* Active development and documentation

**Supported File Formats**  

* BAS
* ASM
* BIN
* DSK
* CDT
* Resource files
* Project files

**Integration**  

* Internal code generation
* Assembly output support
* WinAPE
* Arnold
* ACE-DL
* Retro Virtual Machine

**External Tools**  

* Asset conversion utilities
* Build automation systems
* Source control systems
* Deployment workflows

**Primary Purpose**  
Enable development of Amstrad CPC software using a modern BASIC dialect that compiles to efficient native code.

---

<a id="z88dk-header"></a>

# z88dk

**Official URL**
https://www.z88dk.org/

**Source Code**
https://github.com/z88dk/z88dk

**Host Platforms**

* Windows
* Linux
* macOS

**Verified Amstrad CPC Targets**

* Amstrad CPC 464
* Amstrad CPC 664
* Amstrad CPC 6128
* Amstrad CPC Plus range

**Overview**  
z88dk is a comprehensive Z80 development kit and C-language cross-compilation toolchain supporting a large number of Z80-based systems, including the complete Amstrad CPC family. It is one of the most mature and widely used retro-computing development environments available today.

The toolchain includes C compilers, assemblers, linkers, libraries, runtime support, debugging facilities, and target-specific frameworks. Developers can write software primarily in C while retaining the ability to integrate assembly language for performance-critical routines.

For CPC development, z88dk provides access to extensive platform libraries and hardware support, making it suitable for games, productivity software, communications software, educational programs, and operating system components. The project supports both small hobby projects and larger commercial-quality software development.

Its mature ecosystem, extensive documentation, and active community make it one of the most powerful high-level development options available for Amstrad CPC programming.

**Development Features**  

* ANSI C development environment
* Cross-compilation
* Z80 code generation
* Multiple compiler backends
* Integrated assembler support
* Linker and library management
* Runtime libraries
* Platform-specific APIs
* Mixed C and assembly development
* Build automation support
* Memory model management
* Optimisation options
* Extensive documentation
* Multi-platform targeting
* Large ecosystem of libraries

**Supported File Formats**  

* C
* H
* ASM
* LIB
* OBJ
* BIN
* ROM
* DSK
* CDT
* MAP
* Symbol files

**Integration**  

* z80asm
* External Z80 assemblers
* Mixed-language projects
* WinAPE
* Arnold
* ACE-DL
* Retro Virtual Machine

**External Tools**  

* CPCTelera
* CPCTools
* KC IDE
* Visual Studio Code
* Build automation systems
* Source control systems

**Primary Purpose**  
Provide a complete C-language cross-development toolchain for creating native Amstrad CPC software.
