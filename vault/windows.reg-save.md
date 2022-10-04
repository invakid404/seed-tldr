---
id: windows.reg-save
title: Reg Save
desc: ''
updated: 1664897374265
created: 1664897374265
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# reg save

> Save a registry key, its sub keys and values to a file.
> More information: <https://learn.microsoft.com/windows-server/administration/windows-commands/reg-save>.

- Save a registry key, its sub keys and values to a specific file:

`reg save {{key_name}} {{path/to/file}}`

- Forcefully overwrite an existing file without a prompt:

`reg save {{key_name}} {{path/to/file}} /y`

