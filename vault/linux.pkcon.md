---
id: linux.pkcon
title: Pkcon
desc: ''
updated: 1667741501134
created: 1667741501134
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pkcon

> Command line client for PackageKit console program used by Discover and Gnome software and alternative to 'apt'.
> More information: <https://manned.org/pkcon>.

- Install a package:

`pkcon install {{package}}`

- Remove a package:

`pkcon remove {{package}}`

- Refresh the package cache:

`pkcon refresh`

- Update packages:

`pkcon update`

- Search for a specific package:

`pkcon search {{package}}`

- List all available packages:

`pkcon get-packages`

