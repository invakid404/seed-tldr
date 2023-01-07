---
id: common.ksh
title: Ksh
desc: ''
updated: 1673108584868
created: 1673108584868
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ksh

> Korn Shell, a Bash-compatible command-line interpreter.
> See also: `histexpand`.
> More information: <http://kornshell.com>.

- Start an interactive shell session:

`ksh`

- Execute specific [c]ommands:

`ksh -c "{{echo 'ksh is executed'}}"`

- Execute a specific script:

`ksh {{path/to/script.ksh}}`

- Check a specific script for syntax errors without executing it:

`ksh -n {{path/to/script.ksh}}`

- Execute a specific script, printing each command in the script before executing it:

`ksh -x {{path/to/script.ksh}}`

