---
id: osx.cot
title: Cot
desc: ''
updated: 1658421007964
created: 1658421007964
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

`cot --line {{line_number}} --column {{column_number}} {{path/to/file}}`

