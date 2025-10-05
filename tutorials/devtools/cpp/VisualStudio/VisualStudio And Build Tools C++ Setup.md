# Visual Studio And Visual Studio Build Tools C/C++ Setup

**NOTE:** Many of the sites linked here, have not been fully checked or validated for what contents they offer, and possibly in the future they may also be broken. Anyone using the links should remain vigilant to protect themselves from malicious software and sites through the use of internet security software and good judgement by not falling prey to sites that require the specific entry of personal information. The accuracy of the descriptions may also not be correct, and should be in many cases considered a work-in-progress.
If they don't appear to be what is advertised, or look suspicious.
Then PM an administrator so they can be removed, or updated with the correct information.  
**So use these links and any associated software from these sites at your own risk!**

## Introduction

The best development environment for Microsoft Windows and other Microsoft products are those that are developed by Microsoft. This tutorial will show how to use the both Visual Studio and the Visual Studio Build Tools installers to install the required components without having to use the Visual Studio Installer GUI.

At the time of writing. The current releases of Visual Studio is Visual Studio 2022 and Visual Studio Build Tools 2022 (both at version 17.14). There is also Visual Studio 2026 available from Visual Studio Insiders, basically beta builds for testing.

## Visual Studio 2019+ And Visual Studio Build Tools 2019+

So you may be asking what is the difference between the regular Visual Studio and Visual Studio Build Tools editions. Well the Build Tools edition doesn't come with the overhead of a full blown Integrated Development Environment, but it should be noted that not all of the components will be available between the Build Tools and other editions of Visual Studio. Take for example the components that would only be available to the paid editions, you wouldn't see them being made available to the community edition.

You can download the current version of Visual Studio from [*here*](https://visualstudio.microsoft.com/). Or for a specific version and providing that the download is still available, you can try the online [***Visual Studio documentation***](https://learn.microsoft.com/en-us/visualstudio/ide). The actual download links for the various editions are buried within the section [***Installation/Administrator guide/Install by using command-line parameters***](https://learn.microsoft.com/en-us/visualstudio/install/use-command-line-parameters-to-install-visual-studio). Alternatively, you can get the downloads by having a [***Microsoft Developer Essentials***](https://visualstudio.microsoft.com/dev-essentials/) account.

### Visual Studio Installers on the commandline

**NOTE:** This tutorial doesn't support version of Visual Studio released prior to Visual Studio 2019.

If you have followed the **Visual Studio documentation** information from above. It will show all the options that you can pass to the Visual Studio installer. One of the options allows us to pass a configuration file with the file extension of ***vsconfig***. This means that we can write a file to tell the Visual Studio installer what components to install.

To get a list of the available components that a Visual Studio edition exposes. You have to look at [***List of workload IDs and component IDs***](https://learn.microsoft.com/en-us/visualstudio/install/workload-and-component-ids) documentation and follow the link to the edition of Visual Studio that is to be installed.

At the time of writing the links above would take you to the Visual Studio 2022 documentation.
So what follows would be relevant to that version of Visual Studio.

For a basic C/C++ installation using the Visual Studio Build Tools Installer, you would need to install these components that are listed [***here***](https://learn.microsoft.com/en-us/visualstudio/install/workload-component-id-vs-build-tools#desktop-development-with-c) for the desktop. And for the regular Visual Studio you will find them listed [***here***](https://learn.microsoft.com/en-us/visualstudio/install/workload-component-id-vs-community#desktop-development-with-c) for the desktop, and [***here***](https://learn.microsoft.com/en-us/visualstudio/install/workload-component-id-vs-community#game-development-with-c) for game development. To get more functionality, installation of some optional and recommended components are require.

#### For Visual Studio Build Tools 2022 there are eight required components for the Desktop C++ Workload

* Microsoft.Component.MSBuild
* Microsoft.VisualStudio.Component.Roslyn.Compiler
* Microsoft.VisualStudio.Component.TextTemplating
* Microsoft.VisualStudio.Component.VC.CoreBuildTools
* Microsoft.VisualStudio.Component.VC.CoreIde
* Microsoft.VisualStudio.Component.VC.Redist.14.Latest
* Microsoft.VisualStudio.Component.Windows10SDK
* Microsoft.VisualStudio.ComponentGroup.NativeDesktop.Core

#### For Visual Studio 2022 Community Edition there are six required components for the Desktop C++ Workload

* Microsoft.Component.MSBuild
* Microsoft.VisualStudio.Component.Roslyn.Compiler
* Microsoft.VisualStudio.Component.TextTemplating
* Microsoft.VisualStudio.Component.VC.CoreIde
* Microsoft.VisualStudio.Component.VC.Redist.14.Latest
* Microsoft.VisualStudio.ComponentGroup.NativeDesktop.Core

#### For Visual Studio 2022 Community Edition there are three required components for the Game Development C++ Workload

* Microsoft.VisualStudio.Component.VC.CoreIde
* Microsoft.VisualStudio.Component.VC.Redist.14.Latest
* Microsoft.VisualStudio.Component.Windows10SDK

#### Recommended and optional components

* Microsoft.VisualStudio.Component.VC.ATLMFC
* Microsoft.VisualStudio.Component.VC.CLI.Support
* Microsoft.VisualStudio.Component.VC.ATL
* Microsoft.VisualStudio.Component.VC.ASAN
* Microsoft.VisualStudio.Component.VC.Tools.x86.x64

#### An Example of a ***vsconfig*** file

This will be used in the commandline for the **Visual Studio Build Tools Installer**, so create a new text file, copy and paste the code below, and then rename the file to ***vsc++.vsconfig***. The **Visual Studio 2022 Installer vsconfig** file uses the same JSON file format as that for the Build Tools.</br>
**NOTE:** Make sure that the **Windows Explorer** show file extension is set so that the file extension is renamed.

```json

{
  "version": "1.0",
  "components": [
    "Microsoft.Component.MSBuild",
    "Microsoft.VisualStudio.Component.Roslyn.Compiler",
    "Microsoft.VisualStudio.Component.TextTemplating",
    "Microsoft.VisualStudio.Component.CoreBuildTools",
    "Microsoft.VisualStudio.Component.VC.CoreBuildTools",
    "Microsoft.VisualStudio.Component.VC.CoreIde",
    "Microsoft.VisualStudio.Component.VC.Redist.14.Latest",
    "Microsoft.VisualStudio.Component.Windows10SDK",
    "Microsoft.VisualStudio.ComponentGroup.NativeDesktop.Core",
    "Microsoft.VisualStudio.Component.VC.ATLMFC",
    "Microsoft.VisualStudio.Component.VC.CLI.Support",
    "Microsoft.VisualStudio.Component.VC.ATL",
    "Microsoft.VisualStudio.Component.VC.ASAN",
    "Microsoft.VisualStudio.Component.VC.Tools.x86.x64"
  ]
}

```

Once the correct **Visual Studio Installer** has been downloaded, and JSON file has been created. We can open a command-line terminal in **Administrator** mode to start the the Visual Studio, or Visual Studio Build Tools Installer with:</br>
`vs_installer.exe --config vsc++.vsconfig --passive --norestart`</br>

The above command-line should start the Visual Studio Installer in non-interactive mode with a GUI showing the installation progress.

**NOTE:** You should use the full path to the ***vsc++.vsconfig*** file, and the replace '***vs_installer.exe***' with the name of the downloaded Visual Studio Installer application.
