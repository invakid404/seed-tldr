---
id: linux.apx-pkgmanagers
title: Apx Pkgmanagers
desc: ''
updated: 1695183597776
created: 1695183597776
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# apx pkgmanagers

> Manage package managers in `apx`.
> Note: user-created package manager configurations are stored in `~/.local/share/apx/pkgmanagers`.
> More information: <https://github.com/Vanilla-OS/apx>.

- Interactively create a new package manager configuration:

`apx pkgmanagers create`

- List all available package manager confirgurations:

`apx pkgmanagers list`

- Remove a package manager configuration:

`apx pkgmanagers rm --name {{string}}`

- Display information about a specific package manager:

`apx pkgmanagers show {{name}}`

