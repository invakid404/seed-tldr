---
id: linux.dget
title: Dget
desc: ''
updated: 1693073888624
created: 1693073888624
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# dget

> Download Debian packages.
> More information: <https://manpages.debian.org/latest/devscripts/dget.1.en.html>.

- Download a binary package:

`dget {{package}}`

- Download and extract a package source from its `.dsc` file:

`dget {{http://deb.debian.org/debian/pool/main/h/haskell-tldr/haskell-tldr_0.4.0-2.dsc}}`

- Download a package source tarball from its `.dsc` file but don't extract it:

`dget -d {{http://deb.debian.org/debian/pool/main/h/haskell-tldr/haskell-tldr_0.4.0-2.dsc}}`

