# List of Amstrad CPC Development Tools

This is is going to be the start of a list of useful links to various game libraries and game render engines. If anyone adds some gems, then they will be added to this post, so people don't have to go through every post.

**NOTE:** Many of these sites linked here, have not been fully checked or validated for what contents they offer, and possibly in the future they may also be broken. Anyone using the links should remain vigilant to protect themselves from malicious software and sites through the use of internet security software and good judgement by not falling prey to sites that require the specific entry of personal information. The accuracy of the descriptions may also not be correct, and should be in many cases considered a work-in-progress.
If they don't appear to be what is advertised, or look suspicious.
Then PM an administrator so they can be removed, or updated with the correct information.  
**So use these links and any associated software from these sites at your own risk!**  

## Index

- [Assemblers](#assemblers)
- [Cross-Compilers & High-Level Languages](#compilers)
- [Frameworks & SDKs](#framewprks-and-sdks)
- [Emulators](#emulators)
- [Bitmap Editors](#bitmap-editors)
- [AY Music Editors](#aya-music-editors-cpc)
- [Disk & Media Utilities](#disk-and-media-utilities)

<a id="integrated-development-environments-ides"></a>

## Integrated Development Environments (IDEs)

----

<a id="assemblers"></a>

## Assemblers

[PASMO](https://pasmo.speccy.org/) (*Windows, Linux, macOS*)  
A cross-platform Z80 assembler supporting macro processing, conditional assembly, symbol generation, and multiple output formats. PASMO is frequently used for smaller Amstrad CPC projects and educational development workflows due to its simplicity and portability.

[RASM](https://github.com/EdouardBERGE/RASM) (*Windows, Linux, macOS*)  
A modern high-performance Z80 assembler developed with Amstrad CPC development in mind. RASM provides advanced macro facilities, local labels, structures, conditional assembly, and fast build performance. It is widely used in contemporary CPC game development and demoscene productions.

[SjASMPlus](https://github.com/z00m128/sjasmplus) (*Windows, Linux, macOS*)  
One of the most actively maintained Z80 assemblers available today. SjASMPlus provides namespaces, modules, advanced macro processing, conditional assembly, include management, and extensive automation features. It is commonly used for larger CPC software projects.

----

<a id="compilers"></a>

## Cross-Compilers & High-Level Languages

[Turbo Rascal Syntax Error (TRSE)](https://lemonspawn.com/turbo-rascal-syntax-error-expected-but-begin/) (*Windows, Linux, macOS*)  
A Pascal-inspired cross-development environment featuring a compiler, IDE, resource editors, asset tools, and build system. TRSE supports the Amstrad CPC and generates optimized assembly code for the target machine. It includes built-in editors for sprites, maps, characters, and other game-development assets.

[ugBASIC](https://ugbasic.iwashere.eu/) *(Windows, Linux, macOS)*  
A modern BASIC cross-compiler targeting numerous classic computers including the Amstrad CPC. ugBASIC compiles structured BASIC source code into native machine code and provides access to CPC graphics, sound, input, and storage facilities through a high-level programming model.

[z88dk](https://www.z88dk.org/) (*Windows, Linux, macOS*)  
A comprehensive Z80 development kit that includes a C compiler, libraries, runtime support, linkers, assemblers, and Amstrad CPC target support. z88dk provides a complete workflow for building native CPC applications and is widely used for both CPC-exclusive and multi-platform Z80 software projects. Its extensive libraries and tooling make it one of the most important high-level language environments in the CPC ecosystem.

----

<a id="framewprks-and-sdks"></a>

## Frameworks & SDKs

[CPCRSLib](https://sourceforge.net/projects/cpcrslib/) (*Windows, Linux, macOS*)  
A reusable software library for Amstrad CPC game and application development. CPCRSLib provides routines for graphics, sprites, tilemaps, keyboard handling, joystick input, sound, screen management, memory operations, and other common development tasks. It is designed to reduce the amount of low-level boilerplate code required when building CPC software and can be integrated into modern Z80 development workflows.

[CPCTelera](https://lronaldo.github.io/cpctelera/) (*Windows, Linux, macOS*)  
The most widely adopted modern game-development framework and SDK for the Amstrad CPC. CPCtelera provides a complete cross-development environment including build tools, libraries, hardware abstraction layers, sprite routines, tile systems, memory management, firmware access, sound support, examples, documentation, and project templates. It is commonly regarded as the standard modern SDK for CPC game development.

[CPCTools](https://github.com/cpcsdk/cpctools) (*Windows, Linux, macOS*)  
A collection of development tools and utilities intended to support modern Amstrad CPC software production. CPCTools provides build support, packaging tools, asset handling utilities, and project infrastructure that can be integrated into larger CPC development workflows. It represents the modern continuation of tooling that originated in the CPCSDK ecosystem.

----

<a id="emulators"></a>

## Emulators

[ACE-DL](https://roudoudou.com/ACE-DL/) (*Windows, Linux, macOS, Raspberry Pi*)  
A modern, Amstrad CPC and CPC Plus emulator. ACE-DL emphasizes hardware accuracy while providing an extensive suite of developer-oriented tools, including breakpoints, memory exploration, execution tracing, register inspection, graphics inspection, and hardware visualization. It also integrates closely with the RASM assembler, making it particularly well suited to assembly-language development and debugging. Despite these powerful development features, its primary purpose is emulation, so it is classified as an emulator rather than an IDE.

[Arnold](https://github.com/rofl0r/arnold) (*Windows, Linux*)  
One of the longest-running Amstrad CPC emulators. Arnold provides accurate CPC emulation, support for multiple CPC models, disk image handling, cartridge support, and development-oriented features useful for testing software across different machine configurations.

[Caprice32](https://github.com/ColinPitrat/caprice32) (*Windows, Linux, macOS*)  
A mature Amstrad CPC emulator supporting CPC 464, 664, and 6128 systems. Caprice32 provides disk image support, hardware emulation, configurable peripherals, and cross-platform operation.

[Retro Virtual Machine](https://www.retrovirtualmachine.org/) (*Windows, Linux, macOS*)  
A modern emulator supporting multiple classic computer systems, including the Amstrad CPC. It offers media management, machine configuration, debugging facilities, and a modern user experience suitable for development and testing.

[WinAPE](https://www.winape.net/) (*Windows*)  
The most widely used Amstrad CPC development emulator. WinAPE combines emulation, debugging, assembly, machine-code monitoring, memory inspection, breakpoint handling, and disk-image management in a single integrated environment.

----

## Bitmap Editors

<a id="bitmap-editors"></a>

[GrafX2](http://grafx2.chez.com/) (*Windows, Linux, macOS*)  

A mature, cross-platform pixel art editor inspired by Deluxe Paint and designed for creating graphics for classic computer and console systems. GrafX2 includes native support for Amstrad CPC palettes and picture formats, including SCR, CM5, GraphOS (GO1/GO2), and SymbOS SGX files, making it one of the most capable modern graphics editors for CPC development. It provides layers, animation support, palette management, scripting, and numerous drawing tools suitable for producing sprites, title screens, loading screens, fonts, and other bitmap assets. Although it supports many retro platforms, its comprehensive Amstrad CPC format support makes it a valuable tool in modern CPC development workflows.

----

<a id="aya-music-editors-cpc"></a>

## AYA Music Editors

[Arkos Tracker](https://www.julien-nevo.com/arkostracker/) (*Windows, Linux, macOS*)  

Arkos Tracker is the de facto standard music tracker for modern Amstrad CPC development. Developed by Julien "Targhan" Névo, it is a cross-platform tracker for composing music and sound effects targeting the AY-3-8912 and YM2149 sound chips. It supports advanced pattern editing, instrument design, sample playback, MIDI import, multiple replay routines, hardware playback, and exports music as assembly source or binary data for straightforward integration into Amstrad CPC software. The latest generation, Arkos Tracker 3, is an actively developed rewrite that maintains compatibility with earlier projects while modernising the user interface and workflow.

----

<a id="disk-and-media-utilities"></a>

## Disk & Media Utilities

[CPCDiskXP](https://www.cpcmania.com/cpcdiskxp/cpcdiskxp.htm) (*Windows*)  
A Windows-based utility for creating, editing, reading, and writing Amstrad CPC disk images (DSK format). CPCDiskXP supports standard and extended DSK formats, file injection and extraction, AMSDOS headers, sector-level inspection, and direct floppy disk writing. It also includes command-line options for automated build workflows, making it useful in modern CPC development pipelines for packaging and deployment.

## iDSK

[iDSK](https://github.com/cpcsdk/idsk) (*Windows, Linux, macOS*)  
A command-line tool for managing Amstrad CPC disk images. iDSK allows developers to add, extract, delete, and list files within DSK and EDSK images. It is widely used in automated build systems for CPC software projects and integrates well with assembler and framework-based toolchains.
