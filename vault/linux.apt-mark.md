---
id: linux.apt-mark
title: Apt Mark
desc: ''
updated: 1693073888612
created: 1693073888612
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# apt-mark

> Utility to change the status of installed packages.
> More information: <https://manpages.debian.org/latest/apt/apt-mark.8.html>.

- Mark a package as automatically installed:

`sudo apt-mark auto {{package}}`

- Hold a package at its current version and prevent updates to it:

`sudo apt-mark hold {{package}}`

- Allow a package to be updated again:

`sudo apt-mark unhold {{package}}`

- Show manually installed packages:

`apt-mark showmanual`

- Show held packages that aren't being updated:

`apt-mark showhold`

