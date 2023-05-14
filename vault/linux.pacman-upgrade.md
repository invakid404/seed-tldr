---
id: linux.pacman-upgrade
title: Pacman Upgrade
desc: ''
updated: 1684067360696
created: 1684067360696
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pacman --upgrade

> Arch Linux package manager utility.
> See also: `pacman`.
> More information: <https://man.archlinux.org/man/pacman.8>.

- Install one or more packages from files:

`sudo pacman --upgrade {{path/to/package1.pkg.tar.zst}} {{path/to/package2.pkg.tar.zst}}`

- Install a package without prompting:

`sudo pacman --upgrade --noconfirm {{path/to/package.pkg.tar.zst}}`

- Overwrite conflicting files during a package installation:

`sudo pacman --upgrade --overwrite {{path/to/file}} {{path/to/package.pkg.tar.zst}}`

- Install a package, skipping the dependency version checks:

`sudo pacman --upgrade --nodeps {{path/to/package.pkg.tar.zst}}`

- List packages that would be affected (does not install any packages):

`pacman --upgrade --print {{path/to/package.pkg.tar.zst}}`

- Display help:

`pacman --upgrade --help`

