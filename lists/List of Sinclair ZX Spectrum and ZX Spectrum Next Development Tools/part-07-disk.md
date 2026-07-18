# List of Sinclair ZX Spectrum and ZX Spectrum Next Development Tools# Disk

## Image & Media Utilities

This is is going to be the start of a list of useful links to various tools for programming Sinclair ZX Spectrum and ZX Spectrum Next Development home computers. If anyone adds some gems, then they will be added to this post, so people don't have to go through every post.

**NOTE:** Many of these sites linked here, have not been fully checked or validated for what contents they offer, and possibly in the future they may also be broken. Anyone using the links should remain vigilant to protect themselves from malicious software and sites through the use of internet security software and good judgement by not falling prey to sites that require the specific entry of personal information. The accuracy of the descriptions may also not be correct, and should be in many cases considered a work-in-progress.
If they don't appear to be what is advertised, or look suspicious.
Then PM an administrator so they can be removed, or updated with the correct information.  
**So use these links and any associated software from these sites at your own risk!**  

## Table of Contents

- [hdfmonkey](#hdfmonkey-header)
- [ZX-Blockeditor](#zx-blockeditor-header)

---

<a id="hdfmonkey-header"></a>

## hdfmonkey

**Official URL**
https://github.com/gasman/hdfmonkey

**Host Platforms**

- Windows
- Linux
- macOS

**Verified ZX Spectrum or ZX Spectrum Next Targets**

- ZX Spectrum Next

**Overview**  
hdfmonkey is a command-line utility for creating, inspecting and modifying FAT-formatted hard disk image files used by the ZX Spectrum Next. It allows developers to manipulate virtual storage media directly from a modern desktop operating system without needing to boot an emulator or access physical ZX Spectrum Next hardware.

The tool has become a common component within automated ZX Spectrum Next build pipelines because it can insert, remove and manage files within hard disk images programmatically. This makes it particularly valuable for projects that use automated asset generation, continuous integration workflows or scripted deployment processes. By enabling direct manipulation of HDF images, hdfmonkey significantly simplifies preparation of development and testing environments.

**Development Features**

- FAT filesystem support
- Hard disk image creation
- Hard disk image inspection
- File extraction
- File insertion
- Directory management
- Scriptable command-line operation
- Automated build integration
- Cross-platform support

**Supported File Formats**

- `.hdf`
- FAT filesystem images

**Integration**

- **Assemblers**
  - Compatible with automated deployment workflows
- **Compilers**
  - Compatible with automated deployment workflows
- **Emulators**
  - CSpect
  - ZEsarUX
- **Frameworks & SDKs**
  - Compatible with ZX Spectrum Next development frameworks
- **External tools**
  - Makefiles
  - Continuous integration systems
  - Deployment scripts

**Primary Purpose**  
A command-line utility for creating and managing ZX Spectrum Next hard disk image files and deployment workflows.  

---

<a id="zx-blockeditor-header"></a>

## ZX-Blockeditor

**Official URL**
https://zx-modules.jimdofree.com/zx-modules-start/zx-blockeditor/

**Host Platforms**

- Windows

**Verified ZX Spectrum or ZX Spectrum Next Targets**

- ZX Spectrum 48K
- ZX Spectrum 128K
- ZX Spectrum +2
- ZX Spectrum +2A/+2B
- ZX Spectrum +3

**Overview**  
ZX-Blockeditor is a specialised utility for creating and managing data blocks used within Sinclair ZX Spectrum tape-based software. It provides facilities for examining, editing and generating block structures that can be incorporated into TAP and related media formats commonly used by Spectrum development tools and emulators.

The utility is particularly useful when working with custom loaders, tape-based game distribution formats and low-level media manipulation tasks. By exposing the underlying block structure of Spectrum storage media, it allows developers to create and maintain media layouts that would otherwise require manual editing or specialised scripting.

**Development Features**

- Tape block editing
- Block creation
- Block inspection
- Data structure management
- Media preparation workflows
- Format-aware editing
- Export facilities

**Supported File Formats**

- `.tap`
- ZX Spectrum tape block data

**Integration**

- **Assemblers**
  - Compatible with generated binary outputs
- **Compilers**
  - Compatible with generated binary outputs
- **Emulators**
  - Fuse
  - EightyOne
  - ZEsarUX
  - Retro Virtual Machine
- **Frameworks & SDKs**
  - Compatible with tape-loading workflows
- **External tools**
  - ZX Modules utility suite

**Primary Purpose**  
A utility for creating, editing and managing ZX Spectrum tape media block structures and related development assets.

[Back to index](index.md)
