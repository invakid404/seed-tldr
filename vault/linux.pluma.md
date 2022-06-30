---
id: linux.pluma
title: Pluma
desc: ''
updated: 1656591837644
created: 1656591837644
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pluma

> Edit files in MATE desktop environment.
> More information: <https://manned.org/pluma>.

- Start the editor:

`pluma`

- Open specific documents:

`pluma {{path/to/file1 path/to/file2 ...}}`

- Open documents using a specific encoding:

`pluma --encoding {{WINDOWS-1252}} {{path/to/file1 path/to/file2 ...}}`

- Print all supported encodings:

`pluma --list-encodings`

- Open document and go to a specific line:

`pluma +{{10}} {{path/to/file}}`

