---
id: windows.tskill
title: Tskill
desc: ''
updated: 1664897374268
created: 1664897374268
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# tskill

> Ends a process running in a session on a Remote Desktop Session Host.
> More information: <https://learn.microsoft.com/windows-server/administration/windows-commands/tskill>.

- Terminate a process by its process identifier:

`tskill {{process_id}}`

- Terminate a process by its name:

`tskill {{process_name}}`

