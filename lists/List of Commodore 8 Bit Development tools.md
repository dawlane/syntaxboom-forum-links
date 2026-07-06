# List of Commodore 8 Bit Development Tools

This is is going to be the start of a list of useful links to various game libraries and game render engines. If anyone adds some gems, then they will be added to this post, so people don't have to go through every post.

**NOTE:** Many of these sites linked here, have not been fully checked or validated for what contents they offer, and possibly in the future they may also be broken. Anyone using the links should remain vigilant to protect themselves from malicious software and sites through the use of internet security software and good judgement by not falling prey to sites that require the specific entry of personal information. The accuracy of the descriptions may also not be correct, and should be in many cases considered a work-in-progress.
If they don't appear to be what is advertised, or look suspicious.
Then PM an administrator so they can be removed, or updated with the correct information.  
**So use these links and any associated software from these sites at your own risk!**  

## Index

- [Integrated Development Environments (IDEs)](#integrated-development-environments-ides)
- [Assemblers](#assemblers)
- [Cross-Compilers & High-Level Languages](#compilers)
- [Debuggers and Analysis Tools](#debuggers-and-analysis-tools)
- [Emulators](#emulators)
- [Sprite Editors](#sprite-editors)
- [SID Music Editors](#sid-music-editors)
- [Disk & Media Utilities](#disk-and-media-utilities)
- [Bitmap & Graphics Editors](#bitmap-and-grahics-editors)

<a id="integrated-development-environments-ides"></a>

## Integrated Development Environments

[C64 IDE](https://gopherbrokesoftware.com/) (*macOS*)  
A native macOS development environment for Commodore 64 software development. C64 IDE integrates editing, project management, compilation workflows, debugging facilities, and emulator integration through VirtualC64. The environment is designed specifically for macOS developers who want a modern native experience when creating Commodore software.

[C64 Studio](https://www.georg-rottensteiner.de/en/c64.html) (*Windows*)  
A comprehensive integrated development environment dedicated to Commodore 64 software development. C64 Studio includes a built-in 6510 assembler, BASIC editor, project management, syntax highlighting, source navigation, VICE integration, debugging support, disassembly tools, and facilities for creating PRG, D64, T64, TAP, and CRT files. It is one of the most widely used all-in-one C64 development environments.

[CBM .prg Studio](https://www.ajordison.co.uk/) (*Windows*)  
A full-featured Commodore development environment that combines assembly language programming, BASIC development, project management, emulator integration, disk image manipulation, memory inspection, and build automation. It is designed to streamline the entire Commodore software development process from a single application.

[Relaunch64](https://github.com/sjPlot/Relaunch64) (*Windows, Linux, macOS*)  
A Java-based cross-platform IDE for Commodore assembly language development. Relaunch64 provides syntax highlighting, project management, build automation, emulator launching, source navigation, configurable toolchains, and integration with assemblers such as ACME, Kick Assembler, 64tass, and TMPx. It serves as a flexible frontend for modern cross-development workflows.

[RetroC64](https://retroc64.github.io/) (*Windows*)  
A modern development environment focused on Commodore 64 software creation. RetroC64 provides project management, source editing, build automation, emulator integration, debugging support, and workflows intended to be familiar to developers accustomed to contemporary programming environments.

[VS64](https://marketplace.visualstudio.com/items?itemName=rosc.vs64) (*Windows, Linux, macOS*)  
A Visual Studio Code extension specifically designed for Commodore development. VS64 supports project templates, build integration, source-level debugging, emulator integration, and workflows for ACME, Kick Assembler, cc65, and other common Commodore development tools. It enables developers to use a modern editor while targeting original Commodore hardware.

----

<a id="assemblers"></a>

## Assemblers

[64tass](https://tass64.sourceforge.net/) (*Windows, Linux, macOS*)  
A highly capable multi-pass assembler supporting the complete 6502 processor family, including the Commodore 64's 6510 processor. 64tass provides relocatable object generation, advanced macro facilities, local scopes, conditional assembly, Unicode support, expression evaluation, structured data definitions, and extensive compatibility features. It is frequently used for larger Commodore projects that require modular source code and sophisticated build processes.

[ACME Cross Assembler](https://sourceforge.net/projects/acme-crossass/) and [Sources](https://github.com/meonwax/acme) (*Windows, Linux, macOS, AmigaOS, DOS, RISC OS*)  
One of the most popular assemblers in the Commodore development community. ACME supports the 6502, 6510, 65C02, and 65816 processor families and provides macros, conditional assembly, local labels, expression evaluation, pseudo-operations, and multiple output formats. Its speed, simplicity, and long-standing reliability have made it a common choice for games, demos, utilities, and operating-system-level development.

[Asm6502](https://github.com/xoofx/Asm6502) (*Windows, Linux, macOS*)  
A modern C# library providing a complete 6502/6510 development toolkit that combines a fluent strongly-typed assembler, disassembler, and a cycle-accurate CPU emulator. It supports all standard 6502 instructions as well as undocumented opcodes, and allows programs to be assembled, inspected, and executed directly in a managed runtime environment. The library includes a pluggable 64KB memory bus model, step-based execution, and accurate cycle timing suitable for hardware-precise simulation. It is primarily used in tooling, emulator development, and advanced experimentation environments rather than as a standalone cross-assembler, and is also integrated into projects such as RetroC64 for code generation and analysis workflows.

[Kick Assembler](https://www.theweb.dk/KickAssembler/Main.html#frontpage) (*Windows, Linux, macOS*)  
A powerful Java-based assembler widely used throughout the modern Commodore 64 game-development and demoscene communities. Kick Assembler offers advanced macro processing, scripting capabilities, compile-time calculations, structured programming constructs, resource generation functions, built-in data manipulation features, and automated build support. Its flexibility allows complex projects to be built from a single integrated source tree.

[Ophis](https://michaelcmartin.github.io/Ophis/) (*Windows, Linux, macOS*)  
A portable cross-assembler for the 6502 processor family emphasizing readable source code and flexible output generation. Ophis has been used successfully for Commodore 64 software as well as other 6502-based systems. It is available as standalone installers and through Python package management, making it easy to integrate into modern development environments.

[Turbo Macro Pro X (TMPx)](https://turbo.style64.org/) (*Windows, Linux, macOS, FreeBSD, Solaris*)  
A modern implementation of the classic Turbo Macro Pro assembler environment. TMPx preserves compatibility with Turbo Macro Pro source code while supporting contemporary cross-development workflows. Features include macro assembly, project-oriented development, conditional assembly, modern build integration, and support for producing Commodore 64 executable formats.

[XA](https://github.com/fachat/xa65) (*Windows, Linux, macOS, BSD*)  
A fast, portable multi-pass cross-assembler supporting the 6502, 6510, 65C02, R65C02, and 65816 processor families. XA includes a C-like preprocessor, relocatable object support, flexible expression syntax, scoped labels, and multiple output formats. It remains actively maintained and is suitable for Commodore 64 cross-development.

----

<a id="compilers"></a>

## Cross-Compilers & High-Level Languages

[cc65](https://cc65.github.io/) (*Windows, Linux, macOS, BSD*)  
The most widely used C compiler suite for Commodore 64 development. cc65 provides a complete cross-development toolchain including a C compiler, runtime libraries, assembler integration, linker support, debugging utilities, and project-building tools. It supports modular development, mixed C and assembly-language programming, and remains the standard choice for many modern Commodore software projects.

[KickC](https://gitlab.com/camelot/kickc) (*Windows, Linux, macOS*)  
A C compiler designed specifically for Commodore development. KickC focuses on generating highly optimized assembly output while retaining the productivity advantages of the C language. The compiler integrates closely with Kick Assembler and provides direct access to Commodore hardware features, making it particularly popular for game and demo development.

[llvm-mos](https://llvm-mos.org/) (*Windows, Linux, macOS*)  
A modern LLVM-based compiler toolchain targeting MOS 6502-family processors. llvm-mos brings Clang compatibility, advanced optimization passes, modern diagnostics, debugging support, and contemporary development workflows to Commodore development. Developers familiar with modern C and C++ ecosystems often choose llvm-mos because it provides many of the conveniences found in current desktop compiler environments.

[Oscar64](https://github.com/drmortalwombat/oscar64) (*Windows, Linux, macOS*)  
A modern optimizing C compiler focused on generating efficient machine code for Commodore systems. Oscar64 is designed for performance-critical software such as games, demos, and hardware-intensive applications. It provides aggressive optimization strategies, assembly-language integration, and a development experience tailored to the limitations and capabilities of Commodore hardware.

[Turbo Rascal Syntax Error (TRSE)](https://lemonspawn.com/turbo-rascal-syntax-error-expected-but-begin/) (*Windows, Linux, macOS*)  
A Pascal-inspired cross-development suite featuring a compiler, integrated development environment, resource editors, sprite editors, map editors, asset tools, and project management facilities. TRSE generates optimized 6502 assembly code and supports the Commodore 64 as a primary target platform.

[ugBASIC](https://ugbasic.iwashere.eu/) (*Windows, Linux, macOS*)  
A modern BASIC cross-compiler supporting the Commodore 64 and numerous other classic computers. Programs are compiled into native machine code while providing high-level access to graphics, sprites, sound, storage, and input hardware.

[XC=BASIC 3](https://xc-basic.net/doku.php?id=v3:start) (*Windows, Linux, macOS*)  
A modern compiled BASIC language designed specifically for Commodore 8-bit development. XC=BASIC compiles directly to native machine code rather than relying on an interpreter, allowing programs to achieve performance levels comparable to assembly-language implementations in many situations. The language provides structured programming constructs, procedures, local variables, modules, direct hardware access, inline assembly support, and integration with modern cross-development workflows. It has become one of the most widely adopted BASIC-based development systems for contemporary Commodore 64 game and application development.

----

<a id="debuggers-and-analysis-tools"></a>

## Debuggers & Analysis Tools

[Retro Debugger](https://github.com/slajerek/RetroDebugger) (*Windows, Linux, macOS*)  
An advanced Commodore debugging and analysis environment that combines emulation with powerful software-development tools. Retro Debugger provides cycle-level debugging, source-level debugging, breakpoint management, memory visualization, raster timing analysis, SID inspection, sprite analysis, profiling, execution tracing, watch expressions, and code navigation. It is designed specifically for Commodore 64 development and is particularly useful when investigating timing-sensitive bugs, raster effects, hardware interactions, and performance bottlenecks.

----

<a id="emulators"></a>

## Emulators

[CCS64](https://www.ccs64.com/) (*Windows*)  
One of the longest-running Commodore 64 emulators still under active development. CCS64 provides highly compatible emulation of the Commodore 64, 1541 disk drives, cartridges, tape systems, joysticks, mice, and numerous peripherals. Recent versions include reverse execution capabilities, enhanced time-travel debugging, improved cartridge support, and ongoing compatibility improvements. CCS64 is frequently used for software testing and regression analysis due to its mature and stable emulation core.

[C64 Forever](https://www.c64forever.com/) (*Windows*)  
A commercial Commodore emulation environment that combines licensed Commodore ROMs, emulator management, debugging support, media management, snapshots, and compatibility tools. C64 Forever provides a polished user experience and an integrated testing environment suitable for both hobbyist and professional Commodore software developers.

[Denise](https://sourceforge.net/projects/deniseemu/) (*Windows, macOS*)  
A modern cycle-accurate Commodore emulator designed with a strong focus on timing accuracy, low latency, and developer-oriented features. Denise includes an integrated debugger and disassembler, RunAhead latency reduction, rewind support, PAL and CRT emulation, extensive cartridge support, REU and GeoRAM emulation, EasyFlash compatibility, multiple drive types, and advanced hardware expansion support. Its accuracy makes it particularly valuable when developing timing-sensitive software, demos, and raster effects.

[Hoxs64](https://hoxs64.net/) (*Windows*)  
A highly accurate Commodore 64 emulator emphasizing faithful hardware behaviour and precise timing characteristics. Hoxs64 includes advanced machine-language monitor functionality, breakpoints, memory inspection, timing analysis, hardware expansion support, and extensive debugging capabilities. It is often used to validate software behaviour against real hardware expectations.

[VICE (Versatile Commodore Emulator)](https://vice-emu.sourceforge.io/) (*Windows, Linux, macOS*)  
The reference emulator used throughout much of the Commodore development community. VICE supports the Commodore 64, C128, VIC-20, PET, Plus/4, CBM-II, and other Commodore systems. It provides cycle-accurate emulation, machine-language monitors, breakpoints, watchpoints, memory inspection, cartridge support, drive emulation, REU support, networking features, remote debugging capabilities, and integration with many modern Commodore development environments.

----

<a id="character-map-and-tile-editors"></a>

## Character, Map & Tile Editors

[CharPad](https://subchristsoftware.itch.io/charpad-c64-pro) (*Windows*)  
A professional Commodore 64 character set and tile-map editor widely used in modern game development. CharPad allows creation and management of character graphics, tile-based maps, screen layouts, scrolling environments, and reusable graphical assets. It supports multicolour character modes, advanced attribute control, and direct export into formats suitable for assembly and C toolchains. It is one of the most established tools for structured C64 world-building and level design.

[Petmate](https://github.com/nurpax/petmate) (*Windows, Linux, macOS*)  
A modern PETSCII art and screen editor designed for Commodore 64 development. Petmate allows creation of text-mode graphics, menus, title screens, and decorative PETSCII artwork using a grid-based editor with Commodore character support. It provides export formats compatible with common 6502 assembly toolchains such as ACME, Kick Assembler, and 64tass, making it a practical tool for integrating text-mode visuals directly into software projects.

----

<a id="sprite-editors"></a>

## Sprite Editors

[SpriteMate](https://www.spritemate.com/) (*Web Browser*)  
A modern browser-based Commodore 64 sprite editor supporting multicolour and single-colour sprite creation, layered editing, animation frames, palette constraints, and real-time preview. SpriteMate runs entirely in the browser, making it cross-platform by design. It supports exporting sprite data in multiple formats compatible with common Commodore 64 assemblers and development workflows, and is widely used for quick iteration in game and demo asset creation.

[SpritePad](https://subchristsoftware.itch.io/spritepad-c64-pro) (*Windows*)  
A dedicated Commodore 64 sprite creation and editing tool used extensively in modern game development. SpritePad supports multicolour sprite design, animation sequencing, sprite bank management, and export to assembly and C-compatible formats. It is designed to integrate cleanly into contemporary Commodore development pipelines and is one of the most established sprite editors for professional C64 production.

----

<a id="sid-music-editors"></a>

## SID Music Editors

[GoatTracker 2](https://sourceforge.net/projects/goattracker2/) and [Sources](https://github.com/leafo/goattracker2) (*Windows, Linux, macOS*)  
A widely used SID music tracker for Commodore 64 development. GoatTracker 2 allows composers to create multi-channel SID music using pattern-based sequencing, instrument design, and effect programming. It supports detailed control over SID chip parameters, including waveform manipulation, filter usage, and modulation techniques. The tool exports music in formats suitable for integration into Commodore 64 games, demos, and applications, and remains one of the most established modern SID composition tools.

[SID Factory II](https://github.com/Chordian/sidfactory2) (*Windows, Linux, macOS*)  
A modern SID music creation environment designed specifically for Commodore 64 audio development. SID Factory II provides an intuitive tracker interface, instrument editing, effect control, and sequencing tools tailored to the SID chip’s capabilities. It supports exporting music data for integration into assembly-based and cross-development workflows, making it suitable for both hobbyist and professional Commodore audio production.

----

<a id="disk-and-media-utilities"></a>

## Disk & Media Utilities

[CBM Disk Editor](https://d64.sannic.nl/) (*Web Browser*)  
A modern browser-based tool for inspecting and manipulating Commodore disk and tape images. It supports a wide range of formats including D64, D71, D81, D80, D82, G64, T64, TAP, and CMD-native images. Features include file browsing, PETSCII viewing, BASIC program inspection, 6502 disassembly, graphics preview, archive extraction, and disk integrity checking. It is designed for both analysis and development workflows involving Commodore file systems.

[DirMaster](https://style64.org/dirmaster) (*Windows*)  
A dedicated Commodore disk image editor used for creating, modifying, and managing D64, D71, and D81 disk images. DirMaster provides a graphical file browser for disk contents, supports file import/export between host systems and Commodore images, and allows direct editing of directory structures. It is widely used in Commodore development pipelines for preparing distribution disks and testing software layouts.

----

<a id="bitmap-and-grahics-editors"></a>

## Bitmap & Graphics Editors

[Multipaint](http://multipaint.kameli.net/) (*Windows, Linux, macOS*)  
A cross-platform graphics editor designed for classic computer graphics formats. Multipaint supports Commodore 64 bitmap modes, multicolor graphics, palette restrictions, and export formats commonly used in game and demo development.

[png2c64](https://png2c64.app/) (*Web Browser*)  
A browser-based conversion tool that transforms modern PNG images into Commodore 64-compatible graphics data. It handles palette reduction, multicolour conversion constraints, and output formatting suitable for assembly and C-based development workflows. The tool is commonly used as a bridge between modern digital artwork pipelines and Commodore 64 hardware limitations.
