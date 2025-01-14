---
id: linux.pkgmk
title: Pkgmk
desc: ''
updated: 1685843802283
created: 1685843802283
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pkgmk

> Make a binary package for use with pkgadd on CRUX.
> More information: <https://docs.oracle.com/cd/E88353_01/html/E37839/pkgmk-1.html>.

- Make and download a package:

`pkgmk -d`

- Install the package after making it:

`pkgmk -d -i`

- Upgrade the package after making it:

`pkgmk -d -u`

- Ignore the footprint when making a package:

`pkgmk -d -if`

- Ignore the MD5 sum when making a package:

`pkgmk -d -im`

- Update the package's footprint:

`pkgmk -uf`

