---
id: linux.nmblookup
title: Nmblookup
desc: ''
updated: 1677449830810
created: 1677449830810
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# nmblookup

> Discover SMB shares.
> More information: <https://www.samba.org/samba/docs/current/man-html/nmblookup.1.html>.

- Find hosts in the local network with SMB shares:

`nmblookup -S '*'`

- Find hosts in the local network with SMB shares run by SAMBA:

`nmblookup --status __SAMBA__`

