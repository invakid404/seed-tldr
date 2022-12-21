---
id: windows.wait-process
title: Wait Process
desc: ''
updated: 1671599771483
created: 1671599771483
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# Wait-Process

> Waits for the processes to be stopped before accepting more input.
> This command can only be used through PowerShell.
> More information: <https://learn.microsoft.com/powershell/module/microsoft.powershell.management/wait-process>.

- Stop a process and wait:

`Stop-Process -Id {{process_id}}; Wait-Process -Id {{process_id}}`

- Wait for processes for a specified time:

`Wait-Process -Name {{process_name}} -Timeout {{30}}`

