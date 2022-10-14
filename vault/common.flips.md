---
id: common.flips
title: Flips
desc: ''
updated: 1665715012556
created: 1665715012556
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# flips

> Create and apply patches for IPS and BPS files.
> More information: <https://github.com/Alcaro/Flips>.

- Start Flips to create and apply patches interactively:

`flips`

- Apply a patch and create a new ROM file:

`flips --apply {{patch.bps}} {{rom.smc}} {{hack.smc}}`

- Create a patch from two ROMs:

`flips --create {{rom.smc}} {{hack.smc}} {{patch.bps}}`

