---
id: common.bindkey
title: Bindkey
desc: ''
updated: 1656591837428
created: 1656591837428
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# bindkey

> Add keybindings to Z-Shell.
> More information: <https://zsh.sourceforge.io/Guide/zshguide04.html>.

- Bind a hotkey to a specific command:

`bindkey "{{^k}}" {{kill-line}}`

- Bind a hotkey to a specific key sequence:

`bindkey -s '^o' 'cd ..\n'`

- View keymaps:

`bindkey -l`

- View the hotkey in a keymap:

`bindkey -M main`

