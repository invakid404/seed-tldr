---
id: linux.latte-dock
title: Latte Dock
desc: ''
updated: 1665260759027
created: 1665260759027
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# latte-dock

> Replacement dock for Plasma desktop.
> More information: <https://github.com/KDE/latte-dock>.

- Clear QML cache:

`latte-dock --clear-cache`

- Import and load default layout on startup:

`latte-dock --default-layout`

- Load a specific layout on startup:

`latte-dock --layout {{layout_name}}`

- Import and load a specific layout:

`latte-dock --import-layout {{path/to/file}}`

