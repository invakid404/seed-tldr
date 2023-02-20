---
id: windows.resolve-path
title: Resolve Path
desc: ''
updated: 1676881477682
created: 1676881477682
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# Resolve-Path

> Resolves the wildcard characters in a path, and displays the path contents.
> This command can only be used through PowerShell.
> More information: <https://learn.microsoft.com/powershell/module/microsoft.powershell.management/resolve-path>.

- Resolve the home folder path:

`Resolve-Path {{~}}`

- Resolve a UNC path:

`Resolve-Path -Path "\\{{hostname}}\{{path\to\file}}"`

- Get relative paths:

`Resolve-Path -Path {{path\to\file_or_directory}} -Relative`

