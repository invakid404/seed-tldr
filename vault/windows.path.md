---
id: windows.path
title: Path
desc: ''
updated: 1676881477680
created: 1676881477680
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# path

> Display or set the search path for executable files.
> More information: <https://learn.microsoft.com/windows-server/administration/windows-commands/path>.

- Display the current path:

`path`

- Set the path to one or more semicolon-separated directories:

`path {{path\to\directory1 path\to\directory2 ...}}`

- Append a new directory to the original path:

`path {{path\to\directory}};%path%`

- Set command prompt to only search the current directory for executables:

`path ;`

