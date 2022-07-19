---
id: linux.smem
title: Smem
desc: ''
updated: 1658240355811
created: 1658240355811
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# smem

> Print memory usage for programs.
> More information: <https://manned.org/smem>.

- Print memory usage for current processes:

`smem`

- Print memory usage for current processes for a every user on a system:

`smem --users`

- Print memory usage for current processes for a specified user:

`smem --userfilter {{username}}`

- Print system memory information:

`smem --system`

