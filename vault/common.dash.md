---
id: common.dash
title: Dash
desc: ''
updated: 1670142130895
created: 1670142130895
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# dash

> Debian Almquist Shell, a modern, POSIX-compliant implementation of `sh` (not Bash-compatible).
> More information: <https://manned.org/dash>.

- Start an interactive shell session:

`dash`

- Execute specific [c]ommands:

`dash -c "{{echo 'dash is executed'}}"`

- Execute a specific script:

`dash {{path/to/script.sh}}`

- Check a specific script for syntax errors:

`dash -n {{path/to/script.sh}}`

- Execute a specific script while printing each command before executing it:

`dash -x {{path/to/script.sh}}`

- Execute a specific script and stop at the first [e]rror:

`dash -e {{path/to/script.sh}}`

- Execute specific commands from `stdin`:

`{{echo "echo 'dash is executed'"}} | dash`

