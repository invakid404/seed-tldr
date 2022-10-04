---
id: windows.reg-unload
title: Reg Unload
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
# reg unload

> Remove data from the registry that was loaded using the `reg load` command.
> More information: <https://learn.microsoft.com/windows-server/administration/windows-commands/reg-unload>.

- Remove data from the registry for a specified key:

`reg unload {{key_name}}`

