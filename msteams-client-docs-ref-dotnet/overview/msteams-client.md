---
title: Microsoft Teams Framework (TeamsFx) .NET SDK reference
description: TeamsFx (Microsoft Teams Framework) .NET SDK is a NuGet package for Blazor projects that streamlines authentication and cloud service access
author: erikadoyle
ms.service: msteams
keywords: msteams framework sdk teamsfx .net teams toolkit sso
---
# Microsoft Teams Framework (TeamsFx) .NET SDK reference

The Microsoft Teams Framework (TeamsFx) .NET SDK is a NuGet package for Blazor projects that streamlines single sign-on (SSO) authentication and cloud service access (such as for Microsoft Graph or SQL databases) within Microsoft Teams apps.

The [TeamsFx SDK is also available for JavaScript/TypeScript](/microsoftteams/platform/toolkit/teamsfx-sdk).

## Getting started

Build Teams apps with Blazor and the TeamsFx .NET SDK using Teams Toolkit. [Visit the documentation to learn more](/microsoftteams/platform/toolkit/visual-studio-overview).

### Prerequisites

1. Install the `ASP.NET and web development` workload using the Visual Studio Installer.
2. Launch Visual Studio and create a new Blazor project.

## Usage

### How to get the package

1. Right-click on the project in Visual Studio and choose Manage NuGet Packages.
2. Search for `Microsoft.TeamsFx` and add it to the Blazor project.

Alternately, you can use the Package Manager.

```ps
> Install-Package Microsoft.TeamsFx
```

### How to choose version

For .NET 5 projects (VS 2019): Choose version < 0.3.0-rc.
For .NET 6 projects (VS 2022): Choose version >= 0.3.0-rc.

## Next steps

> [!div class="nextstepaction"]
> [View sample code](https://github.com/OfficeDev/TeamsFx/blob/dev/packages/dotnet-sdk/README.md#usage)
