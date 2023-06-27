---
id: common.diskonaut
title: Diskonaut
desc: ''
updated: 1687904232799
created: 1687904232799
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# diskonaut

> Terminal disk space navigator, written in Rust.
> More information: <https://github.com/imsnif/diskonaut>.

- Start `diskonaut` in the current directory:

`diskonaut`

- Start `diskonaut` in a specific directory:

`diskonaut {{path/to/directory}}`

- Show file sizes rather than their block usage on the disk:

`diskonaut --apparent-size {{path/to/directory}}`

- Disable deletion confirmation:

`diskonaut --disable-delete-confirmation`

