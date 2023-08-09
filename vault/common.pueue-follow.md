---
id: common.pueue-follow
title: Pueue Follow
desc: ''
updated: 1691562059062
created: 1691562059062
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pueue follow

> Follow the output of a currently running task.
> See also: `pueue log`.
> More information: <https://github.com/Nukesor/pueue>.

- Follow the output of a task (`stdout` + `stderr`):

`pueue follow {{task_id}}`

- Follow `stderr` of a task:

`pueue follow --err {{task_id}}`

