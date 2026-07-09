# List of Commodore 8 Bit Development Tools - Bitmap, Map, Character & Sprite Editors

This is is going to be the start of a list of useful links to various game libraries and game render engines. If anyone adds some gems, then they will be added to this post, so people don't have to go through every post.

**NOTE:** Many of these sites linked here, have not been fully checked or validated for what contents they offer, and possibly in the future they may also be broken. Anyone using the links should remain vigilant to protect themselves from malicious software and sites through the use of internet security software and good judgement by not falling prey to sites that require the specific entry of personal information. The accuracy of the descriptions may also not be correct, and should be in many cases considered a work-in-progress.
If they don't appear to be what is advertised, or look suspicious.
Then PM an administrator so they can be removed, or updated with the correct information.  
**So use these links and any associated software from these sites at your own risk!**  

## Table of contents

* [arcPaint64](#arcpaint64-header)
* [ALBERT](#albert-header)
* [Master of Sprites](#master-of-sprites-header)
* [OpenSprite](#opensprite-header)
* [Petmate](#petmate-header)
* [Petsciiator](#petsciiator-header)
* [CharPad C64 Pro](#charpad-c64-pro-header)
* [SpritePad C64 Pro](#spritepad-c64-pro-header)

---

<a id="arcpaint64-header"></a>

## arcPaint64

**Official URL**
https://www.doussis.com/arcpaint64/

**Category**
Bitmap Editor

**Host Platforms**

* Windows
* Linux
* macOS

**Verified Commodore Targets**

* C64

**Overview**__
arcPaint64 is a modern cross-platform pixel art editor designed specifically for Commodore 64 graphics. It provides a native drawing environment that understands VIC-II bitmap constraints instead of relying solely on post-processing conversion. The editor supports C64 bitmap creation, editing of native PRG graphics files, and workflows aimed at artists producing games, demos and digital artwork. Recent releases have introduced improved PRG importing, faster drawing operations and general workflow improvements.

**Development Features**

* Native Commodore 64 bitmap editing
* Pixel-level editing
* PRG import and export
* VIC-II palette support
* Drawing tools
* Shape tools
* Zoom and editing aids
* Cross-platform desktop application

**Supported Formats**

* PRG
* Native project files
* Bitmap graphics

**Integration**

* VICE
* Kick Assembler
* Graphics production workflows

**Primary Purpose**
Native Commodore 64 bitmap artwork creation and editing.

---

<a id="albert-header"></a>

## ALBERT

**Official URL**
https://www.albertpixels.com/

**Category**
Bitmap Editor

**Host Platforms**

* Windows
* Linux
* macOS

**Verified Commodore Targets**

* C64

**Overview**__
ALBERT is an advanced cross-development pixel art editor for creating **extended-border Commodore 64 graphics**. It is specifically designed to produce images that extend beyond the normal 320×200 display area by combining bitmap graphics with sprites, enabling artists to create presentation-quality images without requiring custom programming. In addition to manual editing, ALBERT can import PNG images using several dithering algorithms, provides colour-curve adjustment tools, maintains an effectively unlimited undo/redo history, and includes Lua scripting for automating drawing operations. Projects can also be exported as timelapse sequences documenting the creation process.

**Development Features**

* Native extended-border C64 image editor
* Bitmap drawing tools
* Sprite-assisted border graphics
* PNG image conversion
* Multiple dithering algorithms

  * Nearest colour
  * Floyd–Steinberg
  * Bayer ordered dithering
* Weighted colour matching
* Colour curve adjustments
* Lua scripting interface
* Unlimited undo/redo history
* Project timelapse export
* Cross-platform GUI

**Supported Formats**

* PNG
* ALBERT project files
* Extended C64 bitmap graphics
* Timelapse PNG export

**Integration**

* VICE
* Modern graphics workflows
* Lua scripting
* Asset production pipelines

**Primary Purpose**
Professional creation of extended-border Commodore 64 artwork using integrated bitmap, sprite and scripting workflows.

---

<a id="master-of-sprites-header"></a>

## Master of Sprites

**Official URL**
https://tstamborski.itch.io/master-of-sprites 

**Source Code**
https://github.com/tstamborski/master-of-sprites 

**Category**
Sprite Editor

**Host Platforms**

* Windows
* Linux
* macOS

**Verified Commodore Targets**

* C64

**Overview (Detailed)**
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

## OpenSprite

**Official URL**
https://github.com/jowin202/OpenSprite

**Category**
Sprite Editor

**Host Platforms**

* Windows
* Linux
* macOS

**Verified Commodore Targets**

* C64

**Overview (Detailed)**
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

## Petmate

**Official URL**
https://nurpax.github.io/petmate/

**Source Code**
https://github.com/nurpax/petmate

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

**Overview (Detailed)**
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

<a id="petsciiator-header"></a>

## Petsciiator

**Official URL**
https://github.com/EgonOlsen71/petsciiator

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

**Overview (Detailed)**
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

<a id="charpad-c64-pro-header"></a>

## CharPad C64 Pro

**Official URL**
https://subchristsoftware.itch.io/charpad-c64-pro

**Category**
Character & Map Editor

**Host Platforms**

* Windows

**Verified Commodore Targets**

* C64

**Overview (Detailed)**
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

## SpritePad C64 Pro

**Official URL**
https://subchristsoftware.itch.io/spritepad-c64-pro

**Category**
Sprite Editor

**Host Platforms**

* Windows

**Verified Commodore Targets**

* C64

**Overview (Detailed)**
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
