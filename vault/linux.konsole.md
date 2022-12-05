---
id: linux.konsole
title: Konsole
desc: ''
updated: 1670224629829
created: 1670224629829
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# konsole

> KDE's terminal emulator.
> More information: <https://docs.kde.org/trunk5/en/konsole/konsole/command-line-options.html>.

- Open the terminal in a specific directory:

`konsole --workdir {{path/to/directory}}`

- [e]xecute a specific command and don't close the window after it exits:

`konsole --noclose -e "{{command}}"`

- Open a new tab:

`konsole --new-tab`

- Open the terminal in the background and bring to the front when `Ctrl+Shift+F12` is pressed:

`konsole --background-mode`

