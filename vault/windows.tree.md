---
id: windows.tree
title: Tree
desc: ''
updated: 1676881477683
created: 1676881477683
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# tree

> Display a graphical tree of the directory structure for a path.
> More information: <https://learn.microsoft.com/windows-server/administration/windows-commands/tree>.

- Display the tree for the current directory:

`tree`

- Display the tree for a specific directory:

`tree {{path\to\directory}}`

- Display the tree for a directory including files:

`tree {{path\to\directory}} /f`

- Display the tree using ASCII characters instead of extended characters:

`tree {{path\to\directory}} /a`

