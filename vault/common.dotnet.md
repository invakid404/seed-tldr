---
id: common.dotnet
title: Dotnet
desc: ''
updated: 1664897373986
created: 1664897373986
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# dotnet

> Cross platform .NET command-line tools for .NET Core.
> Some subcommands such as `dotnet build` have their own usage documentation.
> More information: <https://learn.microsoft.com/dotnet/core/tools>.

- Initialize a new .NET project:

`dotnet new {{template_short_name}}`

- Restore NuGet packages:

`dotnet restore`

- Build and execute the .NET project in the current directory:

`dotnet run`

- Run a packaged dotnet application (only needs the runtime, the rest of the commands require the .NET Core SDK installed):

`dotnet {{path/to/application.dll}}`

