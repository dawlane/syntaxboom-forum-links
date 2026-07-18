# List of Sinclair ZX Spectrum and ZX Spectrum Next Development Tools

## Compression & Crunching Tools

This is is going to be the start of a list of useful links to various tools for programming Sinclair ZX Spectrum and ZX Spectrum Next Development home computers. If anyone adds some gems, then they will be added to this post, so people don't have to go through every post.

**NOTE:** Many of these sites linked here, have not been fully checked or validated for what contents they offer, and possibly in the future they may also be broken. Anyone using the links should remain vigilant to protect themselves from malicious software and sites through the use of internet security software and good judgement by not falling prey to sites that require the specific entry of personal information. The accuracy of the descriptions may also not be correct, and should be in many cases considered a work-in-progress.
If they don't appear to be what is advertised, or look suspicious.
Then PM an administrator so they can be removed, or updated with the correct information.  
**So use these links and any associated software from these sites at your own risk!**  

## Table of Contents

- [ZX0](#zx0-header)

---

<a id="zx0-header"></a>

## ZX0

**Official URL**
https://github.com/einar-saukas/ZX0

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
ZX0 is a modern lossless data compression system developed specifically for Z80-based retro-computing platforms, including the Sinclair ZX Spectrum family and ZX Spectrum Next. It combines high compression efficiency with extremely small and fast decompression routines, making it particularly well suited to memory-constrained software environments.

The compressor has become one of the most widely adopted compression standards in contemporary ZX Spectrum development. It is commonly used to compress graphics, level data, music resources, map data, executable overlays and other assets that would otherwise consume significant memory. Because the decompression routines are available in assembly language and designed for Z80 systems, ZX0 integrates naturally into both assembly and high-level language projects.

ZX0 is frequently used in commercial-quality homebrew games and demos where memory utilisation is a critical concern. Its balance of compression ratio, decompression speed and runtime footprint has made it a preferred successor to many older Spectrum compression systems.

**Development Features**

- Lossless data compression
- High compression ratios
- Fast decompression
- Small decompressor footprint
- Command-line operation
- Cross-platform support
- Automated build integration
- Multiple compression modes
- Retro-computing optimisation

**Supported File Formats**

- Generic binary data
- `.bin`
- Graphics assets
- Map data
- Music resources
- Executable resources

**Integration**

- **Assemblers**
  - SjASMPlus
  - PASMO
  - ZASM
- **Compilers**
  - z88dk
  - Boriel BASIC
  - SDCC
- **Emulators**
  - Compatible with all ZX Spectrum emulators
- **Frameworks & SDKs**
  - FASE
  - Rage1
  - Mike Dailly's ZX Spectrum Next ASM Framework
- **External tools**
  - Makefiles
  - Continuous integration systems
  - Custom asset pipelines

**Primary Purpose**  
A lossless compression system and decompression runtime for reducing memory and storage requirements in ZX Spectrum and ZX Spectrum Next software projects.

[Back to index](index.md)
