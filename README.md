# XSharpX

XSharpX is a general library for functional programming using .NET languages.

It provides purely functional data structures to complement those from
the BCEL. There is an intention is to integrate with several .NET
languages such as [F#](http://research.microsoft.com/en-us/projects/fsharp/),
[Cω](http://research.microsoft.com/en-us/um/cambridge/projects/comega/)
and [Nemerle](http://nemerle.org/About/) for the purpose of demonstrating
capability. At this moment, XSharpX uses C# exclusively for implementation.

## Installation

TODO: This section will be true after the package is built and uploaded to nuget.org, pending review of the package metadata

Nuget packages of stable builds are available on nuget.org, with package id XSharpX. The latest version is pre-release version 1.0.0-RC

Install using NuGet with

```
nuget install XSharpX -prerelease
```

in Visual Studio from the package-management console with

```
install-package XSharpX -IncludePrerelease
```

or in Visual Studio from the NuGet Package Manager GUI

## Quick Start

```c#
using XSharpX;
// ...
```

## Building

Build using the dotnet core. The project uses tools version 15, for which you need core tools SDK 1.1 or higher, which can be installed from https://www.microsoft.com/net/core

Build the project from the root directory of the project with

```
dotnet build src/XSharpx/XSharpx.csproj
```

To build a nuget package in release configuration, build with

```
dotnet pack src/XSharpx/XSharpx.csproj -c:Release
```

build artifacts will be created in src/XSharpx/bin


## Support and Community

 * [Google Group xsharpx](https://groups.google.com/forum/?fromgroups#!forum/xsharpx)
 * [IRC, #xsharpx on Freenode](irc://irc.freenode.net/#xsharpx)
