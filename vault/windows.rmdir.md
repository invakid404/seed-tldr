---
id: windows.rmdir
title: Rmdir
desc: ''
updated: 1676881477682
created: 1676881477682
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# rmdir

> Remove a directory and its contents.
> More information: <https://learn.microsoft.com/windows-server/administration/windows-commands/rmdir>.

- Remove an empty directory:

`rmdir {{path\to\directory}}`

- Remove a directory and its contents recursively:

`rmdir {{path\to\directory}} /s`

- Remove a directory and its contents recursively without prompting:

`rmdir {{path\to\directory}} /s /q`

