---
id: common.bash
title: Bash
desc: ''
updated: 1686237395786
created: 1686237395786
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# bash

> Bourne-Again SHell, an `sh`-compatible command-line interpreter.
> See also: `zsh`, `histexpand` (history expansion).
> More information: <https://gnu.org/software/bash/>.

- Start an interactive shell session:

`bash`

- Start an interactive shell session without loading startup configs:

`bash --norc`

- Execute specific [c]ommands:

`bash -c "{{echo 'bash is executed'}}"`

- Execute a specific script:

`bash {{path/to/script.sh}}`

- Execute a specific script while printing each command before executing it:

`bash -x {{path/to/script.sh}}`

- Execute a specific script and stop at the first [e]rror:

`bash -e {{path/to/script.sh}}`

- Execute specific commands from `stdin`:

`{{echo "echo 'bash is executed'"}} | bash`

- Start a [r]estricted shell session:

`bash -r`

