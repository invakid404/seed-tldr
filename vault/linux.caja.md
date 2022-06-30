---
id: linux.caja
title: Caja
desc: ''
updated: 1656591837608
created: 1656591837608
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# caja

> Manages files and directories in MATE desktop environment.
> More information: <https://manned.org/caja>.

- Open the current user home directory:

`caja`

- Open specific directories in separate windows:

`caja {{path/to/directory1 path/to/directory2 ...}}`

- Open specific directories in tabs:

`caja --tabs {{path/to/directory1 path/to/directory2 ...}}`

- Open a directory with a specific window size:

`caja --geometry={{600}}x{{400}} {{path/to/directory}}`

- Close all windows:

`caja --quit`

