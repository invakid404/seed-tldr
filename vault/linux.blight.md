---
id: linux.blight
title: Blight
desc: ''
updated: 1665294081863
created: 1665294081863
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# blight

> Utility for changing the display brightness.
> More information: <https://github.com/gutjuri/blight>.

- Set display brightness to 50%:

`blight set {{50}} -r`

- Show current display brightness:

`blight show`

- Print maximum display brightness:

`blight max`

- Increase display brightness in %:

`blight inc {{number}} -r`

- Decrease display brightness with internal units:

`blight dec {{number}}`

