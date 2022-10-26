---
id: linux.daemon
title: Daemon
desc: ''
updated: 1666779932538
created: 1666779932538
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# daemon

> Run processes into daemons.
> More information: <https://manned.org/man/daemon.1>.

- Run a command as a daemon:

`daemon --name="{{name}}" {{command}}`

- Run a command as a daemon which will restart if the command crashes:

`daemon --name="{{name}}" --respawn {{command}}`

- Run a command as a daemon which will restart if it crashes, with two attempts every 10 seconds:

`daemon --name="{{name}}" --respawn --attempts=2 --delay=10 {{command}}`

- Run a command as a daemon, writing logs to a specific file:

`daemon --name="{{name}}" --errlog={{path/to/file.log}} {{command}}`

- Kill a daemon (SIGTERM):

`daemon --name="{{name}}" --stop`

- List daemons:

`daemon --list`

