---
id: osx.dmesg
title: Dmesg
desc: ''
updated: 1691562059208
created: 1691562059208
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# dmesg

> Write the kernel messages to `stdout`.
> More information: <https://www.manpagez.com/man/8/dmesg/>.

- Show kernel messages:

`dmesg`

- Show how much physical memory is available on this system:

`dmesg | grep -i memory`

- Show kernel messages 1 page at a time:

`dmesg | less`

