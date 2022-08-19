---
id: osx.pbcopy
title: Pbcopy
desc: ''
updated: 1660882076207
created: 1660882076207
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pbcopy

> Copy data from stdin to the clipboard.
> More information: <https://ss64.com/osx/pbcopy.html>.

- Place the contents of a specific file in the clipboard:

`pbcopy < {{path/to/file}}`

- Place the results of a specific command in the clipboard:

`find . -type t -name "*.png" | pbcopy`

