---
id: windows.stop-service
title: Stop Service
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
# Stop-Service

> Stops one or more running services.
> This command can only be used through PowerShell.
> More information: <https://learn.microsoft.com/powershell/module/microsoft.powershell.management/stop-service>.

- Stop a service on the local computer:

`Stop-Service -Name {{service_name}}`

- Stop a service by using the display name:

`Stop-Service -DisplayName "{{name}}"`

- Stop a service that has dependent services:

`Stop-Service -Name {{service_name}} -Force -Confirm`

