This is is going to be the start of a list of useful links to various game libraries and game render engines. If anyone adds some gems, then they will be added to this post, so people don't have to go through every post.

**NOTE:** Many of these sites linked here, have not been fully checked or validated for what contents they offer, and possibly in the future they may also be broken. Anyone using the links should remain vigilant to protect themselves from malicious software and sites through the use of internet security software and good judgement by not falling prey to sites that require the specific entry of personal information. The accuracy of the descriptions may also not be correct, and should be in many cases considered a work-in-progress.
If they don't appear to be what is advertised, or look suspicious.
Then PM an administrator so they can be removed, or updated with the correct information.  
**So use these links and any associated software from these sites at your own risk!**

# Commodore 64 Development Tools

## Index

- [Integrated Development Environments (IDEs)](#integrated-development-environments-ides)
- [Assemblers](#assemblers)
- [C Compilers](#c-compilers)
- [BASIC Compilers](#basic-compilers)
- [Emulators Used for Development](#emulators-used-for-development)

---

<a id="integrated-development-environments-ides"></a>

# Integrated Development Environments (IDEs)

### [C64 Studio](https://github.com/GeorgRottensteiner/C64Studio) *(Windows)*

A comprehensive integrated development environment dedicated to Commodore 64 software development. C64 Studio includes a built-in 6510 assembler, BASIC editor, project management, syntax highlighting, source navigation, debugging integration with VICE, disassembly support, and facilities for creating PRG, D64, T64, TAP, and CRT files. It supports assembly and BASIC development workflows and remains one of the most widely used Windows-based C64 IDEs.

### [CBM .prg Studio](https://www.ajordison.co.uk/) *(Windows)*

A Commodore-focused development environment that combines source editing, assembly language development, BASIC programming, project management, emulator integration, disk image handling, memory inspection, and build automation. It is designed to provide a complete development workflow for Commodore 64 software from within a single application.

### [Relaunch64](https://github.com/sjPlot/Relaunch64) *(Windows, Linux, macOS)*

A Java-based cross-platform IDE for Commodore 64 assembly language development. Relaunch64 provides project management, syntax highlighting, build automation, emulator launching, code navigation, configurable toolchains, and integration with assemblers such as ACME, Kick Assembler, 64tass, and others. It serves as a flexible frontend for modern C64 cross-development.

### [Retroc64](https://github.com/RetroC64/RetroC64) *(Windows)*

A modern Commodore 64 development environment intended to provide contemporary development workflows while targeting original Commodore hardware. It includes source editing, project management, build automation, debugging facilities, and emulator integration designed for both new and experienced C64 developers.

### [VS64](https://marketplace.visualstudio.com/items?itemName=rosc.vs64) *(Windows, Linux, macOS)*

A Visual Studio Code extension specifically designed for Commodore 64 development. VS64 provides project templates, build integration, source-level debugging, emulator integration, and support for common Commodore 64 toolchains including Kick Assembler, ACME, and cc65. It enables modern editor workflows while targeting Commodore hardware.

---

<a id="assemblers"></a>

# Assemblers

### [ACME Cross Assembler](https://sourceforge.net/projects/acme-crossass/) *(Windows, Linux, macOS, AmigaOS, DOS, RISC OS)*

One of the most widely used assemblers in the Commodore 64 development community. ACME supports the 6502, 6510, 65C02, and 65816 processor families and provides macros, conditional assembly, local labels, expression evaluation, pseudo-operations, and multiple output formats. It is commonly used for games, demos, utilities, and operating-system-level development.

### [Kick Assembler](https://www.theweb.dk/KickAssembler/Main.html#frontpage) *(Windows, Linux, macOS)*

A powerful Java-based assembler that has become a standard tool in modern Commodore 64 game and demoscene development. Kick Assembler offers advanced macro processing, scripting capabilities, compile-time calculations, structured programming constructs, resource generation functions, and automated build support. Its flexibility makes it suitable for projects ranging from small utilities to large commercial productions.

### [64tass](https://tass64.sourceforge.net/) *(Windows, Linux, macOS)*

A highly capable multi-pass assembler supporting the full 6502 processor family. Features include relocatable object generation, advanced macro facilities, conditional assembly, Unicode support, expression evaluation, and local scoping. It is often chosen for large-scale Commodore 64 software projects requiring sophisticated assembly language development.

### [Turbo Macro Pro X (TMPx)](https://turbo.style64.org/) *(Windows, Linux, macOS, FreeBSD, Solaris)*

A modern implementation of the Turbo Macro Pro assembler environment. TMPx maintains source compatibility with Turbo Macro Pro while supporting modern cross-development workflows. It provides macro assembly capabilities, project-oriented development, and integration with contemporary build environments.

---

<a id="c-compilers"></a>

# C Compilers

### [cc65](https://cc65.github.io/) *(Windows, Linux, macOS, BSD)*

The most widely used C compiler suite for Commodore 64 development. cc65 provides a complete development environment including a compiler, runtime libraries, assembler integration, linker support, and utilities required to build C-based Commodore 64 software. It remains the primary C toolchain used by many modern C64 projects.

### [Oscar64](https://github.com/drmortalwombat/oscar64) *(Windows, Linux, macOS)*

A modern optimizing C compiler focused on producing highly efficient machine code for the Commodore 64. Oscar64 targets performance-critical applications such as games and demos while providing a contemporary C development experience. It includes advanced optimisation techniques and close integration with assembly language code.

### [KickC](https://gitlab.com/camelot/kickc) *(Windows, Linux, macOS)*

A Commodore 64-oriented C compiler designed to generate highly optimized assembly output. KickC integrates closely with Kick Assembler and focuses on performance, memory efficiency, and direct access to Commodore 64 hardware. It is particularly popular among developers building games and demos.

### [llvm-mos](https://llvm-mos.org/) *(Windows, Linux, macOS)*

A modern LLVM-based compiler toolchain supporting the MOS 6502 processor family. It provides Clang compatibility, advanced optimisation capabilities, modern diagnostics, debugging support, and contemporary development workflows. Commodore 64 developers increasingly adopt llvm-mos when seeking modern compiler technology and tooling.

----

<a id="basic-compilers"></a>

# BASIC Compilers

### [XC=BASIC 3](https://xc-basic.net/doku.php) *(Windows, Linux, macOS)*

A modern compiled BASIC language designed specifically for Commodore 64 development. XC=BASIC compiles directly to native machine code and provides structured programming constructs, direct hardware access, inline assembly support, advanced language features, and significantly higher performance than interpreted BASIC. It is widely used for modern game and application development.

----

<a id="emulators-used-for-development"></a>

# Emulators Used for Development

### [VICE (Versatile Commodore Emulator)](https://vice-emu.sourceforge.io/) *(Windows, Linux, macOS)*

The reference emulator used throughout the Commodore 64 development community. VICE provides cycle-accurate emulation, debugging monitors, breakpoints, memory inspection, cartridge support, disk-drive emulation, REU support, profiling facilities, and integration with numerous development environments.

### [Hoxs64](https://hoxs64.net/) *(Windows)*

A highly accurate Commodore 64 emulator emphasizing faithful hardware behaviour. Hoxs64 includes advanced debugging facilities, breakpoint management, monitor functionality, memory inspection tools, hardware expansion support, and timing analysis features useful during software development and testing.

### [C64 Forever](https://www.c64forever.com/) *(Windows)*

A commercial Commodore 64 emulation package that combines licensed ROMs, emulator management, debugging capabilities, snapshot support, media management, and compatibility tools. It provides a complete testing environment for Commodore 64 software development.
