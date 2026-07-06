# List of Commodore 8 Bit Development Tools

This is is going to be the start of a list of useful links to various game libraries and game render engines. If anyone adds some gems, then they will be added to this post, so people don't have to go through every post.

**NOTE:** Many of these sites linked here, have not been fully checked or validated for what contents they offer, and possibly in the future they may also be broken. Anyone using the links should remain vigilant to protect themselves from malicious software and sites through the use of internet security software and good judgement by not falling prey to sites that require the specific entry of personal information. The accuracy of the descriptions may also not be correct, and should be in many cases considered a work-in-progress.
If they don't appear to be what is advertised, or look suspicious.
Then PM an administrator so they can be removed, or updated with the correct information.  
**So use these links and any associated software from these sites at your own risk!**  

## Index

### [Integrated Development Environments (IDEs)](#integrated-development-environments-ides)

* [C64 Studio](#c64-studio-header)
* [CBM .prg Studio](#cbm-prg-studio-header)
* [ReadyCode](#readycode-header)
* [Relaunch64](#relaunch64-header)
* [VS64](#vs64-header)
* [WUDSN IDE](#wudsn-ide-header)

### [Assemblers](#assemblers-header)

* [64tass](#64tass-header)
* [ACME Cross-Assembler](#acme-cross-assembler-header)
* [Asm6502](#asm6502-header)
* [Kick Assembler](#kick-assembler-header)
* [Ophis](#ophis-header)
* [Retro Assembler](#retro-assembler-header)
* [Turbo Macro Pro X (TMPx)](#tpmx-header)
* [WLA DX (Wzonka-Lad Assembler Deluxe)](#wla-dx-header)
* [XA (xa65)](#xa65-header)

### [Cross-Compilers & High-Level Languages](#compilers-header)

* [cc65](#cc65-header)
* [KickC](#kickc-header)
* [Millfork](#millfork-header)
* [Oscar64](#oscar64-header)
* [Prog8](#prog8-header)
* [TRSE (Turbo Rascal Syntax Error)](#trse-header)
* [ugBASIC](#ugbasic-header)
* [XC=BASIC 3](#xcbasic3-header)

### [Emulators](#emulators-header)

* [CCS64](#ccs64-header)
* [C64 Forever](#c64-forever-header)
* [Denise](#denise-header)
* [Frodo](#frodo-header)
* [Hoxs64](#hoxs64-header)
* [VICE (Versatile Commodore Emulator)](#vice-header)

### [Bitmap, Map. Character & Sprite Editors](#bitmap-map-characte-and-sprite-editors-header)

* [Master of Sprites](#master-of-sprites-header)
* [OpenSprite](#opensprite-header)
* [Petmate](#petmate-header)
* [CharPad C64 Pro](#charpad-c64-pro-header)
* [SpritePad C64 Pro](#spritepad-c64-pro-header)
* [png2c64](#png2c64-header)

### [Music, SID & Audio Tools](#music-sid-audio-tools-header)

* [GoatTracker 2](#goattracker2-header)
* [Sid Factory II](#sidfactory2-header)
* [DefleMask](#deflemask-header)
* [CheeseCutter 2](#cheesecutter2-header)
* [JITT64](#jitt64-header)

### [Disk Tools](#disk-tools-header)

* [OpenCBM](#opencbm-header)
* [DirMaster](#dirmaster-header)

### [Frameworks & SDK's](#frameworks-and-sdks-header)

* [c64lib](#c64lib-header)
* [c64gameframework](#c64gameframework-header)

### [Asset Conversion Tools](#asset-conversion-tools-header)

* [c64img](#c64img-header)
* [Petsciiator](#petsciiator-header)
* [RetroPixels+](#retropixels-header)

----

<a id="integrated-development-environments-ides"></a>

## Integrated Development Environments

<a id="c64-studio-header"></a>

### <ins style="color: red">C64 Studio</ins>

**Official URL**
https://github.com/GeorgRottensteiner/C64Studio

**Category**
Integrated Development Environment

**Host Platforms**

* Windows

**Verified Commodore Targets**

* C64

**License**
Open Source

**Status**
Maintained

**Overview**  
C64 Studio is a comprehensive Windows-based development environment specifically designed for Commodore 64 software creation. It provides a tightly integrated workflow that combines source code editing, project organisation, asset creation tools, and build automation into a single application. Unlike lightweight editors that rely on external tooling, C64 Studio is designed as a full IDE where most aspects of C64 development can be handled without leaving the environment. It is widely used in modern C64 game and demo production pipelines due to its integrated support for graphics and assembly workflows.

**Development Features**

* Integrated assembler workflow
* Sprite editor
* Character set editor
* Map editor for tile-based design
* Project management system
* Build automation system
* D64 disk image handling
* Emulator launch integration

**Supported File Formats**

* ASM source
* PRG binaries
* D64 disk images
* Character and sprite data formats

**Integration**

* External 6502 assemblers
* VICE emulator

**Primary Purpose**
All-in-one Commodore 64 development environment

---

<a id="cbm-prg-studio-header"></a>

### <ins style="color: red">CBM .prg Studio</ins>

**Official URL**
http://www.ajordison.co.uk/

**Category**
Integrated Development Environment

**Host Platforms**

* Windows

**Verified Commodore Targets**

* C64

**License**
Freeware

**Status**
Distributed

**Overview**  
CBM .prg Studio is a Windows-based integrated development environment focused on Commodore 8-bit development, particularly the Commodore 64. It provides a unified workspace where developers can write assembly or BASIC code, create graphical assets, and manage projects targeting multiple Commodore systems. The tool is designed to simplify the traditional fragmented workflow of C64 development by combining editing, asset creation, and emulator testing into a single environment.

**Development Features**

* Assembly and BASIC editors
* Integrated sprite editor
* Character set editor
* Disk image creation tools
* Emulator launching
* Project organisation tools

**Supported File Formats**

* PRG
* D64
* TAP
* Character/sprite data formats

**Integration**

* VICE emulator
* External assemblers

**Primary Purpose**
Commodore multi-language development IDE

---

<a id="readycode-header"></a>

### <ins style="color: red">READYCode</ins>

**Official URL**
https://github.com/jbramwell/readycode

**Category**
Integrated Development Environment

**Host Platforms**

* Windows
* Linux
* macOS

**Verified Commodore Targets**

* C64

**License**
Open Source

**Status**
Active

**Overview**    
READYCode is a modern lightweight development environment focused specifically on Commodore 64 BASIC development. It is designed to provide a streamlined editing and execution workflow that targets modern Commodore emulation environments. Unlike full-featured IDEs, READYCode focuses on simplicity and rapid iteration, making it particularly suitable for learning, experimentation, and BASIC-based software development on the Commodore 64 platform.

**Development Features**  

* BASIC source editor
* Quick run integration with emulator
* Lightweight project handling
* Syntax highlighting for BASIC
* Simple build/run workflow

**Supported File Formats**

* BASIC source files
* PRG output files

**Integration**

* VICE emulator

**Primary Purpose**
Lightweight Commodore 64 BASIC development environment

---

<a id="relaunch64-header"></a>

### <ins style="color: red">Relaunch64</a>

**Official URL**
https://github.com/sjPlot/Relaunch64

**Category**
Integrated Development Environment

**Host Platforms**

* Windows
* Linux
* macOS

**Verified Commodore Targets**

* C64

**License**
Open Source

**Status**
Active

**Overview**    
Relaunch64 is a flexible development environment designed to act as a workflow hub rather than a monolithic IDE. It orchestrates external assemblers, compilers, and emulators, allowing developers to assemble custom toolchains while maintaining a unified interface. It is particularly valued in modern Commodore development for its ability to integrate disparate tools into a consistent workflow without enforcing a single development model.

**Development Features**

* External assembler orchestration
* Emulator integration
* Project management
* Build pipeline configuration
* Multi-toolchain support
* Flexible workflow definition

**Supported File Formats**

* ASM
* PRG
* Binary outputs from external tools

**Integration**

* VICE emulator
* Kick Assembler
* 64tass
* Other external toolchains

**Primary Purpose**
Workflow orchestration for Commodore development

---

<a id="vs64-header"></a>

### <ins style="color: red">VS64</ins>

**Official URL**
https://github.com/rosc77/vs64
https://marketplace.visualstudio.com/items?itemName=rosc.vs64

**Category**
Integrated Development Environment

**Host Platforms**

* Windows
* Linux
* macOS

**Verified Commodore Targets**

* C64

**License**
Open Source

**Status**
Active

**Overview**    
VS64 is a Visual Studio Code extension that transforms VS Code into a Commodore 64 development environment. It integrates build tools, emulator support, and project workflows directly into a modern editor interface. It is designed for developers who prefer contemporary IDEs but want full Commodore 64 development capabilities integrated into their workflow.

**Development Features**

* VS Code integration
* Build automation
* Emulator launching
* Debug support
* Project templates
* Assembly workflow support

**Supported File Formats**

* ASM
* PRG
* D64

**Integration**

* External assemblers
* VICE emulator

**Primary Purpose**
VS Code-based Commodore 64 development environment

---

<a id="wudsn-ide-header"></a>

### <ins style="color: red">WUDSN IDE</ins>

**Official URL**
https://www.wudsn.com/index.php/ide

**Category**
Integrated Development Environment

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

**License**
Freeware

**Status**
Maintained

**Overview**  
WUDSN IDE is an Eclipse-based retro development environment supporting multiple 6502-family systems including the Commodore 8-bit family. It is designed for cross-platform development workflows and integrates assemblers, emulators, and debugging tools within the Eclipse ecosystem. Its strength lies in supporting multiple retro platforms under a unified IDE framework.

**Development Features**

* Eclipse-based IDE integration
* Multi-platform assembler support
* Emulator launching
* Project management
* Source navigation tools
* Syntax highlighting

**Supported File Formats**

* ASM
* PRG
* Binary outputs

**Integration**

* VICE emulator
* External assemblers

**Primary Purpose**
Multi-platform retro development IDE

----

<a id="assemblers-header"></a>

## Assemblers

<a id="64tass-header"></a>

### <ins style="color: red">64tass</ins>

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

**License**
Open Source

**Status**
Active

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

### <ins style="color: red">ACME Cross-Assembler</ins>

**Official URL**
https://sourceforge.net/projects/acme-crossass/

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

**License**
Open Source

**Status**
Active

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

### <ins style="color: red">Asm6502</ins>

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

**License**
Open Source

**Status**
Active

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

<a id="kick-assembler-header"></a>

### <ins style="color: red">Kick Assembler</ins>

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

**License**
Freeware

**Status**
Active

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

### <ins style="color: red">Ophis</ins>

**Official URL**
https://michaelcmartin.github.io/Ophis/

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

**License**
Open Source

**Status**
Maintained

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

### <ins style="color: red">Retro Assembler</ins>

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

**License**
Commercial

**Status**
Active

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

<a id="tpmx-header"></a>

### <ins style="color: red">Turbo Macro Pro X (TMPx)</ins>

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

**License**
Open Source

**Status**
Maintained

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

### <ins style="color: red">WLA DX (Wzonka-Lad Assembler Deluxe)</ins>

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

**License**
Open Source

**Status**
Active

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

<a id="xa65-header"></a>

### <ins style="color: red">XA (xa65)</ins>

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

**License**
Open Source

**Status**
Maintained

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

----

<a id="compilers-header"></a>

# Cross-Compilers & High-Level Languages

<a id="cc65-header"></a>

### <ins style="color: red">cc65</a>

**Official URL**
https://cc65.github.io/

**Category**
Cross-Compiler & C Toolchain

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

**License**
Open Source

**Status**
Active

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

### <ins style="color: red">KickC</ins>

**Official URL**
https://gitlab.com/camelot/kickc

**Category**
Cross-Compiler & Optimising C Compiler

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

**License**
Open Source

**Status**
Active

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

### <ins style="color: red">Millfork</ins>

**Official URL**
https://github.com/KarolS/millfork

**Category**
Cross-Compiler & Structured High-Level Language

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

**License**
Open Source

**Status**
Active

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

### <ins style="color: red">Oscar64</ins>

**Official URL**
https://github.com/drmortalwombat/oscar64

**Category**
Cross-Compiler & C Compiler

**Host Platforms**

* Windows
* Linux
* macOS

**Verified Commodore Targets**

* C64
* C128
* MEGA65

**License**
Open Source

**Status**
Active

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

### <ins style="color: red">Prog8</ins>

**Official URL**
https://github.com/irmen/prog8

**Category**
Cross-Compiler & High-Level Language

**Host Platforms**

* Windows
* Linux
* macOS

**Verified Commodore Targets**

* C64
* C128
* PET

**License**
Open Source

**Status**
Active

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

### <ins style="color: red">TRSE (Turbo Rascal Syntax Error)</ins>

**Official URL**
https://lemonspawn.com/turbo-rascal-syntax-error/

**Category**
Cross-Compiler & Pascal-like Language IDE

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

**License**
Open Source

**Status**
Active

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

### <ins style="color: red">ugBASIC</ins>

**Official URL**
https://ugbasic.iwashere.eu/

**Category**
Cross-Compiler & BASIC Language

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

**License**
Open Source

**Status**
Active

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

<a id="xcbasic3-header"></a>

### <ins style="color: red">XC=BASIC 3</ins>

**Official URL**
https://xc-basic.net/

**Category**
Cross-Compiler & Optimised BASIC Compiler

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

**License**
Commercial

**Status**
Active

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

----

<a id="emulators-header"></a>

## Emulators

<a id="ccs64-header"></a>

### <ins style="color: red">CCS64</ins>

**Official URL**
https://www.ccs64.com/

**Category**
Emulator

**Host Platforms**

* Windows

**Verified Commodore Targets**

* C64

**License**
Shareware

**Status**
Active

**Overview**  
CCS64 is a long-established Commodore 64 emulator known for its high compatibility and stability. It focuses on accurate execution timing and broad software support, making it suitable for both gameplay and software testing. It includes debugging features that allow developers to inspect memory and CPU state during execution.

**Development Features**

* CPU debugging tools
* Memory inspection
* Cartridge support
* Snapshot system
* Timing accuracy controls
* Input recording and playback

**Supported Media Formats**

* D64
* G64
* T64
* PRG
* CRT
* TAP

**Integration**

* External assemblers
* IDE workflows (Relaunch64, VS64)

**Primary Purpose**
High-compatibility Commodore 64 emulation

---

<a id="c64-forever-header"></a>

### <ins style="color: red">C64 Forever</ins>

**Official URL**
https://www.c64forever.com/

**Category**
Emulator Suite

**Host Platforms**

* Windows

**Verified Commodore Targets**

* C64
* C128
* VIC-20
* PET
* Plus/4

**License**
Commercial

**Status**
Active

**Overview**  
C64 Forever is a commercial Commodore emulation and preservation suite built around the VICE emulator core. It provides a curated and user-friendly environment for running Commodore software while also including tools for managing disk images, cartridges, and legacy software collections. It is designed for both preservation and casual usage.

**Development Features**

* VICE-based core emulation
* Integrated ROM management
* Snapshot system
* Software library management
* Automated configuration
* User-friendly GUI

**Supported Media Formats**

* D64
* D71
* D81
* G64
* T64
* PRG
* CRT
* TAP

**Integration**

* External development tools
* VICE-compatible workflows

**Primary Purpose**
Curated Commodore emulation and preservation environment

---

<a id="denise-header"></a>

### <ins style="color: red">Denise</a>

**Official URL**
https://sourceforge.net/projects/deniseemu/

**Category**
Emulator

**Host Platforms**

* Windows
* Linux
* macOS

**Verified Commodore Targets**

* C64
* C128
* VIC-20
* Plus/4

**License**
Open Source

**Status**
Active

**Overview**  
Denise is a modern Commodore emulator focused on low latency, visual accuracy, and developer-friendly features. It is widely used for both gameplay and demo development due to its advanced rendering pipeline and precise hardware emulation. It prioritises user experience while still maintaining strong cycle-accurate behaviour.

**Development Features**

* Cycle-accurate emulation
* Run-ahead input latency reduction
* Debugging tools
* VIC-II visual inspection
* SID audio analysis tools
* Shader-based rendering
* Breakpoints and stepping

**Supported Media Formats**

* D64
* G64
* T64
* PRG
* CRT
* TAP

**Integration**

* External IDEs
* Assembly pipelines
* Debug tooling workflows

**Primary Purpose**
Low-latency accurate Commodore emulation

---

<a id="frodo-header"></a>

### <ins style="color: red">Frodo</ins>

**Official URL**
https://frodo.cebix.net/

**Category**
Emulator

**Host Platforms**

* Windows
* Linux
* macOS

**Verified Commodore Targets**

* C64

**License**
Open Source

**Status**
Maintained

**Overview**  
Frodo is one of the earliest portable Commodore 64 emulators and remains available as a lightweight alternative to modern full-featured emulators. It prioritises portability and simplicity over extreme accuracy, making it useful for educational purposes and lightweight software testing.

**Development Features**

* Lightweight execution model
* Snapshot support
* Simple debugging tools
* Portable architecture
* Minimal configuration overhead

**Supported Media Formats**

* D64
* T64
* PRG

**Integration**

* External toolchains
* Basic IDE workflows

**Primary Purpose**
Lightweight Commodore 64 emulation

---

<a id="hoxs64-header"></a>

### <in style="color: red">Hoxs64</ins>

**Official URL**
https://sourceforge.net/projects/hoxs64/

**Category**
Emulator

**Host Platforms**

* Windows

**Verified Commodore Targets**

* C64

**License**
Open Source

**Status**
Active

**Overview**  
Hoxs64 is a highly accurate Commodore 64 emulator designed with a strong focus on hardware-level correctness. It is frequently used by developers who require precise timing analysis of VIC-II and SID behaviour. It includes extensive debugging tools that allow deep inspection of system state.

**Development Features**

* Cycle-accurate CPU emulation
* VIC-II inspection tools
* SID debugging tools
* Breakpoint system
* Memory analysis tools
* Machine language monitor

**Supported Media Formats**

* D64
* G64
* T64
* PRG
* CRT
* TAP

**Integration**

* Assembly toolchains
* IDE environments
* Debug pipelines

**Primary Purpose**
Hardware-accurate Commodore 64 emulation

----

<a id="vice-header"></a>

### <ins style="color: red">VICE (Versatile Commodore Emulator)</ins>

**Official URL**
https://vice-emu.sourceforge.io/

**Category**
Emulator

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

**License**
Open Source

**Status**
Active

**Overview**  
VICE is the reference emulator for the Commodore 8-bit family and is widely regarded as the most important development and preservation tool in the ecosystem. It provides cycle-accurate emulation of multiple Commodore systems and is used extensively by developers, preservationists, and the demoscene. Its accuracy, configurability, and debugging tools make it the de facto standard for testing Commodore software on modern systems.

**Development Features**

* Machine language monitor
* Cycle-accurate execution
* VIC-II and SID debugging tools
* Memory inspection
* Breakpoints and watchpoints
* Remote debugging support
* Drive emulation
* Cartridge emulation

**Supported Media Formats**

* D64
* D71
* D81
* G64
* T64
* PRG
* CRT
* TAP
* P00

**Integration**

* Kick Assembler
* cc65
* Relaunch64
* VS64
* WUDSN IDE

**Primary Purpose**
Reference-grade Commodore 8-bit emulation

---

<a id="bitmap-map-characte-and-sprite-editors-header"></a>

## Bitmap, Map. Character & Sprite Editors

<a id="master-of-sprites-header"></a>

### <ins style="color: red">Master of Sprites</ins>

**Official URL**
https://github.com/

**Category**
Sprite Editor

**Host Platforms**

* Windows
* Linux
* macOS

**Verified Commodore Targets**

* C64

**License**
Open Source

**Status**
Active

**Overview**  
Master of Sprites is a dedicated Commodore 64 sprite design tool focused on efficient creation, editing, and organisation of VIC-II sprite data. It is designed around the strict 24×21 pixel sprite constraints of the C64 hardware and supports multi-sprite sets used in animation and game development. It emphasises workflow efficiency for demoscene and game asset production.

**Development Features**

* Sprite grid editor (24×21 VIC-II format)
* Multi-sprite animation sets
* Palette constrained editing
* Export to assembly-ready formats
* Sprite bank management

**Supported Formats**

* VIC-II sprite data
* Assembly export files

**Integration**

* Kick Assembler
* VICE emulator
* External toolchains

**Primary Purpose**
Dedicated Commodore 64 sprite creation tool

---

<a id="opensprite-header"></a>

### <ins style="color: red">OpenSprite</ins>

**Official URL**
https://github.com/

**Category**
Sprite Editor

**Host Platforms**

* Windows
* Linux
* macOS

**Verified Commodore Targets**

* C64

**License**
Open Source

**Status**
Active

**Overview**  
OpenSprite is a modern open-source sprite editor designed for retro systems including the Commodore 64. It provides a flexible editing environment for VIC-II sprite data, with support for multi-frame animation and export pipelines suited for assembly-based development workflows.

**Development Features**

* Pixel-level sprite editor
* Multi-frame animation support
* Grid-based VIC-II layout editing
* Export to raw sprite data
* Palette constrained editing

**Supported Formats**

* Sprite binary data
* Assembly export formats

**Integration**

* VICE emulator
* Assembly toolchains

**Primary Purpose**
General-purpose retro sprite editing tool

---

<a id="petmate-header"></a>

### <ins style="color: red">Petmate</ins>

**Official URL**
https://nurpax.github.io/petmate/

**Category**
PETSCII & Character Editor

**Host Platforms**

* Windows
* Linux
* macOS
* Web

**Verified Commodore Targets**

* C64
* VIC-20
* PET

**License**
Open Source

**Status**
Maintained

**Overview**  
Petmate is a PETSCII and character-mode graphics editor designed for Commodore systems. It allows developers to design text-mode screens, logos, and character-based graphics using the Commodore character set. It is widely used in demoscene production and retro software development where character graphics are preferred over bitmap rendering.

**Development Features**

* PETSCII character editor
* Screen layout design
* Charset editing
* Grid-based editing system
* Export to assembly data

**Supported Formats**

* PETSCII screens
* Charset data
* Assembly export

**Integration**

* VICE emulator
* Assembly toolchains

**Primary Purpose**
Character-mode and PETSCII asset creation

---

<a id="charpad-c64-pro-header"></a>

### <ins style="color: red">CharPad C64 Pro</ins>

**Official URL**
https://subchristsoftware.itch.io/charpad-c64-pro

**Category**
Character & Map Editor

**Host Platforms**

* Windows

**Verified Commodore Targets**

* C64

**License**
Commercial

**Status**
Active

**Overview**  
CharPad C64 Pro is a professional-grade character set and tile map editor for Commodore 64 development. It is designed to work within VIC-II constraints and is widely used for tile-based game development. It supports advanced map editing features including layered tilemaps and memory-efficient character reuse strategies.

**Development Features**

* Character set editor
* Tile map editor
* Multi-layer map design
* VIC-II constraint-aware layout
* Palette management
* Animation frame support

**Supported Formats**

* Charset data
* Tile map data
* Assembly export

**Integration**

* Kick Assembler
* VICE emulator
* Game development pipelines

**Primary Purpose**
Tile-based map and character asset creation

---

<a id="spritepad-c64-pro-header"></a>

### <ins style="color: red">SpritePad C64 Pro</ins>

**Official URL**
https://subchristsoftware.itch.io/spritepad-c64-pro

**Category**
Sprite Editor

**Host Platforms**

* Windows

**Verified Commodore Targets**

* C64

**License**
Commercial

**Status**
Active

**Overview**  
SpritePad C64 Pro is a dedicated Commodore 64 sprite editing tool focused on fast creation and management of VIC-II sprites. It provides tools for designing sprite sets, managing animation frames, and exporting directly into formats suitable for assembly and game development workflows.

**Development Features**

* VIC-II sprite editor
* Multi-sprite animation support
* Sprite bank management
* Frame sequencing tools
* Palette constrained editing

**Supported Formats**

* Sprite binary data
* Assembly export formats

**Integration**

* Kick Assembler
* VICE emulator

**Primary Purpose**
Professional Commodore 64 sprite creation

---

<a id="png2c64-header"></a>

### <ins style="color: red">png2c64</ins>

**Official URL**
https://github.com/

**Category**
Bitmap Conversion Tool

**Host Platforms**

* Windows
* Linux
* macOS

**Verified Commodore Targets**

* C64

**License**
Open Source

**Status**
Active

**Overview**  
png2c64 is a conversion utility that transforms modern PNG images into Commodore 64-compatible bitmap formats. It handles palette reduction, dithering, and conversion into VIC-II-compatible graphics layouts. It is primarily used as part of asset pipelines for games and demos where modern artwork must be adapted to retro hardware constraints.

**Development Features**

* PNG to VIC-II bitmap conversion
* Palette reduction
* Dithering algorithms
* Charset conversion support
* Batch processing support

**Supported Formats**

* PNG input
* C64 bitmap output

**Integration**

* Assembly pipelines
* Game asset workflows

**Primary Purpose**
Modern-to-Commodore bitmap conversion tool

----

<a id="music-sid-audio-tools-header"></a>

## Music, SID & Audio Tools

<a id="goattracker2-header"></a>

### <ins style="color: red">GoatTracker 2</ins>

**Official URL**
https://sourceforge.net/projects/goattracker2/

**Category**
SID Music Tracker

**Host Platforms**

* Windows
* Linux
* macOS

**Verified Commodore Targets**

* C64

**License**
Open Source

**Status**
Active

**Overview**  
GoatTracker 2 is one of the most widely used SID music trackers for Commodore 64 music production. It allows composers to create music that runs directly on the SID chip by providing a tracker-style interface designed around real hardware constraints. It is heavily used in the demoscene and homebrew game development for producing authentic C64 audio.

**Development Features**

* SID channel tracker interface
* Real-time playback emulation
* Instrument editor
* Waveform shaping tools
* Pattern sequencing system
* Effect command system

**Supported Formats**

* SID files
* Binary music data
* Tracker project files

**Integration**

* VICE emulator
* C64 game engines
* Assembly pipelines

**Primary Purpose**
Native Commodore 64 SID music composition

---

<a id="sidfactory2-header"></a>

### <ins style="color: red">SID Factory II</ins>

**Official URL**
https://csdb.dk/release/?id=200808

**Category**
SID Music Tracker

**Host Platforms**

* Windows

**Verified Commodore Targets**

* C64

**License**
Freeware

**Status**
Active

**Overview**  
SID Factory II is a modern SID music tracker designed for composing music directly targeting the Commodore 64 SID chip. It provides a more modern workflow than traditional trackers while still maintaining strict compatibility with real hardware. It is widely used for game music and demo productions.

**Development Features**

* Advanced SID instrument editor
* Multi-voice composition
* Real-time playback
* Effect automation system
* Pattern-based sequencing
* Export to SID format

**Supported Formats**

* SID
* Music data exports
* Tracker project files

**Integration**

* VICE emulator
* Game engines
* Assembly pipelines

**Primary Purpose**
Modern SID music composition tool

---

<a id="deflemask-header"></a>

### <ins style="color: red">DefleMask</ins>

**Official URL**
https://www.deflemask.com/
https://store.steampowered.com/app/2422830/DefleMask/

**Category**
Multi-System Chiptune Tracker

**Host Platforms**

* Windows
* Linux
* macOS

**Verified Commodore Targets**

* C64

**License**
Commercial

**Status**
Active

**Overview**  
DefleMask is a cross-platform chiptune tracker supporting multiple retro sound chips, including the Commodore 64 SID chip. It allows composers to create music for multiple systems using a unified interface, making it popular for cross-platform retro game development and modern chiptune production.

**Development Features**

* Multi-system sound chip support
* SID chip emulation mode
* Pattern-based sequencing
* Instrument editor
* Real-time playback
* Export to multiple formats

**Supported Formats**

* Module files
* Exported SID-compatible audio data

**Integration**

* VICE emulator
* Game development pipelines

**Primary Purpose**
Multi-platform chiptune composition including C64 SID

---

<a id="cheesecutter2-header"></a>

### <ins style="color: red">CheeseCutter 2</ins>

**Official URL**
https://github.com/theyamo/CheeseCutter

**Category**
SID Editor / Tracker

**Host Platforms**

* Windows
* Linux
* macOS

**Verified Commodore Targets**

* C64

**License**
Open Source

**Status**
Maintained

**Overview**  
CheeseCutter 2 is a modern SID tracker and editor focused on providing a lightweight but powerful environment for composing Commodore 64 music. It is designed to be efficient and accessible while still allowing deep control over SID chip behaviour.

**Development Features**

* SID waveform editor
* Pattern-based sequencing
* Instrument editor
* Real-time playback
* Lightweight interface
* Export to SID format

**Supported Formats**

* SID
* Tracker project files

**Integration**

* VICE emulator
* Game audio pipelines

**Primary Purpose**
Lightweight SID music composition

---

<a id="jitt64-header"></a>

### <ins style="color: red">JITT64</ins>

**Official URL**
https://github.com/

**Category**
SID Tool / Audio Utility

**Host Platforms**

* Windows
* Linux
* macOS

**Verified Commodore Targets**

* C64

**License**
Open Source

**Status**
Active

**Overview**  
JITT64 is a modern SID-related utility tool used in Commodore 64 audio development pipelines. It is designed to assist with SID music generation workflows, analysis, or conversion tasks depending on project configuration. It is primarily used as a supporting tool within larger SID production pipelines rather than as a standalone tracker.

**Development Features**

* SID data processing utilities
* Music data conversion tools
* Pipeline integration support
* Lightweight CLI design

**Supported Formats**

* SID-related binary formats
* Tracker export formats

**Integration**

* GoatTracker workflows
* VICE emulator
* Assembly pipelines

**Primary Purpose**
SID audio processing and tooling utility

----

<a id="disk-tools-header"></a>

## Disk Tools

<a id="opencbm-header"></a>

### <ins style="color: red">OpenCBM</ins>

**Official URL**
https://spiro.trikaliotis.net/opencbm

**Category**
Disk & Hardware Interface Tool

**Host Platforms**

* Windows
* Linux
* macOS

**Verified Commodore Targets**

* C64
* VIC-20
* C128

**License**
Open Source

**Status**
Active

**Overview**  
OpenCBM is a hardware interface and software suite for accessing Commodore floppy disk drives from modern systems. It allows developers to read, write, and manipulate real Commodore disks using compatible hardware interfaces. It is a foundational tool for preservation, disk imaging, and physical media workflows.

**Development Features**

* Direct disk drive communication
* D64/D71/D81 imaging support
* Fast serial transfer support
* Disk reading and writing tools
* Drive diagnostics utilities

**Supported Formats**

* D64
* D71
* D81
* G64 (via tooling)
* RAW disk data

**Integration**

* VICE emulator workflows
* Disk image toolchains
* Preservation pipelines

**Primary Purpose**
Physical Commodore disk access and manipulation

---

<a id="dirmaster-header"></a>

### <ins style="color: red">DirMaster</ins>

**Official URL**
https://style64.org/dirmaster

**Category**
Disk Image Editor

**Host Platforms**

* Windows

**Verified Commodore Targets**

* C64
* VIC-20
* C128

**License**
Freeware

**Status**
Maintained

**Overview**  
DirMaster is a powerful graphical tool for editing Commodore disk images. It allows developers to create, modify, and organise files within D64 and related disk formats. It is widely used in game development and demo production for preparing release disks.

**Development Features**

* Disk image editing
* File import/export
* Directory management
* Disk sector visualisation
* Batch file operations

**Supported Formats**

* D64
* D71
* D81

**Integration**

* VICE emulator
* Assembly workflows
* Game packaging pipelines

**Primary Purpose**
Commodore disk image creation and editing

---

<a id="frameworks-and-sdks-header"></a>

## Frameworks & SDK's

<a id="c64lib-header"></a>

### <ins style="color: red">c64lib</ins>

**Official URL**
https://c64lib.github.io/

**Category**
Assembly Framework / SDK

**Host Platforms**

* Windows
* Linux
* macOS

**Verified Commodore Targets**

* C64

**License**
Open Source

**Status**
Active

**Overview**  
c64lib is a modular assembly language framework designed to simplify Commodore 64 development by providing reusable low-level routines and abstractions. It focuses on structured assembly programming and reusable components for graphics, sound, memory management, and hardware interaction.

**Development Features**

* Reusable assembly modules
* Hardware abstraction layer
* Sprite and graphics routines
* SID audio utilities
* Memory management tools
* Modular build system support

**Supported Formats**

* Assembly source modules
* PRG integration outputs

**Integration**

* Kick Assembler
* ACME
* VICE emulator

**Primary Purpose**
Structured assembly development framework for C64

---

<a id="c64gameframework-header"></a>

### <ins style="color: red">c64gameframework</ins>

**Official URL**
https://github.com/cadaver/c64gameframework

**Category**
Game Development Framework

**Host Platforms**

* Windows
* Linux
* macOS

**Verified Commodore Targets**

* C64

**License**
Open Source

**Status**
Active

**Overview**  
c64gameframework is a lightweight game development framework for Commodore 64 assembly projects. It provides reusable systems for input handling, game loops, graphics routines, and memory management, allowing developers to focus on gameplay logic rather than low-level hardware setup.

**Development Features**

* Game loop abstraction
* Input handling system
* Sprite management utilities
* Memory layout helpers
* Basic rendering routines

**Supported Formats**

* Assembly source
* PRG builds

**Integration**

* Kick Assembler
* VICE emulator

**Primary Purpose**
Commodore 64 assembly game development framework

---

<a id="asset-conversion-tools-header"></a>

## Asset Conversion Tools

<a id="c64img-header"></a>

### <ins style="color:red">c64img<ins>

**Official URL**
https://github.com/

**Category**
Asset Conversion Tool

**Host Platforms**

* Windows
* Linux
* macOS

**Verified Commodore Targets**

* C64

**License**
Open Source

**Status**
Active

**Overview**  
c64img is an image conversion tool designed to transform modern bitmap graphics into Commodore 64-compatible formats. It supports palette reduction and conversion into VIC-II constrained formats suitable for use in games and demos.

**Development Features**

* Image format conversion
* Palette reduction
* Dithering support
* VIC-II format output
* Batch processing

**Supported Formats**

* PNG input
* C64 bitmap output

**Integration**

* Assembly pipelines
* Game asset workflows

**Primary Purpose**
Bitmap conversion for Commodore graphics pipelines

---

<a id="petsciiator-header"></a>

### <ins style="color: red">Petsciiator</ins>

**Official URL**
https://github.com/

**Category**
PETSCII Asset Tool

**Host Platforms**

* Windows
* Linux
* macOS

**Verified Commodore Targets**

* C64
* VIC-20

**License**
Open Source

**Status**
Active

**Overview**  
Petsciiator is a PETSCII art and text conversion tool that allows modern text or images to be converted into Commodore PETSCII character graphics. It is commonly used for splash screens, intro screens, and retro-styled UI design.

**Development Features**

* Text-to-PETSCII conversion
* Image-to-character mapping
* Charset editing support
* Screen layout export
* Palette constrained rendering

**Supported Formats**

* PETSCII screens
* Charset data

**Integration**

* VICE emulator
* Assembly toolchains

**Primary Purpose**
PETSCII graphics generation tool

---

<a id="retropixels-header"></a>

### <ins style="color: red">RetroPixels+</ins>

**Official URL**
https://github.com/

**Category**
Graphics Conversion Tool

**Host Platforms**

* Windows
* Linux
* macOS

**Verified Commodore Targets**

* C64

**License**
Open Source

**Status**
Active

**Overview**  
RetroPixels+ is an asset conversion tool designed to convert modern images into retro-computer-compatible formats, including Commodore 64 bitmap and character-based graphics. It provides fine control over dithering, palette selection, and output formats.

**Development Features**

* Bitmap conversion pipeline
* Palette optimisation
* Dithering algorithms
* Charset conversion
* Batch processing tools

**Supported Formats**

* PNG input
* C64 bitmap output
* Charset data

**Integration**

* Game asset pipelines
* Assembly toolchains
* Emulator testing workflows

**Primary Purpose**
General retro graphics conversion pipeline tool
