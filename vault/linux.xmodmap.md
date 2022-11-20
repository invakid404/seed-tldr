---
id: linux.xmodmap
title: Xmodmap
desc: ''
updated: 1668942963927
created: 1668942963927
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# xmodmap

> Utility for modifying keymaps and pointer button mappings in X.
> More information: <https://manned.org/xmodmap>.

- Swap left-click and right-click on the pointer:

`xmodmap -e 'pointer = 3 2 1'`

- Reassign a key on the keyboard to another key:

`xmodmap -e 'keycode {{keycode}} = {{keyname}}'`

- Disable a key on the keyboard:

`xmodmap -e 'keycode {{keycode}} ='`

- Execute all xmodmap expressions in the specified file:

`xmodmap {{path/to/file}}`

