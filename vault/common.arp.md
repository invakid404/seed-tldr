---
id: common.arp
title: Arp
desc: ''
updated: 1681146869072
created: 1681146869072
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# arp

> Show and manipulate your system's ARP cache.
> More information: <https://manned.org/arp>.

- Show the current ARP table:

`arp -a`

- Delete a specific entry:

`arp -d {{address}}`

- Create an entry in the ARP table:

`arp -s {{address}} {{mac_address}}`

