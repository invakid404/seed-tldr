---
id: linux.unshare
title: Unshare
desc: ''
updated: 1656591837658
created: 1656591837658
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# unshare

> Execute a command in new user-defined namespaces.
> More information: <https://www.kernel.org/doc/html/latest/userspace-api/unshare.html>.

- Execute a command without sharing access to connected networks:

`unshare --net {{command}} {{command_arguments}}`

- Execute a command as a child process without sharing mounts, processes, or networks:

`unshare --mount --pid --net --fork {{command}} {{command_arguments}}`

