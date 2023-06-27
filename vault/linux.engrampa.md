---
id: linux.engrampa
title: Engrampa
desc: ''
updated: 1687904232954
created: 1687904232954
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# engrampa

> Package files into zip/tar file in MATE desktop environment.
> See also: `zip`, `tar`.
> More information: <https://github.com/mate-desktop/engrampa>.

- Start Engrampa:

`engrampa`

- Open specific archives:

`engrampa {{path/to/archive1.tar path/to/archive2.tar ...}}`

- Archive specific files and/or directories recursively:

`engrampa --add-to={{path/to/compressed.tar}} {{path/to/file_or_directory1 path/to/file_or_directory2 ...}}`

- Extract files and/or directories from archives to a specific path:

`engrampa --extract-to={{path/to/directory}} {{path/to/archive1.tar path/to/archive2.tar ...}}`

