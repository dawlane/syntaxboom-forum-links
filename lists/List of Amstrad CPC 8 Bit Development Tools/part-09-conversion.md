# List of Amstrad CPC 8 Bit Development Tools - Asset Conversion Tools

This is is going to be the start of a list of useful links to various tools for programming Amstrad CPC 8 Bit home computers. If anyone adds some gems, then they will be added to this post, so people don't have to go through every post.

**NOTE:** Many of these sites linked here, have not been fully checked or validated for what contents they offer, and possibly in the future they may also be broken. Anyone using the links should remain vigilant to protect themselves from malicious software and sites through the use of internet security software and good judgement by not falling prey to sites that require the specific entry of personal information. The accuracy of the descriptions may also not be correct, and should be in many cases considered a work-in-progress.
If they don't appear to be what is advertised, or look suspicious.
Then PM an administrator so they can be removed, or updated with the correct information.  
**So use these links and any associated software from these sites at your own risk!**  

## Table of contents

* [ConvImgCPC](#convimgcpc-header)
* [Img2CPC](#img2cpc-header)
* [Martine](#martine-header)

---
<a id="convimgcpc-header"></a>

# ConvImgCPC

**Official URL**

https://github.com/IMPact-Scene/ConvImgCpc

**Host Platforms**

* Windows
* Linux
* macOS

**Verified Amstrad CPC Targets**

* Amstrad CPC 464
* Amstrad CPC 664
* Amstrad CPC 6128
* CPC Plus range

**Overview**  
ConvImgCPC is a specialised graphics conversion utility designed to transform modern image formats into data suitable for use on the Amstrad CPC. It automates many of the technical tasks involved in preparing artwork for the CPC's display hardware, including colour reduction, palette conversion, pixel format transformation, and binary data generation.

The tool is intended for use after artwork has been created in a graphics editor such as GrafX2. Rather than editing images directly, ConvImgCPC focuses on converting completed artwork into formats that can be consumed by games, demos, utilities, and other CPC software projects.

Modern CPC development commonly separates asset creation from asset conversion. Artists create graphics using contemporary tools while programmers use conversion utilities to generate binary resources suitable for integration into source code and build systems. ConvImgCPC fits directly into this workflow by acting as the bridge between artwork and executable software.

The utility is particularly useful for automated build environments because conversion tasks can be integrated into repeatable project pipelines.

**Development Features**

* Image conversion
* CPC palette conversion
* Colour reduction
* Pixel format conversion
* Binary asset generation
* Automated asset processing
* Build pipeline integration
* Batch conversion support
* Command-line workflow
* Cross-platform operation
* Resource preparation
* Software deployment workflow support

**Supported File Formats**

* PNG
* BMP
* CPC binary graphics formats
* Raw graphics data
* Resource files

**Integration**

* PASMO
* RASM
* SjASMPlus
* WinAPE
* Arnold
* ACE-DL
* Retro Virtual Machine

**External Tools**

* GrafX2
* CPCTelera
* CPCTools
* KC IDE
* Build automation systems

**Primary Purpose**  
Convert modern image assets into graphics data suitable for use in Amstrad CPC software projects.

---

<a id="img2cpc-header"></a>

# Img2CPC

**Official URL**
https://github.com/AugustoRuiz/Img2CPC

**Host Platforms**

* Windows
* Linux
* macOS

**Verified Amstrad CPC Targets**

* Amstrad CPC 464
* Amstrad CPC 664
* Amstrad CPC 6128

**Overview**  

Img2CPC is a graphics conversion utility designed specifically for transforming standard image files into formats suitable for the Amstrad CPC graphics hardware. The tool assists developers in preparing artwork for use in games, demos, loading screens, user interfaces, and other graphical applications.

The conversion process handles many CPC-specific requirements automatically, reducing the complexity involved in adapting modern artwork to classic hardware limitations. Developers can use the utility to generate graphical resources that can be linked directly into assembly, C, or framework-based projects.

Img2CPC is particularly useful within automated workflows because it allows graphics assets to be regenerated whenever source artwork changes. This supports modern development practices where graphical resources remain synchronised with source control and build systems.

As a dedicated conversion utility rather than an editor, Img2CPC complements tools such as GrafX2 by focusing solely on preparing assets for deployment.

**Development Features**

* Image conversion
* CPC graphics generation
* Palette conversion
* Binary output generation
* Asset preparation workflow
* Automated processing
* Command-line operation
* Cross-platform compatibility
* Build system integration
* Resource generation

**Supported File Formats**

* PNG
* BMP
* CPC graphics resources
* Binary output files

**Integration**

* PASMO
* RASM
* SjASMPlus
* WinAPE
* Arnold
* ACE-DL
* Retro Virtual Machine

**External Tools**

* GrafX2
* KC IDE
* CPCTelera
* z88dk
* Build automation systems

**Primary Purpose**  
Convert standard image assets into Amstrad CPC-compatible graphics resources.

---
<a id="martine-header"></a>

# Martine

**Official URL**
https://github.com/jeromelesaux/martine

**Host Platforms**

* Windows
* Linux
* macOS

**Verified Amstrad CPC Targets**

* Amstrad CPC 464
* Amstrad CPC 664
* Amstrad CPC 6128
* CPC Plus range
* GX4000

**Overview**  

Martine is a modern multimedia conversion toolkit focused on preparing graphical assets for Amstrad CPC systems. It provides an extensive collection of conversion, optimisation, and export functions that help developers transform contemporary artwork into formats suitable for CPC hardware.

The project supports numerous graphics workflows including screen conversion, sprite preparation, palette generation, image optimisation, and resource export. It is actively used within the modern CPC development community for game development, demoscene productions, and preservation projects.

Martine is designed to simplify many of the technical challenges associated with CPC graphics production. By automating colour selection, palette adaptation, and hardware-specific formatting, it allows artists and developers to focus on content creation rather than low-level conversion details.

The tool integrates well with contemporary development pipelines and is frequently used alongside editors, assemblers, frameworks, and automated build systems.

**Development Features**

* Image conversion
* Screen conversion
* Sprite conversion
* Palette optimisation
* CPC graphics generation
* CPC Plus graphics support
* Resource export
* Automated asset processing
* Batch conversion
* Command-line workflow
* Cross-platform operation
* Build system integration
* Modern development workflow support

**Supported File Formats**

* PNG
* BMP
* JPG
* GIF
* CPC screen formats
* CPC sprite formats
* Binary resource files

**Integration**

* PASMO
* RASM
* SjASMPlus
* WinAPE
* Arnold
* ACE-DL
* Retro Virtual Machine

**External Tools**

* GrafX2
* KC IDE
* CPCTelera
* CPCTools
* z88dk
* Build automation systems
* Continuous integration workflows

**Primary Purpose**  
Convert, optimise, and export graphical assets for use in Amstrad CPC games, demos, and software projects.

[Back to index](index.md)
