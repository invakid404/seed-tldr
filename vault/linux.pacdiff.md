---
id: linux.pacdiff
title: Pacdiff
desc: ''
updated: 1664720595250
created: 1664720595250
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pacdiff

> Maintenance utility for `.pacorig`, `.pacnew` and `.pacsave` files created by `pacman`.
> More information: <https://man.archlinux.org/man/pacdiff>.

- Review files that need maintenance in interactive mode:

`pacdiff`

- Use sudo and sudoedit to remove and merge files:

`pacdiff --sudo`

- Review files needing maintenance, creating `.bak`ups of the original if you `(O)verwrite`:

`pacdiff --sudo --backup`

- Use a specific editor to view and merge configuration files (default is `vim -d`):

`DIFFPROG={{editor}} pacdiff`

- Scan for configuration files with `locate` instead of using pacman database:

`pacdiff --locate`

- Display help:

`pacdiff --help`

