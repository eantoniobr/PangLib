<img align="left" src=".github/Images/pang.png" width="64" />

# PangLib 

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/5c7ef3db76de435e83008f257cb11d11)](https://www.codacy.com/app/PangyaTools/PangLib?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=pangyatools/PangLib&amp;utm_campaign=Badge_Grade) [![Discord](https://discordapp.com/api/guilds/521180240542826496/widget.png?style=shield)](https://discord.gg/HwDTssf)

Series of tools to interact with Pangya game files

## About

This set of libraries allows developers to build tools interacting with files of the MMO Golf game Pangya by Ntreev Software.

## Usage

The libraries are built using .NET Core and .NET Standard 2.0. So you need to download and setup the [.NET Core SDK](https://www.microsoft.com/net/download) on your system.

Once that is done you can simply clone this repository somewhere, create your project using the .NET CLI and then point a reference to one of the libraries.

Example, wanting to use the `PangLib.IFF` library:

```
$ mkdir MyCoolProject && cd MyCoolProject
$ dotnet new console
$ dotnet add package PangLib.IFF
```

You should get a message about the reference being added successfully, now you can use the library inside your application!

More information on how you can use each library can be found in their folders and source code comments across all classes and files.

## Available Libraries

| Library                                       | Version                                                                                                               | Build Status                                                                                                                                                                  | Description                                              |
| --------------------------------------------- | --------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------- |
| [**PangLib.IFF**](PangLib.IFF/)               | [![Nuget](https://img.shields.io/nuget/v/PangLib.IFF.svg)](https://www.nuget.org/packages/PangLib.IFF/)               | [![Build status](https://ci.appveyor.com/api/projects/status/sdpkqdag4hrstuk7/branch/master?svg=true)](https://ci.appveyor.com/project/pixeldesu/panglib-nrfc5/branch/master) | Library to handle and parse data from `.iff` files       |
| [**PangLib.DAT**](PangLib.DAT/)               | [![Nuget](https://img.shields.io/nuget/v/PangLib.DAT.svg)](https://www.nuget.org/packages/PangLib.DAT/)               | [![Build status](https://ci.appveyor.com/api/projects/status/sdpkqdag4hrstuk7/branch/master?svg=true)](https://ci.appveyor.com/project/pixeldesu/panglib-nrfc5/branch/master) | Library to handle and parse data from `.dat` files       |
| [**PangLib.PAK**](PangLib.PAK/)               | [![Nuget](https://img.shields.io/nuget/v/PangLib.PAK.svg)](https://www.nuget.org/packages/PangLib.PAK/)               | [![Build status](https://ci.appveyor.com/api/projects/status/cd5qsu61grfsjd7q/branch/master?svg=true)](https://ci.appveyor.com/project/pixeldesu/panglib-6qiyf/branch/master) | Library to handle and parse data from `.pak` files       |
| [**PangLib.PET**](PangLib.PET/)               | [![Nuget](https://img.shields.io/nuget/v/PangLib.PET.svg)](https://www.nuget.org/packages/PangLib.PET/)               | [![Build status](https://ci.appveyor.com/api/projects/status/7gjip9py34vnmtv1/branch/master?svg=true)](https://ci.appveyor.com/project/pixeldesu/panglib/branch/master)       | Library to handle and parse data from `.*pet` files      |
| [**PangLib.PSP.NOP**](PangLib.PSP.NOP/)       | [![Nuget](https://img.shields.io/nuget/v/PangLib.PSP.NOP.svg)](https://www.nuget.org/packages/PangLib.PSP.NOP/)       | [![Build status](https://ci.appveyor.com/api/projects/status/749685jg9xx136h8/branch/master?svg=true)](https://ci.appveyor.com/project/pixeldesu/panglib-rcueu/branch/master) | Library to handle and parse data from PSP `.nop` files   |
| [**PangLib.PSP.PAK**](PangLib.PSP.PAK/)       | [![Nuget](https://img.shields.io/nuget/v/PangLib.PSP.PAK.svg)](https://www.nuget.org/packages/PangLib.PSP.PAK/)       | [![Build status](https://ci.appveyor.com/api/projects/status/t8oduj8k1te2296o/branch/master?svg=true)](https://ci.appveyor.com/project/pixeldesu/panglib-uf9he/branch/master) | Library to handle and parse data from PSP `.pak` files   |
| [**PangLib.PSP.QST**](PangLib.PSP.QST/)       | [![Nuget](https://img.shields.io/nuget/v/PangLib.PSP.QST.svg)](https://www.nuget.org/packages/PangLib.PSP.QST/)       | [![Build status](https://ci.appveyor.com/api/projects/status/bmaj090yp6i3fdu3/branch/master?svg=true)](https://ci.appveyor.com/project/pixeldesu/panglib-n2p01/branch/master) | Library to handle and parse data from PSP `.qst` files   |
| [**PangLib.UCC**](PangLib.UCC/)               | [![Nuget](https://img.shields.io/nuget/v/PangLib.UCC.svg)](https://www.nuget.org/packages/PangLib.UCC/)               | [![Build status](https://ci.appveyor.com/api/projects/status/nqxjdr7pem7a9pv9/branch/master?svg=true)](https://ci.appveyor.com/project/pixeldesu/panglib-9je33/branch/master) | Library to handle and parse data from SelfDesign files   |
| [**PangLib.UpdateList**](PangLib.UpdateList/) | [![Nuget](https://img.shields.io/nuget/v/PangLib.UpdateList.svg)](https://www.nuget.org/packages/PangLib.UpdateList/) | [![Build status](https://ci.appveyor.com/api/projects/status/v1iexyfax1jc790s/branch/master?svg=true)](https://ci.appveyor.com/project/pixeldesu/panglib-njuqy/branch/master) | Library to handle and parse data from `updatelist` files |
| [**PangLib.Wii.ECB**](PangLib.Wii.ECB/)       | [![Nuget](https://img.shields.io/nuget/v/PangLib.Wii.ECB.svg)](https://www.nuget.org/packages/PangLib.Wii.ECB/)       | [![Build status](https://ci.appveyor.com/api/projects/status/divi17vkamgtmqko/branch/master?svg=true)](https://ci.appveyor.com/project/pixeldesu/panglib-3511b/branch/master) | Library to handle and parse data from Wii `.ECB` files   |
| [**PangLib.Utilities**](PangLib.Utilities/)   | [![Nuget](https://img.shields.io/nuget/v/PangLib.Utilities.svg)](https://www.nuget.org/packages/PangLib.Utilities/)   | [![Build status](https://ci.appveyor.com/api/projects/status/1eohtvn6tp6t89ed/branch/master?svg=true)](https://ci.appveyor.com/project/pixeldesu/panglib-aan6t/branch/master) | Common utilities used in other `PangLib` libraries       |

## Building

To build PangLib or any of the libraries inside it, you need, just as for using it, the [.NET Core SDK](https://www.microsoft.com/net/download).

Once the SDK is available on your system to use, you can either run the following commands in the project root to build every library from the solution,
or navigate to a subfolder (e.g. `PangLib.PET/`) and execute them there:

```
$ dotnet restore
$ dotnet build
```

If the commands run successfully, you now have compiled libraries available at `[library-name]/bin/Debug/netstandard2.0/[arch]`

To quickly test changes or use your local copy of a PangLib library in a project, you can run the following command to add 
a reference:

```
$ dotnet add reference [path to .csproj file of desired library]
```

This will now allow you to change the code of the library, and of your program and once you build your program, it will also
build the referenced library again, so you don't have to manually include a built library or publish it to Nuget yourself.

## Contributing

Want to contribute? **Awesome!**

You can contribute in many ways, like:

- Opening an issue if a problem with a library occurs.
- Opening an issue for a feature request, when a library is missing something you need.
- Opening an issue for a library request, if you need handling for another format.

Of course you can already contribute code if you are a developer, adding features, additional libraries and more, I'm
pretty open to anything, as long as it is related to Pangya and the addition is reasonable!

### Discuss on other Websites

Forum posts allowing for engagement and feedback on PangLib:

- [pangya.community](https://pangya.community/t/panglib-a-toolchain-for-pangya-files/22)
- [RageZone](http://forum.ragezone.com/f513/panglib-set-libraries-pangya-game-1162203/)

## Documentation

Documentation on the parsed file formats can be found at [docs.pangya.golf](https://docs.pangya.golf)

## License

This project is licensed under the AGPL-3.0
