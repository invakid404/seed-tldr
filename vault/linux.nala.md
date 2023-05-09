---
id: linux.nala
title: Nala
desc: ''
updated: 1683627475080
created: 1683627475080
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# nala

> Package management Utility.
> Wrapper for the `apt` package manager.
> More information: <https://gitlab.com/volian/nala>.

- Install a package, or update it to the latest available version:

`sudo nala install {{package}}`

- Remove a package:

`sudo nala remove {{package}}`

- Remove a package and its configuration files:

`nala purge {{package}}`

- Search package names and descriptions using a word, regex (default) or glob:

`nala search "{{pattern}}"`

- Update the list of available packages and upgrade the system:

`sudo nala upgrade`

- Remove all unused packages and dependencies from your system:

`sudo nala autoremove`

- Fetch fast mirrors to improve download speeds:

`sudo nala fetch`

- Display the history of all transactions:

`nala history`

