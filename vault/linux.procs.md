---
id: linux.procs
title: Procs
desc: ''
updated: 1670394233698
created: 1670394233698
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# procs

> Display information about the active processes.
> More information: <https://github.com/dalance/procs>.

- List all processes showing the PID, user, CPU usage, memory usage, and the command which started them:

`procs`

- List information about processes, if the commands which started them contain `zsh`:

`procs {{zsh}}`

- List information about all processes sorted by CPU time in [a]scending or [d]escending order:

`procs {{--sorta|--sortd}} cpu`

- List information about processes with either a PID, command, or user containing `41` or `firefox`:

`procs --or {{PID|command|user}} {{41}} {{firefox}}`

- List information about processes with both PID `41` and a command or user containing `zsh`:

`procs --and {{41}} {{zsh}}`

