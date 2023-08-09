---
id: linux.pkgctl
title: Pkgctl
desc: ''
updated: 1691562059174
created: 1691562059174
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pkgctl

> Unified command-line devtools frontend for Arch Linux.
> More information: <https://man.archlinux.org/man/pkgctl.1>.

- Download PKGBUILD of a package in a folder named `package_name`:

`pkgctl repo clone --protocol=https {{package_name}}`

