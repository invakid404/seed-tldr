---
id: osx.vm_stat
title: Vm_stat
desc: ''
updated: 1656591837678
created: 1656591837678
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# vm_stat

> Show virtual memory statistics.
> More information: <https://www.unix.com/man-page/osx/1/vm_stat>.

- Display virtual memory statistics:

`vm_stat`

- Display reports every 2 seconds for 5 times:

`vm_stat -c {{5}} {{2}}`

