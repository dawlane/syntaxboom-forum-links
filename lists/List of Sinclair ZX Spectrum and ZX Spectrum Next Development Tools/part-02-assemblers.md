
# List of Sinclair ZX Spectrum and ZX Spectrum Next Development Tools

## Assemblers

This is is going to be the start of a list of useful links to various tools for programming Sinclair ZX Spectrum and ZX Spectrum Next Development home computers. If anyone adds some gems, then they will be added to this post, so people don't have to go through every post.

**NOTE:** Many of these sites linked here, have not been fully checked or validated for what contents they offer, and possibly in the future they may also be broken. Anyone using the links should remain vigilant to protect themselves from malicious software and sites through the use of internet security software and good judgement by not falling prey to sites that require the specific entry of personal information. The accuracy of the descriptions may also not be correct, and should be in many cases considered a work-in-progress.
If they don't appear to be what is advertised, or look suspicious.
Then PM an administrator so they can be removed, or updated with the correct information.  
**So use these links and any associated software from these sites at your own risk!**  

## Table of Contents

- [PASMO](#pasmo-header)
- [SjASMPlus](#sjasmplus-header)
- [WLA-DX](#wla-dx-header)
- [ZASM](#zasm-header)
- [Zeus](#zeus-header)

---

<a id="pasmo-header"></a>

## PASMO

**Official URL**
https://pasmo.speccy.org/

**Host Platforms**

- Windows
- Linux
- macOS

**Verified ZX Spectrum or ZX Spectrum Next Targets**

- ZX Spectrum 16K
- ZX Spectrum 48K
- ZX Spectrum 128K
- ZX Spectrum +2
- ZX Spectrum +2A/+2B
- ZX Spectrum +3

**Overview**  
PASMO is a portable Z80 cross-assembler designed for modern systems while targeting classic Zilog Z80-based machines. It has long been a popular choice within the ZX Spectrum development community due to its simplicity, reliability and compatibility with traditional Spectrum development workflows. PASMO supports the generation of binary files suitable for direct loading into ZX Spectrum software projects and is frequently used in build pipelines for retro software development.

The assembler focuses on standards-compliant Z80 assembly language development and provides support for macros, conditional assembly and symbol handling. Its lightweight design makes it particularly useful for automated build systems, command-line workflows and integration with external editors, IDEs and continuous integration environments.

**Development Features**

- Z80 cross-assembler
- Macro support
- Conditional assembly
- Include file support
- Symbol generation
- Listing file generation
- Command-line operation
- Portable cross-platform implementation
- Binary output generation

**Supported File Formats**

- `.asm`
- `.inc`
- `.bin`
- `.lst`
- `.sym`

**Integration**

- **Assemblers**
  - Standalone assembler
- **Compilers**
  - Can be used alongside z88dk and other compiler toolchains
- **Emulators**
  - Output compatible with ZX Spectrum emulators
- **Frameworks & SDKs**
  - Compatible with Spectrum development libraries and frameworks
- **External tools**
  - Makefiles and automated build systems

**Primary Purpose**  
A portable Z80 cross-assembler for building classic Sinclair ZX Spectrum assembly language software.  

---

<a id="sjasmplus-header"></a>

## SjASMPlus

**Official URL**
https://github.com/z00m128/sjasmplus

**Host Platforms**

- Windows
- Linux
- macOS

**Verified ZX Spectrum or ZX Spectrum Next Targets**

- ZX Spectrum 16K
- ZX Spectrum 48K
- ZX Spectrum 128K
- ZX Spectrum +2
- ZX Spectrum +2A/+2B
- ZX Spectrum +3
- ZX Spectrum Next

**Overview**  
SjASMPlus is one of the most widely used modern Z80 cross-assemblers for Sinclair ZX Spectrum and ZX Spectrum Next development. Originally derived from the SjASM assembler, it has evolved into a powerful and actively maintained tool that supports advanced assembly language workflows, large projects and modern build automation.

The assembler includes extensive support for macros, modules, structures, conditional assembly and device-specific features. It has become the de facto standard assembler for many ZX Spectrum Next projects due to its native support for Next-specific functionality, NEX file generation and modern development practices. Its broad adoption has led to extensive integration with IDEs, frameworks and community development resources.

**Development Features**

- Advanced macro system
- Conditional assembly
- Module support
- Structure support
- Repeat blocks
- Symbol export generation
- Listing file generation
- Device emulation directives
- ZX Spectrum Next support
- NEX file generation
- Snapshot generation
- Command-line build integration

**Supported File Formats**

- `.asm`
- `.inc`
- `.bin`
- `.lst`
- `.sym`
- `.tap`
- `.sna`
- `.nex`

**Integration**

- **Assemblers**
  - Standalone assembler
- **Compilers**
  - Frequently used with z88dk projects
- **Emulators**
  - CSpect
  - ZEsarUX
  - Fuse
- **Frameworks & SDKs**
  - FASE
  - Rage1
  - Mike Dailly's ZX Spectrum Next ASM Framework
- **External tools**
  - Continuous integration pipelines
  - Makefiles
  - Klive IDE

**Primary Purpose**  
A modern feature-rich Z80 cross-assembler for Sinclair ZX Spectrum and ZX Spectrum Next software development.  

---

<a id="wla-dx-header"></a>

## WLA-DX

**Official URL**
https://github.com/vhelin/wla-dx

**Host Platforms**

- Windows
- Linux
- macOS

**Verified ZX Spectrum or ZX Spectrum Next Targets**

- ZX Spectrum 16K
- ZX Spectrum 48K
- ZX Spectrum 128K
- ZX Spectrum +2
- ZX Spectrum +2A/+2B
- ZX Spectrum +3

**Overview**  
WLA-DX is a multi-platform macro assembler framework supporting numerous 8-bit and 16-bit processors, including the Z80 used by the Sinclair ZX Spectrum family. Although not exclusively focused on Spectrum development, it is capable of building ZX Spectrum software and is frequently selected by developers working across multiple retro platforms.

The project emphasises modular source organisation, linker-based workflows and large project support. This makes it particularly attractive for developers who prefer modern software engineering practices while targeting classic hardware platforms.

**Development Features**

- Z80 assembler support
- Macro language
- Object file generation
- Linker support
- Library support
- Conditional assembly
- Structured project organisation
- Cross-platform operation
- Large project support

**Supported File Formats**

- `.asm`
- `.inc`
- `.obj`
- `.lib`
- `.lst`
- `.sym`
- `.bin`

**Integration**

- **Assemblers**
  - wla-z80
- **Compilers**
  - External toolchain integration
- **Emulators**
  - Output compatible with ZX Spectrum emulators
- **Frameworks & SDKs**
  - Compatible with custom Spectrum frameworks
- **External tools**
  - wlalink
  - Automated build systems

**Primary Purpose**  
A linker-capable macro assembler framework supporting Z80 development for ZX Spectrum software projects.  

---

<a id="zasm-header"></a>

## ZASM

**Official URL**
https://k1.spdns.de/Develop/Projects/zasm/Distributions/

**Host Platforms**

- Windows
- Linux
- macOS

**Verified ZX Spectrum or ZX Spectrum Next Targets**

- ZX Spectrum 16K
- ZX Spectrum 48K
- ZX Spectrum 128K
- ZX Spectrum +2
- ZX Spectrum +2A/+2B
- ZX Spectrum +3

**Overview**  
ZASM is a mature Z80 macro assembler developed as part of a broader collection of Sinclair-related development tools. It provides a high-performance assembly environment with support for modern macro facilities, symbol handling and multiple output formats suitable for ZX Spectrum development.

The assembler is particularly useful for developers seeking a traditional command-line workflow while retaining support for advanced assembly constructs. Its efficient implementation and broad CPU support make it suitable for both Spectrum-specific projects and wider Z80 development work.

**Development Features**

- Z80 macro assembler
- Conditional assembly
- Macro support
- Include file support
- Symbol generation
- Listing generation
- Multiple output formats
- Command-line workflow
- Fast assembly performance

**Supported File Formats**

- `.asm`
- `.inc`
- `.bin`
- `.lst`
- `.sym`

**Integration**

- **Assemblers**
  - Standalone assembler
- **Compilers**
  - External toolchain integration
- **Emulators**
  - Output compatible with ZX Spectrum emulators
- **Frameworks & SDKs**
  - Compatible with Spectrum development frameworks
- **External tools**
  - Build automation systems

**Primary Purpose**  
A high-performance Z80 macro assembler suitable for classic ZX Spectrum assembly language development.  

---

<a id="zeus-header"></a>

## Zeus

**Official URL**
https://www.desdes.com/products/oldfiles/zeus.htm

**Host Platforms**

- Windows

**Verified ZX Spectrum or ZX Spectrum Next Targets**

- ZX Spectrum 48K
- ZX Spectrum 128K
- ZX Spectrum +2
- ZX Spectrum +2A/+2B
- ZX Spectrum +3

**Overview**  
Zeus is a long-established integrated Z80 development environment and assembler aimed at developers creating software for Z80-based systems, including the Sinclair ZX Spectrum family. It combines source editing, assembly, debugging support and project management into a single desktop application.

Historically popular among professional and enthusiast Z80 developers, Zeus provides a more integrated workflow than traditional command-line assemblers. Its extensive assembler capabilities and project-oriented design make it suitable for medium and large Spectrum software projects where organisation and productivity are important considerations.

**Development Features**

- Integrated source editor
- Z80 assembler
- Macro support
- Conditional assembly
- Project management
- Symbol browser
- Cross-reference generation
- Listing generation
- Build management
- Integrated development workflow

**Supported File Formats**

- `.asm`
- `.inc`
- `.bin`
- `.lst`
- `.sym`

**Integration**

- **Assemblers**
  - Built-in Zeus assembler
- **Compilers**
  - External toolchain support
- **Emulators**
  - Compatible with Spectrum emulator workflows
- **Frameworks & SDKs**
  - Compatible with assembly-based Spectrum frameworks
- **External tools**
  - Custom build pipelines

**Primary Purpose**  
An integrated Z80 assembler and development environment for creating Sinclair ZX Spectrum assembly language software.

[Back to index](index.md)
