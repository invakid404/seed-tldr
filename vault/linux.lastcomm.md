---
id: linux.lastcomm
title: Lastcomm
desc: ''
updated: 1684034192346
created: 1684034192346
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# lastcomm

> Show last commands executed.
> More information: <https://manpages.debian.org/latest/acct/lastcomm.1.en.html>.

- Print information about all the commands in the acct (record file):

`lastcomm`

- Display commands executed by a given user:

`lastcomm --user {{user}}`

- Display information about a given command executed on the system:

`lastcomm --command {{command}}`

- Display information about commands executed on a given terminal:

`lastcomm --tty {{terminal_name}}`

