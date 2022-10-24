---
id: linux.loadkeys
title: Loadkeys
desc: ''
updated: 1666579143452
created: 1666579143452
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# loadkeys

> Load the kernel keymap for the console.
> More information: <https://manned.org/loadkeys>.

- Load a default keymap:

`loadkeys --default`

- Create a kernel source table:

`loadkeys --mktable`

- Create a binary keymap:

`loadkeys --bkeymap`

- Search and parse keymap without action:

`loadkeys --parse`

- Load the keymap suppressing all output:

`loadkeys --quiet`

- Display help:

`loadkeys --help`

- Display version:

`loadkeys --version`

