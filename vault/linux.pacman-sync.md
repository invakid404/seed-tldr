---
id: linux.pacman-sync
title: Pacman Sync
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
# pacman --sync

> Arch Linux package manager utility.
> See also: `pacman`.
> More information: <https://man.archlinux.org/man/pacman.8>.

- Install a new package:

`sudo pacman --sync {{package}}`

- Synchronize and update all packages (add `--downloadonly` to download the packages and not update them):

`sudo pacman --sync --refresh --sysupgrade`

- Update all packages and install a new one without prompting:

`sudo pacman --sync --refresh --sysupgrade --noconfirm {{package}}`

- Search the package database for a regular expression or keyword:

`pacman --sync --search "{{search_pattern}}"`

- Display information about a package:

`pacman --sync --info {{package}}`

- Overwrite conflicting files during a package update:

`sudo pacman --sync --refresh --sysupgrade --overwrite {{path/to/file}}`

- Synchronize and update all packages, but ignore a specific package (can be used more than once):

`sudo pacman --sync --refresh --sysupgrade --ignore {{package}}`

- Remove not installed packages and unused repositories from the cache (use two `--clean` flags to clean all packages):

`sudo pacman --sync --clean`

