---
id: windows.cd
title: CD
desc: ''
updated: 1666859373525
created: 1666859373525
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# cd

> Display the current working directory or move to a different directory.
> More information: <https://learn.microsoft.com/windows-server/administration/windows-commands/cd>.

- Display the path of the current directory:

`cd`

- Go to root of current drive:

`cd \`

- Go up to the parent of the current directory:

`cd ..`

- Go to a specific directory in the same drive:

`cd {{path\to\directory}}`

- Go to a specific directory in a different [d]rive:

`cd /d {{C}}:{{path\to\directory}}`

