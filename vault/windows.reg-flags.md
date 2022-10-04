---
id: windows.reg-flags
title: Reg Flags
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
# reg flags

> Display or set flags on registry keys.
> More information: <https://learn.microsoft.com/windows-server/administration/windows-commands/reg-flags>.

- Display current flags for a specific key:

`reg flags {{key_name}} query`

- Display help and available flag types:

`reg flags /?`

- Set specified space-separated flags, and unset unmentioned flags, for a specific key:

`reg flags {{key_name}} set {{flag_names}}`

- Set specified flags for a specific key and its sub keys:

`reg flags {{key_name}} set {{flag_names}} /s`

