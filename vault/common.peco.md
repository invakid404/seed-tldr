---
id: common.peco
title: Peco
desc: ''
updated: 1687904232882
created: 1687904232882
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# peco

> Interactive filtering tool.
> More information: <https://github.com/peco/peco>.

- Start `peco` on all files in the specified directory:

`find {{path/to/directory}} -type f | peco`

- Start `peco` for running processes:

`ps aux | peco`

- Start `peco` with a specified query:

`peco --query "{{query}}"`

