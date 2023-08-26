---
id: linux.paru
title: Paru
desc: ''
updated: 1693073888659
created: 1693073888659
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# paru

> An AUR helper and pacman wrapper.
> More information: <https://github.com/Morganamilo/paru>.

- Interactively search for and install a package:

`paru {{package_name_or_search_term}}`

- Synchronize and update all packages:

`paru`

- Upgrade AUR packages:

`paru -Sua`

- Get information about a package:

`paru -Si {{package}}`

- Download `PKGBUILD` and other package source files from the AUR or ABS:

`paru --getpkgbuild {{package}}`

- Display the `PKGBUILD` file of a package:

`paru --getpkgbuild --print {{package}}`

