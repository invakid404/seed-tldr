---
id: linux.pkgctl-diff
title: Pkgctl Diff
desc: ''
updated: 1692202829898
created: 1692202829898
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pkgctl diff

> Compare package files using different modes.
> See also: `pkgctl`.
> More information: <https://man.archlinux.org/man/pkgctl-diff.1>.

- Compare package files in tar content [l]ist different mode (default):

`pkgctl diff --list {{path/to/file|pkgname}}`

- Compare package files in [d]iffoscope different mode:

`pkgctl diff --diffoscope {{path/to/file|pkgname}}`

- Compare package files in `.PKGINFO` different mode:

`pkgctl diff --pkginfo {{path/to/file|pkgname}}`

- Compare package files in `.BUILDINFO` different mode:

`pkgctl diff --buildinfo {{path/to/file|pkgname}}`

