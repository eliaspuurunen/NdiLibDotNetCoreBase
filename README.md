# NDI® C# Wrapper for .NET 7 (.NET Core)

This library provides a wrapper to the NDI libraries for Windows, macOS, and Linux.

![GitHub](https://img.shields.io/github/license/eliaspuurunen/NdiLibDotNetCoreBase) ![Nuget](https://img.shields.io/nuget/v/NDILibDotNetCoreBase)

Install via dotnet:
`dotnet add package NDILibDotNetCoreBase --version 2023.11.7.3`

Projects this library is used by:
- [Tractus Multiview for NDI](https://multiviewforndi.com/)
- [Elias' NDI Utiliites](https://agfinn.gumroad.com/)

Based on the .NET Wrapper for C# provided by the NDI SDK.

NDI® is a registered trademark of Vizrt.

### Linux Notes

`libndi.so` is searched for in the app launch path. Make sure the correct library for your platform is copied there.

