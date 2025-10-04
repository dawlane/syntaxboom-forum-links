# Gnu Compiler Collection C/C++ Development Environment Setup

**NOTE:** Many of the sites linked here, have not been fully checked or validated for what contents they offer, and possibly in the future they may also be broken. Anyone using the links should remain vigilant to protect themselves from malicious software and sites through the use of internet security software and good judgement by not falling prey to sites that require the specific entry of personal information. The accuracy of the descriptions may also not be correct, and should be in many cases considered a work-in-progress.
If they don't appear to be what is advertised, or look suspicious.
Then PM an administrator so they can be removed, or updated with the correct information.  
**So use these links and any associated software from these sites at your own risk!**

This tutorial will go through the steps to set up a development environment for the Gnu Compiler Collection (aka GCC) that focuses on the tool chain for the creation of C/C++ applications. What steps to take depends on the operating system, the build systems, this would traditionally be Makefiles, and if an Integrated Development Environment is to be used.

## Step One: Installing

### GCC On MS Windows

On Windows the GCC tool chain is known as MinGW (aka Minimalist Gnu for Windows). The setup for MinGW can get a bit tricky, as it depends on how you want to set up the development environment, but the basics require that MinGW can either be downloaded and used stand alone, or alternatively download as part of a posix environment, such as MSYS2, which can give you access to cool libraries and tools that you would normally find on a Linux, or macOS system setup. Whichever is chosen. You have to decide if you want to use MinGW system wide or a build environment launched from a script.

#### MinGW Installation

The current trend for installing MinGW is via [***MSYS2***](https://www.msys2.org). This is a Linux like posix terminal environment. The MSYS2 a rolling release that actually comes with a number of [*runtime environments*](https://www.msys2.org/docs/environments/), with the current version of MSYS2 favouring the 64 bit **U**niversal **C** **R**un **T**ime (aka **UCRT64**). You will need to pay attention to the directory structures, as you will need these later.

The alternate method is to download a specific version and install or extract the files to a directory. The most common location is to setup the files on the main system drive e.g. **C:\MinGW**. You can download, or build a version of MinGW from [*https://www.mingw-w64.org/*](https://www.mingw-w64.org/).

#### MinGW System Wide

To use MinGw system wide. You have to add the MinGW bin directory to the systems **PATH** environment variable. You simple do this by clicking on the **Windows System Start Menu** and search for **Edit** the system Environment Variables. In the **System Properties** dialog, click the **Environment  Variables...** button. And in the dialog, find the **path** variable in the **System Variables** sections and click the **Edit** button. And add the MinGW bin directory path. The next time you reboot the computer, MinGW will be system wide. The alternative to system wide, is to add the MinGW bin path to **Path** in the **Use Environment** section.

#### MinGW Shell Script

Another way is to write a BATCH file, or PowerShell script to add the MinGW path the current users **Path** and then automatically start a new command shell, or an editor.

A Powershell script example called ***mingw-script.ps1*** for setting up an environment and starting a new Powershell terminal, or VS Code with a specific user defined profile.</br>

```powershell

# Usage: .\mingw-script.ps1 {-dir root_dir_path -version version_number}
param(
    [string]$dir=".",
    [string]$version="14.2.0"
)

    # Set the path to the MinGW version to use.
    [string]$MINGW_W64 = "C:\development\winlibs\gcc-$version-posix-mingw-w64ucrt-12.0.0\mingw64"
    ${env:PATH}="$MINGW_W64\bin;${env:PATH}"
    
    # Comment out the two lines below, and uncomment the Start-Process for VSCode if not using a commandline console.
    set-location $dir
    start-process powershell
    # Start VS Code with a specific VS Code user defined profile at a specific directory.
    # Start-Process -PassThru -FilePath "C:\Program Files\Microsoft VS Code\Code.exe" "--profile `"C/C++ Dev`" $dir"
```

</br>

### GCC On Linux

On Linux. You install GCC via the Linux distribution's package manager. Now this depends on the type of package manager, the distribution and the actual names used for the various packages. Many distributions have what is call a base development package that installs the core build tools used for development. It is recommended that you search the distributions support forum for details on development packages. Below are a number of terminal command lines for the most popular distributions for the installation of base development packages.

#### Linux distributions derived from Debian or Ubuntu

```text
sudo update
sudo apt install build-essential
```

#### OpenSUSE

```text
sudo zypper ref
sudo zypper up
sudo zypper in -t pattern devel_basis
```

#### Fedora 41 and later

```text
sudo dnf update
sudo dnf install @c-development
```

#### Arch Linux

```text
sudo pacman -Syu
sudo pacman -S base-devel
```

</br>

### GCC On macOS

On macOS. You have to install [*XCode*](https://developer.apple.com/xcode/) to the **Application** directory and the XCode command line developer tools in an open terminal shell with `xcode-select --install`.</br></br>

</br>

## Step Two: Build Tool Environment

If not using an Integrated Development Environment that supports it's own build environment, then you will need to install a build system tool; that is unless you like to do every build step by hand, which many would say is a good learning experience as it gets you familiar with the actual build process. But if you think that would be too tedious, then there are a fair few build systems that can be used. There's the ever venerable [***Gnu make tool***](https://www.gnu.org/software/make/), on MS Windows you would use MinGW32-make, to the more recent upstart makefile generator [***CMake***](https://cmake.org/). There is also nothing stopping you from creating your own custom build script with regular shell scripts, but you lose a lot of functionality such as incremental builds and speed.

Here is a list of current build systems that either are true make tools, or makefile generators.

* [Gnu make tool](https://www.gnu.org/software/make/)
* [CMake](https://cmake.org/)
* [Scons](https://scons.org/)
* [Premake](https://premake.github.io/)
* [Ninja-Build](https://ninja-build.org/)
* [Meson](https://mesonbuild.com/)
* [FastBuild](https://www.fastbuild.org/docs/home.html)
* [Bazel](https://bazel.build/)
* [Build2](https://build2.org/)
* [Waf](https://waf.io/)
* [Tundra](https://github.com/deplinenoise/tundra)
* [Tup](https://gittup.org/tup/)
* [XMake](https://xmake.io/)
* [AutoMake/AutoTools](https://www.gnu.org/software/automake/manual/html_node/index.html#SEC_Contents)

All of these build systems have a bit of a learning curve, but once learned can make building applications a lot easier. The current trend is to use CMake to generate a files that can be used with a make build system, or number of integrated development environments.

</br>

## Step Three: Code Editor

You can use any type of text editor to create source code files. But the more simpler the editor, the more work has to be done to compile, debug and profile the application. Ideally at the minimum, an editor should support break point debugging, code highlighting and a method to organize the code files.

### Plain Text Editors

These types of editors usually come as part of the operating system and generally have no formatting capabilities, but some do have such luxuries such as code highlighting and the opening of multiple files. Plain text editors are mostly used for making or creating edits to system configuration files and basic notes. They also have a simple user interface that mostly handles creating, loading, saving of files and basic editing functionality such as undo, redo, cut, copy, paste and delete. But some do have some features as searching and replace of text in a file.

Examples of plain text editors:

* [*Notepad*](https://en.wikipedia.org/wiki/Windows_Notepad) (*MS Windows GUI*)
* [*Edit*](https://learn.microsoft.com/en-us/windows/edit/) (*MS Windows Console: **Note:** Currently not available for Windows 11 as a default feature*)
* [*TextEdit*](https://support.apple.com/en-gb/guide/textedit/welcome/mac) (*Apple macOS GUI*)
* [*nano*](https://www.nano-editor.org/) (*Console*)
* [*Vim*](https://www.vim.org/)  (*Console & GUI*)
* [*gEdit*](https://gedit-text-editor.org/) (*GUI*)
* [*xed*](https://github.com/linuxmint/xed) (*Linux GUI*)

Using a plain text editor requires that you are comfortable building and debugging using a command line terminal.

### Versatile Text Editors

These types of editors have more features than a plain text editor, usually via a plugins or extensions. Like plain text editors, they have the usual basic features and generally implement file management system of some type. Some of the additional features can include code highlighting, a GUI command line console, and functionality to execute external commands.

Examples of versatile text editors:

* [*Visual Studio Code*](https://code.visualstudio.com/)
* [*Emacs*](https://www.gnu.org/software/emacs/)
* [*Textmate*](https://macromates.com/) (*macOS only*)
* [*Notepad++*](https://notepad-plus-plus.org/) (*MS Windows Only*)
* [*Sublime Text*](https://www.sublimetext.com/)
* [*Geany*](https://www.geany.org/)
* [*Zed*](https://zed.dev/)
* [*Kate Editor*](https://kate-editor.org/en-gb/)

Many versatile text editors may require that you have to learn how to control features via the use of configuration files.

### Integrated Development Environments

An Integrated Development Environment, also known as an **IDE**. Is an application that is specifically written for the writing, compiling, debugging and profiling of an application or other programming task. Some of these IDE's are dedicated to just the one programming language, or can support multiple programming languages. They have their own build system, but some can be configured to use another if required. These type of code editors have a lot more features and settings than the other types previously mentioned, due to supporting file and compiler project management and configuration.

Examples of integrated development environments:

* [*CodeLite*](https://codelite.org/)
* [*Code::Blocks*](https://www.codeblocks.org/) (***Note:** On macOS, Code::Blocks is buggy and may not work at all on newer versions of macOS*)
* [*Netbeans*](https://netbeans.apache.org/front/main/index.html) (*Requires the C++ development plugin*)
* [*CLion*](https://www.jetbrains.com/clion/)
* [*Dev-C++*](https://www.embarcadero.com/free-tools/dev-cpp) (***Note:** The IDE supports a package management system, but there are no packages and it's buggy*)
* [*Eclipse IDE for C++ Developers*](https://www.eclipse.org/downloads/packages/)
* [*Qt Creator*](https://doc.qt.io/qtcreator/) (*You don't have to download a full Qt Developer Software Kit if you only want to use the IDE for basic C/C++ software development. Read the **Installation** and projects wizard documentation sections*)
* [*XCode*](https://developer.apple.com/xcode/) (*macOS Only. **Note:** Xcode supports two languages for macOS & iOS development: Swift and Objective-C. But can be used to create a C/C++ project. And with a glue code little know-how, can be made to communicate between the different languages*)