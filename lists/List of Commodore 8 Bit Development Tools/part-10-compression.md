# List of Commodore 8 Bit Development Tools - Compression Tools

This is is going to be the start of a list of useful links to various tools for programming Commodore 8 Bit home computers. If anyone adds some gems, then they will be added to this post, so people don't have to go through every post.

**NOTE:** Many of these sites linked here, have not been fully checked or validated for what contents they offer, and possibly in the future they may also be broken. Anyone using the links should remain vigilant to protect themselves from malicious software and sites through the use of internet security software and good judgement by not falling prey to sites that require the specific entry of personal information. The accuracy of the descriptions may also not be correct, and should be in many cases considered a work-in-progress.
If they don't appear to be what is advertised, or look suspicious.
Then PM an administrator so they can be removed, or updated with the correct information.  
**So use these links and any associated software from these sites at your own risk!**  

## Table of contents

* [Exomizer](#exomizer-header)
* [Pucrunch](#pucrunch-header)
* [TSCrunch](#tscrunch-header)

---

<a id="exomizer-header"></a>

## Exomizer

**Official URL**
[https://bitbucket.org/magli143/exomizer/](https://bitbucket.org/magli143/exomizer/)

**Category**
Compression & Packing Utility

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

**Overview**
Exomizer is the de facto standard executable and data compressor used in modern Commodore development. It can compress complete PRG files into self-extracting executables (SFX) or compress individual assets for in-memory decompression. It provides excellent compression ratios while remaining relatively fast to decompress on 6502 hardware. It is the most widely used compressor in contemporary C64 game and demo production.

**Development Features**

* Self-extracting executable generation
* Raw data compression
* Memory-resident decompression
* Forward and backward decompression
* Command-line interface
* Build script friendly

**Supported Formats**

* PRG
* Raw binary
* SFX executables

**Integration**

* Kick Assembler
* 64tass
* ACME
* VS64
* Relaunch64
* VICE

**Primary Purpose**
Compress Commodore executables and assets.

---

<a id="pucrunch-header"></a>

## Pucrunch

**Official URL**
[https://github.com/mist64/pucrunch](https://github.com/mist64/pucrunch)

**Category**
Compression & Packing Utility

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

**Overview**
Pucrunch is one of the classic cross-platform Commodore compressors and remains actively used in modern development. It uses a hybrid LZ77/RLE algorithm and supports both executable compression and data compression. Although older than Exomizer, it is still popular because of its fast decompression routines and straightforward command-line interface.

**Development Features**

* Hybrid LZ77/RLE compression
* Executable crunching
* Data compression
* Self-extracting executables
* Command-line interface

**Supported Formats**

* PRG
* Raw binary

**Integration**

* Kick Assembler
* ACME
* 64tass
* VS64
* VICE

**Primary Purpose**
Compress Commodore programs and data.

---

<a id="tscrunch-header"></a>

## TSCrunch

**Official URL**
[https://github.com/tonysavon/TSCrunch](https://github.com/tonysavon/TSCrunch)

**Category**
Compression & Packing Utility

**Host Platforms**

* Windows
* Linux
* macOS

**Verified Commodore Targets**

* C64

**Overview**
TSCrunch is a modern byte-aligned LZ/RLE compressor developed by Antonio Savona (Piggy 18/RGCD). It was designed for high-speed in-memory decompression in games while also supporting creation of self-extracting Commodore 64 executables. It is increasingly used in new commercial-quality C64 software where decompression speed is as important as compression ratio.

**Development Features**

* Fast byte-aligned decompressor
* LZ + RLE compression
* SFX executable generation
* Asset compression
* Command-line utility

**Supported Formats**

* PRG
* Raw binary

**Integration**

* Modern assembly toolchains
* VICE
* Build automation

**Primary Purpose**
Fast compression for games and asset loading.
