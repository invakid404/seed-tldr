---
id: common.dircolors
title: Dircolors
desc: ''
updated: 1670145406941
created: 1670145406941
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# dircolors

> Output commands to set the LS_COLOR environment variable and style `ls`, `dir`, etc.
> More information: <https://www.gnu.org/software/coreutils/dircolors>.

- Output commands to set LS_COLOR using default colors:

`dircolors`

- Output commands to set LS_COLOR using colors from a file:

`dircolors {{path/to/file}}`

- Output commands for Bourne shell:

`dircolors --bourne-shell`

- Output commands for C shell:

`dircolors --c-shell`

- View the default colors for file types and extensions:

`dircolors --print-data`

