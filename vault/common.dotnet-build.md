---
id: common.dotnet-build
title: Dotnet Build
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
# dotnet build

> Builds a .NET application and its dependencies.
> More information: <https://learn.microsoft.com/dotnet/core/tools/dotnet-build>.

- Compile the project or solution in the current directory:

`dotnet build`

- Compile a .NET project or solution in debug mode:

`dotnet build {{path/to/project_or_solution}}`

- Compile in release mode:

`dotnet build --configuration {{Release}}`

- Compile without restoring dependencies:

`dotnet build --no-restore`

- Compile with a specific verbosity level:

`dotnet build --verbosity {{quiet|minimal|normal|detailed|diagnostic}}`

- Compile for a specific runtime:

`dotnet build --runtime {{runtime_identifier}}`

- Specify the output directory:

`dotnet build --output {{path/to/directory}}`

