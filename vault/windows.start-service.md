---
id: windows.start-service
title: Start Service
desc: ''
updated: 1671599771482
created: 1671599771482
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# Start-Service

> Starts one or more stopped services.
> This command can only be used through PowerShell.
> More information: <https://learn.microsoft.com/powershell/module/microsoft.powershell.management/start-service>.

- Start a service by using its name:

`Start-Service -Name {{service_name}}`

- Display information without starting a service:

`Start-Service -DisplayName *{{name}}* -WhatIf`

- Start a disabled service:

`Set-Service {{service_name}} -StartupType {{manual}}; Start-Service {{service_name}}`

