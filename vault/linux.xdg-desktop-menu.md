---
id: linux.xdg-desktop-menu
title: Xdg Desktop Menu
desc: ''
updated: 1656591837666
created: 1656591837666
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# xdg-desktop-menu

> Command-line tool for installing or uninstalling desktop menu items.
> More information: <https://manned.org/xdg-desktop-menu>.

- Install an application to the desktop menu system:

`xdg-desktop-menu install {{path/to/file.desktop}}`

- Install an application to the desktop menu system with the vendor prefix check disabled:

`xdg-desktop-menu install --novendor {{path/to/file.desktop}}`

- Uninstall an application from the desktop menu system:

`xdg-desktop-menu uninstall {{path/to/file.desktop}}`

- Force an update of the desktop menu system:

`xdg-desktop-menu forceupdate --mode {{user|system}}`

