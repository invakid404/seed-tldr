---
id: linux.loadkeys
title: Loadkeys
desc: ''
updated: 1666750046466
created: 1666750046466
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

- Load default keymap when an unusual keymap is loaded and `-` sign cannot be found:

`loadkeys defmap`

- Create a kernel source table:

`loadkeys --mktable`

- Create a binary keymap:

`loadkeys --bkeymap`

- Search and parse keymap without action:

`loadkeys --parse`

- Load the keymap suppressing all output:

`loadkeys --quiet`

- Load a keymap from the specified file for the console:

`loadkeys --console {{/dev/ttyN}} {{/path/to/file}}`

- Use standard names for keymaps of different locales:

`loadkeys --console {{/dev/ttyN}} {{uk}}`

