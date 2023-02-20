---
id: windows.reg-load
title: Reg Load
desc: ''
updated: 1676881477681
created: 1676881477681
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# reg load

> Load saved sub keys into a different sub key in the registry.
> This is intended for troubleshooting and temporary keys.
> More information: <https://learn.microsoft.com/windows-server/administration/windows-commands/reg-load>.

- Load a backup file into the specified key:

`reg load {{key_name}} {{path\to\file}}`

