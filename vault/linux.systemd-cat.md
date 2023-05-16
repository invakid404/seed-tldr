---
id: linux.systemd-cat
title: Systemd Cat
desc: ''
updated: 1684214116422
created: 1684214116422
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# systemd-cat

> Connect a pipeline or program's output streams with the systemd journal.
> More information: <https://www.freedesktop.org/software/systemd/man/systemd-cat.html>.

- Write the output of the specified command to the journal (both output streams are captured):

`systemd-cat {{command}}`

- Write the output of a pipeline to the journal (`stderr` stays connected to the terminal):

`{{command}} | systemd-cat`

