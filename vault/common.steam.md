---
id: common.steam
title: Steam
desc: ''
updated: 1670142131010
created: 1670142131010
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# steam

> Video game platform by Valve.
> More information: <https://developer.valvesoftware.com/wiki/Command_Line_Options>.

- Launch Steam, printing debug messages to `stdout`:

`steam`

- Launch Steam and enable its in-app debug console tab:

`steam -console`

- Enable and open the Steam console tab in a running Steam instance:

`steam steam://open/console`

- Log into Steam with the specified credentials:

`steam -login {{username}} {{password}}`

- Launch Steam in Big Picture Mode:

`steam -tenfoot`

- Exit Steam:

`steam -shutdown`

