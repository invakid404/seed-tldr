---
id: osx.cot
title: Cot
desc: ''
updated: 1676812918782
created: 1676812918782
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# cot

> The Plain-Text Editor for macOS.
> More information: <https://coteditor.com/>.

- Start CotEditor:

`cot`

- Open specific files:

`cot {{path/to/file1 path/to/file2 ...}}`

- Open a new blank document:

`cot --new`

- Open a specific file and block the terminal until it is closed:

`cot --wait {{path/to/file}}`

- Open a specific file with the cursor at a specific line and column:

`cot --line {{1}} --column {{80}} {{path/to/file}}`

