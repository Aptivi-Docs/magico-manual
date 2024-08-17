---
description: Welcome to Magico!
---

# 👋 Welcome

Welcome to Magico! It's a C# library that allows you to pull some magical tricks on a variety of things, such as `IEnumerable` instances and file magic investigation. To use this library, go to any page in the left side of the screen.

{% hint style="warning" %}
Starting from Magico v1.1.1, 32-bit support has been removed. If you still want to target 32-bit platforms in your applications, you can use v1.1.0.1 or older, but you'll miss out on all the new features and the improvements. We advise you to take out 32-bit support as soon as you can.
{% endhint %}

## Installation

This library is very easy to install. It's available at [NuGet](https://www.nuget.org/packages/SpecProbe/). Just follow these steps:

1. Open your project file (`.csproj` or `.fsproj`)
2. Place the `PackageReference` line on a property group like so:
   * `<PackageReference Include="Magico" Version="x.x.x" />`
   * ...where `Version` is the current version of the library
3. Run a package restore using `dotnet restore`

If you follow these steps correctly, you should be able to use this library's functions.
