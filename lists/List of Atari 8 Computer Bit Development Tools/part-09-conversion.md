# List of Atari 8 Computer Bit Development Tools - Asset Conversion Tools

This is is going to be the start of a list of useful links to various tools for programming Atari 8 Bit home computers. If anyone adds some gems, then they will be added to this post, so people don't have to go through every post.

**NOTE:** Many of these sites linked here, have not been fully checked or validated for what contents they offer, and possibly in the future they may also be broken. Anyone using the links should remain vigilant to protect themselves from malicious software and sites through the use of internet security software and good judgement by not falling prey to sites that require the specific entry of personal information. The accuracy of the descriptions may also not be correct, and should be in many cases considered a work-in-progress.
If they don't appear to be what is advertised, or look suspicious.
Then PM an administrator so they can be removed, or updated with the correct information.  
**So use these links and any associated software from these sites at your own risk!**  

## Table of Contents

- [BMP2MCH](#bmp2mch-header)
- [BMP2MIC](#bmp2mic-header)
- [CharSetter](#charsetter-header)
- [G2F Extractor](#g2f-extractor-header)

---

<a id="bmp2mch-header"></a>

## BMP2MCH

**Official URL**
https://github.com/tebe6502/bmp2mch

**Host Platforms**

- Windows
- Linux
- macOS

**Verified Target Systems**

- Atari 8-bit Family

**Overview**  
BMP2MCH is a command-line asset conversion utility that converts modern bitmap images into Atari character mode graphics suitable for use in games, demos, and other Atari 8-bit software. It is designed to integrate into automated build pipelines, allowing graphics created with contemporary image editors to be converted into native Atari data formats as part of the build process.

**Development Features**

- Command-line interface
- Batch processing
- Automated asset conversion
- Build pipeline integration
- Cross-platform operation

**Conversion Targets**

- Character mode graphics
- Native Atari graphics data

**Supported File Formats**

- Input
  - .BMP

- Output
  - MCH graphics data

**Integration**

- Bitmap, Map, Character, Sprite & Graphics Editors
  - Graph2Font
  - RetroDP Pixel Art Editor
- Cross-Compilers & High-Level Languages
  - cc65
  - Mad Pascal
- Build systems

**Primary Purpose**  
Command-line bitmap conversion utility for Atari 8-bit character graphics.

---

<a id="bmp2mic-header"></a>

## BMP2MIC

**Official URL**
https://github.com/tebe6502/bmp2mic

**Host Platforms**

- Windows
- Linux
- macOS

**Verified Target Systems**

- Atari 8-bit Family

**Overview**  
BMP2MIC is a companion utility to BMP2MCH that converts standard bitmap images into Atari MIC graphics. It is intended for automated graphics conversion workflows and is particularly useful when integrating artwork created with modern graphics editors into Atari 8-bit software projects.

**Development Features**

- Command-line interface
- Batch processing
- Automated graphics conversion
- Cross-platform operation
- Build pipeline integration

**Conversion Targets**

- MIC graphics
- Native Atari bitmap data

**Supported File Formats**

- Input
  - .BMP

- Output
  - .MIC

**Integration**

- Bitmap, Map, Character, Sprite & Graphics Editors
  - Graph2Font
  - RetroDP Pixel Art Editor
- Cross-Compilers & High-Level Languages
  - cc65
  - Mad Pascal
- Build systems

**Primary Purpose**  
Command-line bitmap conversion utility for Atari MIC graphics.

---

<a id="charsetter-header"></a>

## CharSetter

**Official URL**
https://www.atari.org.pl/charsetter/

**Host Platforms**

- Web

**Verified Target Systems**

- Atari 8-bit Family

**Overview**  
CharSetter is a browser-based utility for creating, editing, and converting Atari character sets and tile maps. It bridges modern graphics workflows with Atari-native formats by importing standard image files and exporting character data suitable for use with assembly language, cc65, Mad Pascal, Atari BASIC, and other Atari development environments. Its strong emphasis on import and export functionality makes it a valuable addition to modern Atari asset conversion pipelines.

**Development Features**

- Character set conversion
- Tile map conversion
- Browser-based interface
- Character editor
- Tile editor
- Palette management
- Assembly export
- cc65 export
- Mad Pascal export
- Atari BASIC export

**Conversion Targets**

- Character sets
- Tile maps
- Assembly source
- cc65 data
- Mad Pascal data

**Supported File Formats**

- Input
  - .PNG

- Output
  - Character set data
  - Tile map data
  - Assembly source

**Integration**

- Bitmap, Map, Character, Sprite & Graphics Editors
  - Graph2Font
- Assemblers
  - MADS
  - ATasm
- Cross-Compilers & High-Level Languages
  - cc65
  - Mad Pascal

**Primary Purpose**  
Browser-based character set and tile map conversion utility for Atari 8-bit development.

---

<a id="g2f-extractor-header"></a>

## G2F Extractor

**Official URL**
https://g2f.atari8.info/

**Host Platforms**

- Windows
- Linux
- macOS

**Verified Target Systems**

- Atari 8-bit Family

**Overview**  
G2F Extractor is a standalone utility distributed with the Graph2Font project that extracts graphics assets from Graph2Font project files for use in software development. It is intended for automated asset pipelines, allowing graphics created in Graph2Font to be converted into formats suitable for integration into assembly language and high-level language projects without requiring manual extraction.

**Development Features**

- Graph2Font project extraction
- Command-line interface
- Batch processing
- Automated asset generation
- Build pipeline integration

**Conversion Targets**

- Character data
- Font data
- Screen data
- Graphics assets

**Supported File Formats**

- Input
  - .G2F

- Output
  - Native Atari graphics data

**Integration**

- Bitmap, Map, Character, Sprite & Graphics Editors
  - Graph2Font
- Assemblers
  - MADS
  - ATasm
- Cross-Compilers & High-Level Languages
  - cc65
  - Mad Pascal
- Build systems

**Primary Purpose**  
Extracts reusable graphics assets from Graph2Font project files for Atari 8-bit development.

[Back to index](index.md)
