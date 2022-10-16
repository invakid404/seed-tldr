---
id: windows.winget
title: Winget
desc: ''
updated: 1665899330063
created: 1665899330063
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# winget

> Windows Package Manager CLI.
> More information: <https://learn.microsoft.com/windows/package-manager/winget>.

- Install a package:

`winget install {{package}}`

- Display information about a package:

`winget show {{package}}`

- Search for a package:

`winget search {{package}}`

- Upgrade all packages to latest versions:

`winget upgrade --all`

- List all packages installed that can be managed with winget:

`winget list --source winget`

