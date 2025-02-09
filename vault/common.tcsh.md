---
id: common.tcsh
title: Tcsh
desc: ''
updated: 1685473997362
created: 1685473997362
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# tcsh

> C shell with file name completion and command-line editing.
> See also: `csh`.
> More information: <https://manned.org/tcsh>.

- Start an interactive shell session:

`tcsh`

- Start an interactive shell session without loading startup configs:

`tcsh -f`

- Execute specific [c]ommands:

`tcsh -c "{{echo 'tcsh is executed'}}"`

- Execute a specific script:

`tcsh {{path/to/script.tcsh}}`

- Check a specific script for syntax errors:

`tcsh -n {{path/to/script.tcsh}}`

- Execute specific commands from `stdin`:

`{{echo "echo 'tcsh is executed'"}} | tcsh`

