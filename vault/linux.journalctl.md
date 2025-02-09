---
id: linux.journalctl
title: Journalctl
desc: ''
updated: 1656591837629
created: 1656591837629
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# journalctl

> Query the systemd journal.
> More information: <https://manned.org/journalctl>.

- Show all messages with priority level 3 (errors) from this [b]oot:

`journalctl -b --priority={{3}}`

- Show all messages from last [b]oot:

`journalctl -b -1`

- Delete journal logs which are older than 2 days:

`journalctl --vacuum-time={{2d}}`

- [f]ollow new messages (like `tail -f` for traditional syslog):

`journalctl -f`

- Show all messages by a specific [u]nit:

`journalctl -u {{unit}}`

- Filter messages within a time range (either timestamp or placeholders like "yesterday"):

`journalctl --since {{now|today|yesterday|tomorrow}} --until {{YYYY-MM-DD HH:MM:SS}}`

- Show all messages by a specific process:

`journalctl _PID={{pid}}`

- Show all messages by a specific executable:

`journalctl {{path/to/executable}}`

