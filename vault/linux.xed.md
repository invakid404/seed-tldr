---
id: linux.xed
title: Xed
desc: ''
updated: 1656591837667
created: 1656591837667
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# xed

> Edit files in Cinnamon desktop environment.
> More information: <https://github.com/linuxmint/xed>.

- Start the editor:

`xed`

- Open specific files:

`xed {{path/to/file1 path/to/file2 ...}}`

- Open files using a specific encoding:

`xed --encoding {{WINDOWS-1252}} {{path/to/file1 path/to/file2 ...}}`

- Print all supported encodings:

`xed --list-encodings`

- Open a file and go to a specific line:

`xed +{{10}} {{path/to/file}}`

