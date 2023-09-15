---
id: common.!
title: '!'
desc: ''
updated: 1694751539765
created: 1694751539765
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# Exclamation mark

> Bash builtin to substitute with a command found in history.
> More information: <https://www.gnu.org/software/bash/manual/bash.html#Event-Designators>.

- Substitute with the previous command and run it with sudo:

`sudo !!`

- Substitute with a command based on its line number found with `history`:

`!{{number}}`

- Substitute with a command that was used a specified number of lines back:

`!-{{number}}`

- Substitute with the most recent command that starts with `string`:

`!{{string}}`

