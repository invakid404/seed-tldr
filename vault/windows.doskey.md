---
id: windows.doskey
title: Doskey
desc: ''
updated: 1676881477677
created: 1676881477677
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# doskey

> Manage macros, windows commands and command-lines.
> More information: <https://learn.microsoft.com/windows-server/administration/windows-commands/doskey>.

- List available macros:

`doskey /macros`

- Create a new macro:

`doskey {{name}} = "{{command}}"`

- Create a new macro for a specific executable:

`doskey /exename={{executable}} {{name}} = "{{command}}"`

- Remove a macro:

`doskey {{name}} =`

- Display all commands that are stored in memory:

`doskey /history`

- Save macros to a file for portability:

`doskey /macros > {{path\to\macinit_file}}`

- Load macros from a file:

`doskey /macrofile = {{path\to\macinit_file}}`

