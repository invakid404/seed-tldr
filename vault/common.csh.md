---
id: common.csh
title: Csh
desc: ''
updated: 1656591837439
created: 1656591837439
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# csh

> The shell (command interpreter) with C-like syntax.
> See also: `tcsh`.
> More information: <https://www.mkssoftware.com/docs/man1/csh.1.asp>.

- Start an interactive shell session:

`csh`

- Start an interactive shell session without loading startup configs:

`csh -f`

- Execute specific [c]ommands:

`csh -c "{{echo 'csh is executed'}}"`

- Execute a specific script:

`csh {{path/to/script.csh}}`

