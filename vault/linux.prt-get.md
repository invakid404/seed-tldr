---
id: linux.prt-get
title: Prt Get
desc: ''
updated: 1693073888663
created: 1693073888663
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# prt-get

> The CRUX package manager.
> More information: <https://crux.nu/doc/prt-get%20-%20User%20Manual.html>.

- Install a package:

`prt-get install {{package}}`

- Install a package with dependency handling:

`prt-get depinst {{package}}`

- Update a package manually:

`prt-get upgrade {{package}}`

- Remove a package:

`prt-get remove {{package}}`

- Upgrade the system from the local ports tree:

`prt-get sysup`

- Search the ports tree:

`prt-get search {{query}}`

- Search for a file in a package:

`prt-get fsearch {{file}}`

