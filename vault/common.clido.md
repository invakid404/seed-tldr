---
id: common.clido
title: Clido
desc: ''
updated: 1685859579985
created: 1685859579985
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# clido

> Save-state TODO app for the terminal.
> More information: <https://codeberg.org/Oglo12/clido/wiki>.

- Create a list:

`clido --new {{name}}`

- Load a list:

`clido --load {{name}}`

- Delete a list:

`clido --remove {{name}}`

- List all lists:

`clido --lists`

- Toggle autowrite:

`clido toggle-autowrite`

- Open a list in a text editor:

`clido edit {{text_editor}}`

- Display version:

`clido -v`

- Display help:

`clido -h`

