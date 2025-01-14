---
id: windows.taskkill
title: Taskkill
desc: ''
updated: 1664897374267
created: 1664897374267
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# taskkill

> Terminate a process by its process ID or name.
> More information: <https://learn.microsoft.com/windows-server/administration/windows-commands/taskkill>.

- Terminate a process by its ID:

`taskkill /pid {{process_id}}`

- Terminate a process by its name:

`taskkill /im {{process_name}}`

- Forcefully terminate a specified process:

`taskkill /pid {{process_id}} /f`

- Terminate a process and its child processes:

`taskkill /im {{process_name}} /t`

- Terminate a process on a remote machine:

`taskkill /pid {{process_id}} /s {{remote_name}}`

- Display information about the usage of the command:

`taskkill /?`

