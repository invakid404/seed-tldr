---
id: common.sh
title: Sh
desc: ''
updated: 1670142131005
created: 1670142131005
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# sh

> Bourne shell, the standard command language interpreter.
> See also `histexpand` for history expansion.
> More information: <https://manned.org/sh>.

- Start an interactive shell session:

`sh`

- Execute a command and then exit:

`sh -c "{{command}}"`

- Execute a script:

`sh {{path/to/script.sh}}`

- Read and execute commands from `stdin`:

`sh -s`

