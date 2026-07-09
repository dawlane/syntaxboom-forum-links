# List of Commodore 8 Bit Development Tools - Asset Conversion Tools

This is is going to be the start of a list of useful links to various game libraries and game render engines. If anyone adds some gems, then they will be added to this post, so people don't have to go through every post.

**NOTE:** Many of these sites linked here, have not been fully checked or validated for what contents they offer, and possibly in the future they may also be broken. Anyone using the links should remain vigilant to protect themselves from malicious software and sites through the use of internet security software and good judgement by not falling prey to sites that require the specific entry of personal information. The accuracy of the descriptions may also not be correct, and should be in many cases considered a work-in-progress.
If they don't appear to be what is advertised, or look suspicious.
Then PM an administrator so they can be removed, or updated with the correct information.  
**So use these links and any associated software from these sites at your own risk!**  

## Table of contents

* [c64img](#c64img-header)
* [png2c64](#png2c64-header)
* [png2prg](#png2prg-header)
* [png2spd](#png2spd-header)
* [RetroPixels+](#retropixels)

---

<a id="c64img-header"></a>

## c64img

**Official URL**
https://github.com/elysium64/c64img

**Category**
Asset Conversion Tool

**Host Platforms**

* Windows
* Linux
* macOS

**Verified Commodore Targets**

* C64

**Overview (Detailed)**
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

<a id="png2c64-header"></a>

## png2c64

**Official URL**
https://png2c64.app/

**Source Code**
https://github.com/tinic/png2c64

**Category**
Bitmap Conversion Tool

**Host Platforms**

* Windows
* Linux
* macOS

**Verified Commodore Targets**

* C64

**Overview (Detailed)**
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


---

<a id="png2prg-header"></a>

## png2prg

**Official URL**
https://github.com/staD020/png2prg

**Category**
Asset Conversion Tool

**Host Platforms**

* Windows
* Linux
* macOS

**Verified Commodore Targets**

* C64

**Overview**__
png2prg is one of the most capable modern image conversion tools available for Commodore 64 development. It converts modern PNG, GIF and JPEG images directly into C64-compatible graphics and executable PRG files. The converter automatically determines the optimal palette, colour assignments and graphics mode for the source image, significantly reducing the manual work normally required to prepare artwork for the VIC-II.

Unlike many earlier conversion utilities, png2prg supports numerous C64 graphics modes including bitmap, character, PETSCII, Extended Colour Mode (ECM) and sprite graphics. It can also generate display programs, animation sequences and optionally include SID music playback. The project is implemented in Go, making it portable across all major desktop operating systems and suitable for automated asset pipelines.

**Development Features**

* PNG, GIF and JPEG conversion
* Automatic palette optimisation
* Automatic graphics mode selection
* Hires bitmap conversion
* Multicolour bitmap conversion
* Character mode conversion
* PETSCII conversion
* Extended Colour Mode (ECM)
* Sprite conversion
* Animation support
* Optional display program generation
* Optional SID playback
* Command-line interface
* Can be used as a Go library in custom tools

**Supported Formats**

* PNG
* GIF
* JPEG
* PRG
* PETSCII
* Sprite data
* Bitmap data
* Character sets

**Integration**

* Kick Assembler
* 64tass
* ACME
* VICE
* Automated build systems
* Go-based asset pipelines

**Primary Purpose**
Automated conversion of modern artwork into Commodore 64 graphics and executable display programs.

---

<a id="png2spd-header"></a>

## png2spd

**Official URL**
https://github.com/Esshahn/png2spd

**Category**
Asset Conversion Tool

**Host Platforms**

* Windows
* Linux
* macOS

**Verified Commodore Targets**

* C64

**Overview (Detailed)**
png2spd is a specialised graphics conversion utility that converts PNG images into SpritePad (.SPD) project files for Commodore 64 sprite development. Rather than generating finished binaries, it produces editable SpritePad projects, allowing artists to continue refining sprites using SpritePad Pro or compatible editors. This makes it particularly useful in modern graphics production pipelines where artwork originates in conventional image editors before being imported into C64-specific tools.

**Development Features**

* PNG import
* SpritePad (.SPD) project generation
* Automatic palette conversion
* VIC-II sprite constraint handling
* Command-line operation
* Suitable for automated build pipelines

**Supported Formats**

* PNG
* SPD (SpritePad)
* VIC-II sprite graphics

**Integration**

* SpritePad C64 Pro
* Kick Assembler
* VICE
* Modern graphics workflows

**Primary Purpose**
Convert modern bitmap artwork into editable SpritePad project files for Commodore 64 sprite development.

---

<a id="retropixels-header"></a>

## RetroPixels+

**Official URL**
https://meatloaf.cc/tools/retropixels/

**Category**
Graphics Conversion Tool

**Host Platforms**

* Windows
* Linux
* macOS

**Verified Commodore Targets**

* C64

**Overview (Detailed)**
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
