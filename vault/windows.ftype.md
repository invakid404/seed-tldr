---
id: windows.ftype
title: Ftype
desc: ''
updated: 1664897374262
created: 1664897374262
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ftype

> Display or modify file types used for file extension association.
> More information: <https://learn.microsoft.com/windows-server/administration/windows-commands/ftype>.

- Display a list of all file types:

`ftype`

- Display the associated program for a specific file type:

`ftype {{file_type}}`

- Set the associated program for a specific file type:

`ftype {{file_type}}="{{path/to/executable_command}}"`

