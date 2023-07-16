---
id: windows.scoop
title: Scoop
desc: ''
updated: 1689531679927
created: 1689531679927
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# scoop

> The Scoop package manager.
> More information: <https://scoop.sh>.

- Install a package:

`scoop install {{package}}`

- Remove a package:

`scoop uninstall {{package}}`

- Update all installed packages:

`scoop update --all`

- List installed packages:

`scoop list`

- Display information about a package:

`scoop info {{package}}`

- Search for a package:

`scoop search {{package}}`

- Remove old versions of all packages and clear the download cache:

`scoop cleanup --cache --all`

