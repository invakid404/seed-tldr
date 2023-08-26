---
id: linux.pacman-database
title: Pacman Database
desc: ''
updated: 1693073888658
created: 1693073888658
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pacman --database

> Operate on the Arch Linux package database.
> Modify certain attributes of the installed packages.
> See also: `pacman`.
> More information: <https://man.archlinux.org/man/pacman.8>.

- Mark a package as implicitly installed:

`sudo pacman --database --asdeps {{package}}`

- Mark a package as explicitly installed:

`sudo pacman --database --asexplicit {{package}}`

- Check that all the package dependencies are installed:

`pacman --database --check`

- Check the repositories to ensure all specified dependencies are available:

`pacman --database --check --check`

- Display only error messages:

`pacman --database --check --quiet`

- Display help:

`pacman --database --help`

