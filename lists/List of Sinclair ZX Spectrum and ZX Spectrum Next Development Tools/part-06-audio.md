# List of Sinclair ZX Spectrum and ZX Spectrum Next Development Tools

## Music, Sound & AY Editors

This is is going to be the start of a list of useful links to various tools for programming Sinclair ZX Spectrum and ZX Spectrum Next Development home computers. If anyone adds some gems, then they will be added to this post, so people don't have to go through every post.

**NOTE:** Many of these sites linked here, have not been fully checked or validated for what contents they offer, and possibly in the future they may also be broken. Anyone using the links should remain vigilant to protect themselves from malicious software and sites through the use of internet security software and good judgement by not falling prey to sites that require the specific entry of personal information. The accuracy of the descriptions may also not be correct, and should be in many cases considered a work-in-progress.
If they don't appear to be what is advertised, or look suspicious.
Then PM an administrator so they can be removed, or updated with the correct information.  
**So use these links and any associated software from these sites at your own risk!**  

## Table of Contents

- [1tracker](#1tracker-header)
- [Arkos Tracker](#arkos-tracker-header)
- [AYFX Editor (Improved)](#ayfx-editor-improved-header)
- [BeepFX Editor](#beepfx-editor-header)
- [Beepola](#beepola-header)
- [Remy's AY Audio Generator](#remys-ay-audio-generator-header)
- [Vortex Tracker II](#vortex-tracker-ii-header)

---

<a id="1tracker-header"></a>

## 1tracker

**Official URL**
https://shiru.untergrund.net/software.shtml

**Host Platforms**

- Windows

**Verified ZX Spectrum or ZX Spectrum Next Targets**

- ZX Spectrum 128K
- ZX Spectrum +2
- ZX Spectrum +2A/+2B
- ZX Spectrum +3
- ZX Spectrum Next

**Overview**  
1tracker is a compact music tracker created by Shiru for composing music for AY-3-8910 and compatible sound chips commonly found in 128K Sinclair ZX Spectrum systems. The application provides a tracker-style workflow familiar to retro game musicians while focusing on efficient music creation for constrained hardware environments.

The tracker is frequently used by hobbyist and homebrew developers seeking a lightweight solution for producing AY music. Its straightforward workflow allows composers to quickly create background music suitable for games, demos and other Spectrum software projects.

**Development Features**

- Pattern-based music composition
- AY chip music creation
- Instrument editing
- Pattern editor
- Order list management
- Playback testing
- Compact workflow
- Export support

**Supported Playback Engines**

- Built-in 1tracker playback engine

**Supported File Formats**

- 1tracker project files
- AY music data exports

**Integration**

- **Assemblers**
  - Asset export workflows
- **Compilers**
  - Asset export workflows
- **Frameworks & SDKs**
  - Compatible with AY playback integration
- **External tools**
  - ZX Spectrum build pipelines

**Primary Purpose**  
A lightweight tracker for composing AY music for ZX Spectrum 128K-class systems and ZX Spectrum Next projects.  

---

<a id="arkos-tracker-header"></a>

## Arkos Tracker

**Official URL**
https://www.julien-nevo.com/arkostracker/

**Source Code**
https://github.com/ArkosTracker/ArkosTracker2

**Host Platforms**

- Windows
- Linux
- macOS

**Verified ZX Spectrum or ZX Spectrum Next Targets**

- ZX Spectrum 128K
- ZX Spectrum +2
- ZX Spectrum +2A/+2B
- ZX Spectrum +3
- ZX Spectrum Next

**Overview**  
Arkos Tracker is a modern cross-platform chiptune tracker supporting AY-3-8910 music composition for multiple retro systems, including the Sinclair ZX Spectrum family. It provides an advanced music creation environment featuring sophisticated instrument control, effect processing and export facilities designed for game development.

The tracker is widely used throughout the retro-development community because it combines powerful composition features with efficient replay routines. Its music engines are particularly well suited to commercial-quality games and demos targeting AY-equipped Spectrum hardware.

**Development Features**

- Multi-pattern composition
- Advanced instrument editor
- Effect processing
- AY music generation
- Music optimisation
- Cross-platform operation
- Real-time playback
- Export facilities
- Multi-project workflow

**Supported Playback Engines**

- Arkos Tracker Player
- Arkos Tracker Lightweight Player

**Supported File Formats**

- Arkos Tracker project files
- AY music exports
- Assembly exports

**Integration**

- **Assemblers**
  - SjASMPlus
  - PASMO
- **Compilers**
  - z88dk
  - Boriel BASIC
- **Frameworks & SDKs**
  - Compatible with custom AY playback integration
- **External tools**
  - Automated build pipelines

**Primary Purpose**  
A professional cross-platform AY music tracker and playback system for retro game development.  

---

<a id="ayfx-editor-improved-header"></a>

## AYFX Editor (Improved)

**Official URL**
https://github.com/Threetwosevensixseven/ayfxedit-improved

**Host Platforms**

- Windows
- Linux
- macOS

**Verified ZX Spectrum or ZX Spectrum Next Targets**

- ZX Spectrum 128K
- ZX Spectrum +2
- ZX Spectrum +2A/+2B
- ZX Spectrum +3
- ZX Spectrum Next

**Overview**  
AYFX Editor (Improved) is an enhanced editor for creating AY sound effects compatible with the widely used AYFX sound effect system. It allows developers and audio designers to create, modify and preview sound effects intended for games and interactive software running on AY-equipped Sinclair hardware.

The tool is focused specifically on sound effects rather than music composition, making it an important companion tool to music trackers. It is commonly used in game development projects where efficient memory usage and fast sound effect playback are important considerations.

**Development Features**

- Sound effect creation
- Sound effect editing
- AY register editing
- Real-time preview
- Effect library management
- Import and export support
- Cross-platform operation

**Supported Playback Engines**

- AYFX Player

**Supported File Formats**

- AYFX banks
- AYFX effect files
- Assembly exports

**Integration**

- **Assemblers**
  - SjASMPlus
  - PASMO
- **Compilers**
  - z88dk
  - Boriel BASIC
- **Frameworks & SDKs**
  - Compatible with AYFX playback libraries
- **External tools**
  - Game build workflows

**Primary Purpose**  
A specialised editor for creating AY sound effect libraries for ZX Spectrum software development.  

---

<a id="beepfx-editor-header"></a>

## BeepFX Editor

**Official URL**
https://shiru.untergrund.net/software.shtml

**Host Platforms**

- Windows

**Verified ZX Spectrum or ZX Spectrum Next Targets**

- ZX Spectrum 16K
- ZX Spectrum 48K
- ZX Spectrum 128K
- ZX Spectrum +2
- ZX Spectrum +2A/+2B
- ZX Spectrum +3
- ZX Spectrum Next

**Overview**  
BeepFX Editor is a sound effect creation utility designed for the ZX Spectrum beeper speaker. It allows developers to create sound effects suitable for machines that lack AY sound hardware or for projects that intentionally target the original beeper-based audio environment.

The tool is particularly useful for games targeting 16K and 48K Spectrum systems where audio must be generated through the machine's internal speaker. It provides a streamlined workflow for designing retro sound effects that fit within the constraints of beeper audio playback.

**Development Features**

- Beeper sound effect creation
- Sound preview
- Effect editing
- Export facilities
- Compact workflow
- Hardware-aware design

**Supported Playback Engines**

- BeepFX playback engine

**Supported File Formats**

- BeepFX effect data
- Assembly exports

**Integration**

- **Assemblers**
  - SjASMPlus
  - PASMO
- **Compilers**
  - z88dk
  - Boriel BASIC
- **Frameworks & SDKs**
  - Compatible with BeepFX playback libraries
- **External tools**
  - ZX Spectrum game build workflows

**Primary Purpose**  
A dedicated editor for designing and exporting ZX Spectrum beeper sound effects.  

---

<a id="beepola-header"></a>

## Beepola

**Official URL**
https://freestuff.grok.co.uk/beepola/

**Host Platforms**

- Windows

**Verified ZX Spectrum or ZX Spectrum Next Targets**

- ZX Spectrum 16K
- ZX Spectrum 48K
- ZX Spectrum 128K
- ZX Spectrum +2
- ZX Spectrum +2A/+2B
- ZX Spectrum +3
- ZX Spectrum Next

**Overview**  
Beepola is one of the most widely used music composition tools for ZX Spectrum beeper audio. It enables composers to create music using several popular beeper playback engines and provides a tracker-like workflow tailored specifically to Spectrum hardware limitations.

The application has become a standard tool for developers targeting 48K and other beeper-based Spectrum systems. By supporting multiple playback engines, it gives composers flexibility when balancing sound quality, CPU usage and memory consumption.

**Development Features**

- Pattern-based composition
- Beeper music creation
- Multi-engine support
- Song arrangement tools
- Playback testing
- Export facilities
- Instrument configuration

**Supported Playback Engines**

- Phaser 1 Engine
- Phaser 2 Engine
- The Music Box
- Special FX
- Octode
- MicroBeep

**Supported File Formats**

- Beepola project files
- Assembly exports
- Music data exports

**Integration**

- **Assemblers**
  - SjASMPlus
  - PASMO
- **Compilers**
  - z88dk
  - Boriel BASIC
- **Frameworks & SDKs**
  - Compatible with supported playback engines
- **External tools**
  - Spectrum game development workflows

**Primary Purpose**  
A tracker-based music composition environment for ZX Spectrum beeper audio systems.  

---

<a id="remys-ay-audio-generator-header"></a>

## Remy's AY Audio Generator

**Official URL**
https://zx.remysharp.com/audio/#src=MjA4LDMy

**Host Platforms**

- Web

**Verified ZX Spectrum or ZX Spectrum Next Targets**

- ZX Spectrum 128K
- ZX Spectrum +2
- ZX Spectrum +2A/+2B
- ZX Spectrum +3
- ZX Spectrum Next

**Overview**  
Remy's AY Audio Generator is a browser-based sound generation tool designed specifically for AY-3-8910 audio development targeting the Sinclair ZX Spectrum family and ZX Spectrum Next. The application allows developers, musicians and sound designers to experiment with AY register values, tones, envelopes and sound generation parameters directly within a modern web browser.

Unlike full-featured music trackers, the tool focuses on rapid prototyping, experimentation and understanding of AY sound generation. This makes it particularly useful for developers creating sound effects, testing playback routines or learning how AY audio hardware behaves. Because it operates entirely in the browser, it can be used immediately without installation, making it a convenient companion utility within modern ZX Spectrum development workflows.

**Development Features**

- Browser-based operation
- AY tone generation
- Envelope experimentation
- Real-time audio preview
- Register-level control
- Sound effect prototyping
- Rapid iteration workflow
- Export-oriented development support

**Supported Playback Engines**

- Generic AY playback implementations
- Custom AY playback routines

**Supported File Formats**

- Generated AY parameter data
- Browser-exported audio configuration data

**Integration**

- **Assemblers**
  - Compatible with assembly-based AY playback routines
- **Compilers**
  - Compatible with AY-enabled applications
- **Frameworks & SDKs**
  - Compatible with custom AY audio systems
- **External tools**
  - Remy's ZX Spectrum Tools

**Primary Purpose**  
A browser-based AY sound design and prototyping utility for Sinclair ZX Spectrum and ZX Spectrum Next audio development.  

---

<a id="vortex-tracker-ii-header"></a>

## Vortex Tracker II

**Official URL**
https://ay.strangled.net/vortex_e.htm

**Host Platforms**

- Windows

**Verified ZX Spectrum or ZX Spectrum Next Targets**

- ZX Spectrum 128K
- ZX Spectrum +2
- ZX Spectrum +2A/+2B
- ZX Spectrum +3
- ZX Spectrum Next

**Overview**  
Vortex Tracker II is one of the most influential and widely adopted AY music trackers within the ZX Spectrum scene. It was created specifically for composing music for AY-3-8910 and YM-compatible sound chips and has been used extensively in games, demos and music productions for Sinclair ZX Spectrum systems.

The tracker provides a powerful pattern-based composition environment with extensive control over instruments, ornaments, envelopes and playback effects. Its popularity has resulted in broad support throughout the Spectrum development ecosystem, and a significant amount of existing AY music content has been produced using its workflow. Vortex Tracker II remains an important tool for both new and experienced AY musicians.

**Development Features**

- Pattern-based composition
- Advanced AY music editing
- Instrument editor
- Ornament editor
- Envelope control
- Multi-channel composition
- Real-time playback
- Song arrangement tools
- Music export facilities
- Mature workflow

**Supported Playback Engines**

- PT3 Playback Engine
- PT2 Playback Engine

**Supported File Formats**

- `.pt3`
- `.pt2`
- Vortex Tracker project files
- Assembly exports

**Integration**

- **Assemblers**
  - SjASMPlus
  - PASMO
- **Compilers**
  - z88dk
  - Boriel BASIC
- **Frameworks & SDKs**
  - Compatible with PT2 and PT3 playback libraries
- **External tools**
  - ZX Spectrum game and demo build pipelines

**Primary Purpose**  
A professional AY music tracker for composing and exporting music for Sinclair ZX Spectrum 128K systems and ZX Spectrum Next projects.

[Back to index](index.md)
