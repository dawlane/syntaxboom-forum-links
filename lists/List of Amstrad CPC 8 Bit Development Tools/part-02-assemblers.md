# List of Amstrad CPC 8 Bit Development Tools - Assemblers

This is is going to be the start of a list of useful links to various tools for programming Amstrad CPC 8 Bit home computers. If anyone adds some gems, then they will be added to this post, so people don't have to go through every post.

**NOTE:** Many of these sites linked here, have not been fully checked or validated for what contents they offer, and possibly in the future they may also be broken. Anyone using the links should remain vigilant to protect themselves from malicious software and sites through the use of internet security software and good judgement by not falling prey to sites that require the specific entry of personal information. The accuracy of the descriptions may also not be correct, and should be in many cases considered a work-in-progress.
If they don't appear to be what is advertised, or look suspicious.
Then PM an administrator so they can be removed, or updated with the correct information.  
**So use these links and any associated software from these sites at your own risk!**  

## Table of contents

* [PASMO](#pasmo-header)
* [RASM](#rasm-header)
* [SjASMPlus](#sjasmplus-header)

---

<a id="pasmo-header"></a>

# PASMO

**Official URL**
https://pasmo.speccy.org/

**Host Platforms**

* Windows
* Linux
* macOS (via source build)

**Verified Amstrad CPC Targets**

* Amstrad CPC 464
* Amstrad CPC 664
* Amstrad CPC 6128
* Amstrad CPC Plus range

**Overview**  
PASMO is a portable cross-assembler for Z80-family processors designed for modern host systems. It supports the instruction sets used by the Amstrad CPC and other Z80-based platforms, making it suitable for developing games, demos, utilities, firmware, and hardware-related software.

The assembler is command-line driven and integrates easily into automated build systems, IDEs, scripts, and continuous integration workflows. PASMO supports multi-file projects through source inclusion mechanisms and provides compatibility features intended to ease migration from assemblers used in classic development environments.

For CPC developers, PASMO offers a lightweight and reliable assembly environment that can be incorporated into custom toolchains. Its portability and simplicity make it especially useful for projects that favour reproducible builds and platform-independent development workflows.

**Development Features**

* Z80 cross-assembly
* Command-line operation
* Multi-file project support
* Include file support
* Symbol handling
* Label management
* Conditional assembly
* Macro support
* Listing file generation
* Binary output generation
* Cross-platform operation
* Build script integration
* Portable source compatibility

**Supported File Formats**

* ASM
* INC
* BIN
* HEX
* Listing files
* Symbol files

**Integration**

* Standalone assembler
* WinAPE
* Arnold
* ACE-DL
* Retro Virtual Machine
* Any emulator supporting assembled binaries

**External Tools**

* KC IDE
* Visual Studio Code
* Makefiles
* Build scripts
* Continuous integration systems

**Primary Purpose**  
Assemble Z80 source code into executable binaries for Amstrad CPC software development.

---

<a id="rasm-header"></a>

# RASM

**Official URL**
https://github.com/EdouardBERGE/RASM

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
RASM is a modern high-performance Z80 assembler developed with a strong focus on Amstrad CPC development. It is widely adopted within the contemporary CPC demoscene and game-development communities due to its extensive macro system, advanced assembly capabilities, and support for large projects.

The assembler is designed to streamline development of sophisticated software by providing powerful language extensions, project structuring facilities, conditional compilation, and advanced source processing features. RASM supports modern development practices while maintaining compatibility with traditional CPC programming techniques.

Its extensive feature set makes it particularly attractive for large games, demos, and hardware-intensive projects where maintainability and build flexibility are important. RASM is often integrated into automated build environments and Visual Studio Code-based workflows.

**Development Features**

* Full Z80 assembly support
* Advanced macro system
* Conditional assembly
* Structured source organisation
* Multi-file projects
* Symbol export facilities
* Expression evaluation
* Reusable code generation
* Include file support
* Listing generation
* Binary generation
* Error diagnostics
* Fast assembly performance
* Scriptable build integration
* CPC-oriented development features

**Supported File Formats**

* ASM
* INC
* BIN
* ROM
* Symbol files
* Listing files

**Integration**

* Standalone assembler
* WinAPE
* Arnold
* ACE-DL
* Retro Virtual Machine

**External Tools**

* KC IDE
* Visual Studio Code
* Build automation systems
* Asset conversion tools
* Source control systems

**Primary Purpose**  
Provide a powerful modern assembler specifically suited to advanced Amstrad CPC software development.

---

<a id="sjasmplus-header"></a>

# SjASMPlus

**Official URL**
https://github.com/z00m128/sjasmplus

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
SjASMPlus is an actively maintained cross-platform Z80 assembler supporting a variety of Z80-based computer systems, including the Amstrad CPC. It is derived from the original SjASM project and extends it with modern development features, improved compatibility, and enhanced project management capabilities.

The assembler is widely used in retro-computing communities because it supports large projects, advanced macro processing, conditional compilation, and flexible output generation. It provides developers with a mature and well-documented environment suitable for both small utilities and large commercial-quality software projects.

For CPC development, SjASMPlus integrates easily into contemporary toolchains and development environments. Its cross-platform design and active maintenance make it a reliable choice for developers who require portability and long-term support.

**Development Features**

* Z80 cross-assembly
* Advanced macro facilities
* Conditional assembly
* Multi-file projects
* Include file support
* Symbol management
* Expression evaluation
* Listing generation
* Binary generation
* Label namespaces
* Structured source organisation
* Cross-platform operation
* Build automation integration
* Large-project support

**Supported File Formats**

* ASM
* INC
* BIN
* HEX
* ROM
* Listing files
* Symbol files

**Integration**

* Standalone assembler
* WinAPE
* Arnold
* ACE-DL
* Retro Virtual Machine

**External Tools**

* KC IDE
* Visual Studio Code
* Makefiles
* Build automation systems
* Continuous integration workflows

**Primary Purpose**  
Assemble Z80 source code into executable output files for modern Amstrad CPC software development projects.

[Back to index](index.md)
