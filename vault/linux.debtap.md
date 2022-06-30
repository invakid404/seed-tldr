---
id: linux.debtap
title: Debtap
desc: ''
updated: 1656591837612
created: 1656591837612
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# debtap

> Convert Debian packages into Arch Linux packages.
> See also: `pacman-upgrade`.
> More information: <https://github.com/helixarch/debtap>.

- Update debtap database (before the first run):

`sudo debtap --update`

- Convert the specified package:

`debtap {{path/to/package.deb}}`

- Convert the specified package bypassing all questions, except for editing metadata files:

`debtap --quiet {{path/to/package.deb}}`

- Generate a PKGBUILD file:

`debtap --pkgbuild {{path/to/package.deb}}`

